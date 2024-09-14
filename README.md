# College Management System in Java

Welcome!

This project is a fully designed and developed **College Management System** using **Java Swing** for the front-end and **MySQL** for the back-end database. The entire design and implementation are original and self-written.

## Features

### Common Features:
- **Courses Management**: Add, update, and manage course details.
- **Subjects Management**: Manage subjects for different courses.
- **Students Management**: Maintain student details including registration, attendance, and performance.
- **Faculties Management**: Manage faculty details and their assigned subjects.
- **Student Attendance Management**: Track and record student attendance.
- **Student Marks Management**: Store and manage student marks and performance data.

### Advanced Features 🔥:
- **Roll Number Generator**: Automatically generate roll numbers for students.
- **Chatting**: Real-time chat functionality between users.
  - **Message Delivered**: Indicator for message delivery status.
  - **Unseen Messages**: Notifications for unread messages.
- **Notifications**: Real-time notifications for important events.
- **Group Chatting**: Create chat groups for students or faculties.
- **Photo View**: Display profile photos of students and faculty.
- **Login History**: Track login history for students and faculty.
- **Download Marksheet**: Generate and download student marksheets.
- **Declare Result**: Publish exam results for students.

## Installation

1. **Import the project into your IDE**.
2. **Create a new MySQL database** named `collegedata` and import the provided `collegedata.sql` file (attached in the project folder).
   
### Database Connection
To connect to the MySQL database, the following configuration is used:
```java
url = "jdbc:mysql://localhost:3306/Collegedata";
username = "root";
password = "";
```
If you want to change this configuration, navigate to `.\src\collegeapplication\common\DataBaseConnection.java` and modify the connection details as per your requirements.

## How to Run

1. **Start the MySQL Database Server**.
2. Navigate to `src/collegeapplication/chat/Server.java` and run this file to start the chat server.
3. Navigate to `src/collegeapplication/login/LoginPageFrame.java` and run this file to launch the main application.

### Admin Credentials:
- **UserID**: admin  
- **Password**: admin  

### Faculty Login:
- Use the **Faculty ID** to log in.

### Student Login:
- The format for student login is:  
  `course-semester-rollnumber`  
  Example: `IT-1-1001`  

## Thanks for exploring the College Management System!  
Feel free to reach out if you have any questions or suggestions.

---

Happy Coding!
