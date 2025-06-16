# Hospital-Management-System
🏥 Hospital Management System
A web-based Hospital Management System (HMS) designed to streamline hospital operations such as patient registration, doctor appointments, prescription management, and user communication through an organized and digitized platform.

📌 Project Overview
This system was developed as a semester project to demonstrate the application of database management and web development concepts in a real-life healthcare scenario. It aims to eliminate paperwork, reduce human errors, and enhance the overall experience for both hospital staff and patients.

🚩 Problem Statement
Many hospitals still manage data manually, leading to issues like:

Lost or misplaced patient records
Confusing appointment schedules
Long queues and inefficient patient handling
This system addresses these problems by digitizing hospital workflows and enabling easy access to patient and doctor data.

🏥 Real-Life Use Case
A medium-sized hospital in Rawalpindi could implement this HMS to:

Schedule appointments with doctors
Record and view prescriptions
Manage doctor-patient data more efficiently
Reduce administrative workload and improve patient care
✅ Features
👤 Admin
Secure login
Dashboard with admin controls
🧑‍⚕️ Doctor
Secure login
View scheduled appointments
Write and manage patient prescriptions
🧑 Patient
Register and log in
Book appointments
View prescription history
🌐 General
Role-based dashboards (Admin, Doctor, Patient)
Contact form for feedback/messages
User session management
Basic form validation
🔧 Tech Stack
Frontend: HTML, CSS
Backend: PHP
Database: SQL Server
🧠 Requirements Analysis
Functional Requirements
Admin login and management
Doctor login, appointment viewing, and prescription writing
Patient registration, login, and appointment booking
Role-based dashboard interface
Contact form for messages
Non-Functional Requirements
Fast and reliable performance
Secure login with validation
User-friendly UI/UX
Scalable database structure
Maintainable code and structure
🗄️ Database Design
Tables and Relationships
admint: Admin login data (PK: username)
doctb: Doctor data (PK: username)
patreg: Patient registration (PK: pid)
appointmenttb: Appointment records (PK: ID, FK: pid)
prestb: Prescription records (FKs: pid, ID, and logical doctor reference)
contact: User messages (no PK)
Key Design Features
Use of primary and foreign keys for relational integrity
Logical references between doctor and appointment/prescription tables
Scalable schema for future modules
💡 Challenges & Learnings
Challenges
Establishing correct foreign key relationships
Managing role-specific login and session handling
Dynamic dashboards per user role
Learnings
Database normalization and entity design
Writing secure and efficient SQL queries
Frontend-backend integration in PHP
Real-world relevance of keys and constraints
🔮 Future Improvements
Add support for lab reports and file uploads
Enable email notifications for appointments
Responsive design for mobile users
Downloadable reports (PDF/Excel)
Analytics dashboard to monitor doctor performance
📌 Conclusion
Our Hospital Management System provides a modern, digital solution to manage essential hospital operations. By automating patient registration, appointments, and prescriptions, the system reduces workload and error while improving communication and clarity.
