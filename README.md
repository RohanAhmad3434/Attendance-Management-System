📚 Attendance Management System

A full-stack web-based Attendance Management System designed to simplify attendance tracking in educational institutions. It supports user management, course scheduling, attendance tracking, and PDF report generation, with dedicated roles for Admins, Teachers, and Students.


🚀 Project Overview:
The Attendance Management System is a comprehensive solution built to automate the attendance process. Admins can manage users and courses, assign timetables, and generate attendance reports. Teachers can mark attendance based on schedule, and students can view their own records.


🌟 Features by Role

1)👤 Admin Panel:
- Create, update, and delete users (students, teachers)
- Assign courses to teachers and enroll students
- Create and manage course timetables
- Generate attendance reports in PDF format
- View attendance by course and date

2)👨‍🏫 Teacher Panel:
- View assigned courses
- Mark attendance for students in scheduled classes
- View attendance history

 3)👨‍🎓 Student Panel:
- View personal attendance records
- View course and timetable info


🔧 Tech Stack:

Frontend: HTML, CSS, JavaScript  
Backend: Spring Boot (Java)  
Database: MySQL  
Tools: 
  - Postman (API Testing)
  - Spring Boot DevTools (Live Reload)
  - GitHub (Version Control)
  - Maven (Build & Dependency Management)


🗂️ Functional Requirements

- Admins can add/remove users and assign them roles (teacher/student)
- Courses and timetables are managed by the admin
- Attendance is recorded **only when a course is scheduled**
- Teachers can mark and update attendance
- Students can access only their own attendance data
- PDF export feature for attendance reports


🛠️ How to Run Locally

🔹 Step 1: Clone the Repository:
git clone https://github.com/RohanAhmad3434/Attendance-Management-System.git
cd Attendance-Management-System

🔹 Step 2: Set Up the Backend (Spring Boot)
Open the Backend folder in IntelliJ IDEA, Eclipse, or Spring Tool Suite.

Configure your MySQL database in:
Backend/src/main/resources/application.properties
Update fields like:

spring.datasource.username=your_username
spring.datasource.password=your_password
spring.datasource.url=jdbc:mysql://localhost:3306/attendance_db
Make sure MySQL is running and the database attendance_db is created.

Run the application by starting:
AttendanceManagementApplication.java

🔹 Step 3: Set Up the Frontend
Navigate to the Frontend folder.
Open index.html in any web browser.
Make sure the frontend is calling the correct backend API endpoints (e.g., http://localhost:8080/...) in your JavaScript files.

✅ Result
You should now be able to:
Access the app interface from your browser.
Perform admin, teacher, and student actions as per the role-based UI.
View, mark, and export attendance records.
