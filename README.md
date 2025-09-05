# student-management-system

🎓 Student Management System
A simple Python-based Student Management System developed as a capstone project for the RITA Africa Python Fundamentals Course. This application allows secure login, student record management (CRUD), report generation, and file-based data persistence.

🚀 Features

Authentication System – Secure login with user accounts stored in users.txt
Student Data Management – Add, view, search, update, and delete student records
Report Generation – Generate basic reports on total students and grade distribution
Activity Logging – Tracks user logins, logouts, and actions in activity_log.txt
File-Based Storage – Data is stored in text files (students.txt, users.txt) for persistence

🛠️ Technologies Used
Python 3.x
File Handling (TXT)
Datetime module (for logging timestamps)
Getpass module (for hidden password entry)

📂 Project Structure
student_management_system/
│── student-management-system.py # Main program (menu-driven interface)
│── users.txt # Stores usernames and passwords
│── students.txt # Stores student records
│── activity_log.txt # Stores user activity logs
How to Run

Clone this repository:
git clone https://github.com/yourusername/student-management-system.git
cd student-management-system
Run the program:
python student-management-system.py
If running for the first time, create an Admin account when prompted.

Usage

Login with a valid username and password.
Use the menu to:
Add a new student
View all students
Search for a student by roll number
Update student details
Delete student records
Generate a student report
Logout : when done (session activity will be logged).
Sample Report Output

Student Report

Total Students: 4
Grade A: 2 student(s)
Grade B: 1 student(s)
Grade C: 1 student(s)

Acknowledgements

This project was created as part of the RITA Africa Python Fundamentals Bootcamp. Special thanks to RITA AFRICA
