# Attendance Management System

## Overview

The **Attendance Management System** is designed to streamline the process of registering students and marking attendance using **face recognition**. It provides a user-friendly interface for administrators and students, making it easy to manage student registrations and attendance records. The system ensures accurate tracking by leveraging modern technologies like **OpenCV** for real-time face detection and recognition.

---

## Features

1. **Student Registration**  
   - Allows new students to register by capturing their face through a live photo.
   - Stores student details (name, batch, enrollment number) in an SQLite database.
   - Saves the student's face encoding for future recognition.

2. **Attendance Marking**  
   - Automatically marks attendance based on real-time face recognition during class hours.
   - Allows admins to capture a snapshot during class and mark attendance.

3. **Real-Time Monitoring**  
   - Admins can view and track real-time attendance for ongoing classes.

4. **Database Integration**  
   - All student and attendance data is stored in a secure **SQLite** database.
   - **Face encodings** are stored in a **pickle file** for quick retrieval.

---

## Installation

To install and run this system, follow the steps below:

### 1. Clone the repository

```bash
git clone https://github.com/your-username/attendance-management-system.git
cd attendance-management-system
## 2. Install the required dependencies

Make sure you have Python 3 installed, then install the necessary libraries.

```bash
pip install -r requirements.txt
3. Run the system

You can run the system by executing the following command:

python main.py
The system will prompt you to either register a new student or mark attendance.

How to Use

Register a New Student:
After running the system, select option 1 to register a student.
The system will ask for the student's name, batch, and ID.
After entering the details, a live photo will be captured for face recognition.
Mark Attendance:
Select option 2 to mark attendance for a subject.
The system will capture a live image of the class and match the faces to the stored data to mark attendance.
Future Updates

In future updates, the following features and improvements are planned to enhance the system:

1. Real-Time Attendance Dashboard
A dynamic dashboard where the admin can see the real-time attendance for each ongoing lecture.
Visual Representation of attendance with graphs and statistics.
2. Email Notification System
Automatic email notifications to students when their attendance is marked.
Daily/Weekly Reports sent to students and teachers for attendance summaries.
3. Facial Recognition with Liveness Detection
Implement liveness detection to prevent fraud by ensuring that the captured image is from a real person (not a photo or video).
This feature will ask users to blink or smile during the registration process.
4. Class Schedule Integration
Automatically trigger the attendance marking process based on the class schedule.
The system will capture and process the students' faces at the scheduled time slots for each class.
5. AI Chatbot for Student Queries
A chatbot integrated into the system to assist students and teachers with queries related to attendance.
Students can ask about their attendance status, missing classes, and more.
6. Student and Teacher Role Management
Role-based access control for different users.
Admin: Can view and manage all student records and attendance.
Teacher/Student: Can view their attendance records and class schedules.
7. AI-Powered Student Monitoring
AI models will be used to measure student engagement during classes based on facial expressions and body language.
Provide insights into student participation in real-time.
8. Data Backup & Recovery
Implement automatic backups of the database to prevent data loss.
Restore functionality to recover data in case of corruption or accidental deletion.
9. Custom Attendance Reports
Ability to generate customized attendance reports based on specific parameters such as date, subject, or student.
Generate monthly/semester-based reports for teachers and students.
10. Admin Dashboard with Analytics
A comprehensive admin dashboard to track attendance trends across classes and students.
Generate visual reports and provide detailed attendance analytics for improved decision-making.
Contribution

If you want to contribute to this project, feel free to fork the repository and submit a pull request with your changes. We welcome contributions that enhance the functionality and usability of the system.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments

OpenCV for face recognition.
SQLite for database management.
smtplib for email integration (future updates).

This should now be ready to use as a fully formatted **Markdown** README file. Let me know if you need any more adjustments!