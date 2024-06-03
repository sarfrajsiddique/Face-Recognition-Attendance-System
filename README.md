This project is a Face Recognition Attendance System built using a full-stack Java application. It leverages facial recognition technology to automate and streamline the process of tracking and managing attendance. The system is composed of a front-end interface, a back-end server, and a database to store the attendance records.

Features
User Authentication: Secure login for administrators and users.
Face Detection and Recognition: Capture and recognize faces using a webcam.
Attendance Management: Mark attendance based on face recognition.
Admin Dashboard: View, edit, and manage attendance records.
Reports Generation: Generate attendance reports for specified periods.
Real-time Notifications: Notify users about their attendance status in real-time.
Technologies Used
Setup Instructions
Prerequisites
Java 11 or higher
Maven
MySQL
OpenCV (Java bindings)
Database Setup
Install MySQL and create a database named attendance_system.
Run the SQL script provided in database/schema.sql to create the necessary tables.
Backend Setup
Navigate to the backend directory.
Update the application.properties file with your MySQL database credentials.
Run the following command to build and start the backend server:
sh
Copy code
mvn spring-boot:run
Frontend Setup
Navigate to the frontend directory.
Build and run the frontend application using the following command:
sh
Copy code
mvn javafx:run
Running the Application
Access the frontend application to interact with the face recognition attendance system.
The admin dashboard is available at /admin after logging in as an administrator.
Usage
Register Users: Register users with their images in the system.
Mark Attendance: Users can mark their attendance by scanning their face using the webcam.
View Attendance: Admin can view the attendance records and generate reports.
Contribution
Contributions are welcome! Please fork this repository and submit pull requests.

License
This project is licensed under the MIT License - see the LICENSE file for details.
