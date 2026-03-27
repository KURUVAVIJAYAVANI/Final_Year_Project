📊 Smart QR-Based Attendance Monitoring System


📌 Project Overview

The Smart QR-Based Attendance Monitoring System is a web-based application designed to automate and secure the attendance process using dynamically generated QR codes. It eliminates manual attendance errors and prevents proxy attendance through time-based validation.

🚀 Features
✅ Dynamic QR Code Generation (changes every 10 seconds)
✅ Secure Student Authentication
✅ Real-time Attendance Marking
✅ Admin Dashboard for Monitoring
✅ Subject-wise Attendance Tracking
✅ Automatic Percentage Calculation
✅ MySQL Database Integration
✅ Responsive User Interface
🛠️ Technologies Used

Frontend: HTML, CSS, JavaScript
Backend: Node.js
Database: MySQL
Other Tools: QR Code Generator Library


📂 Project Structure
Smart-QR-Attendance/
│── admin/
│   ├── admin_login.php
│   ├── dashboard.php
│   ├── generate_qr.php
│
│── student/
│   ├── student_login.php
│   ├── scan_qr.php
│
│── database/
│   ├── attendance.sql
│
│── assets/
│   ├── css/
│   ├── js/
│
│── index.php
│── README.md


⚙️ How It Works (Step-by-Step)
1️⃣ Admin Login
Admin logs into the system using credentials.
Redirected to the admin dashboard.
2️⃣ QR Code Generation
Admin selects subject.
System generates a dynamic QR code valid for a limited time (e.g., 10 seconds).
3️⃣ Student Login
Students log in using their credentials (Roll No & Password).
4️⃣ QR Code Scanning
Students scan the QR code using the system interface.
QR code is validated in real-time.
5️⃣ Attendance Marking
If QR is valid:
Attendance is marked successfully.
If expired/invalid:
Access is denied.
6️⃣ Data Storage
Attendance data is stored in MySQL database.
Includes:
Roll Number
Subject
Date & Time
7️⃣ Dashboard & Reports
Admin can:
View attendance records
Track subject-wise attendance
Calculate overall percentage


🧩 Database Design
Tables:
students
admin
subjects
attendance


📊 Sample Output
Attendance Dashboard showing:
Student Details
Subject-wise attendance
Overall Percentage


💡 Advantages
⏱️ Saves time compared to manual attendance
🔒 Reduces proxy attendance
📈 Easy tracking and reporting
🌐 Scalable for institutions


⚠️ Challenges Faced
Real-time QR validation
Handling multiple users simultaneously
Preventing QR reuse after expiry
Database optimization for faster queries
🔮 Future Enhancements
Face Recognition Integration
Firebase/Cloud Integration
Mobile App Version
Two-Factor Authentication


🧑‍💻 How to Run the Project
Install XAMPP/WAMP
Place project folder in htdocs
Start Apache & MySQL
Import attendance.sql into phpMyAdmin

Open browser:

http://localhost/Smart-QR-Attendance/
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/3fc1e6e5-c834-49e7-bd64-2be41a76c22d" />



🏁 Conclusion

This project demonstrates the use of web technologies and QR-based authentication to build a secure and efficient attendance system. It highlights skills in full-stack development, database management, and real-time validation systems.
