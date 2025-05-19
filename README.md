# Student Exam Portal
A comprehensive online examination platform built with PHP and PostgreSQL that allows administrators to create and manage exams while providing students with a controlled testing environment featuring real-time timers.

![Dashboard](https://github.com/itspiyush3451/Student-Exam-Portal/raw/main/UI/DashBoard.jpeg)

## Features
- **Real-time Exam Timer**: Countdown timer for exam duration
- **Admin Dashboard**: Complete exam and user management system
- **Student Interface**: User-friendly exam-taking environment
- **Feedback System**: Collect student feedback on exam experience
- **Ranking System**: View performance rankings based on exam results
- **Question Management**: Create, edit, and delete exam questions
- **User Authentication**: Secure login for admins and students

## UI Showcase
### Main Interfaces
<div align="center">
  <img src="https://github.com/itspiyush3451/Student-Exam-Portal/raw/main/UI/DashBoard.jpeg" width="400" alt="Dashboard">
  <img src="https://github.com/itspiyush3451/Student-Exam-Portal/raw/main/UI/ExamPortal.jpeg" width="400" alt="Exam Portal">
</div>

### Admin Management
<div align="center">
  <img src="https://github.com/itspiyush3451/Student-Exam-Portal/raw/main/UI/ManageUsers.jpeg" width="400" alt="Manage Users">
  <img src="https://github.com/itspiyush3451/Student-Exam-Portal/raw/main/UI/ManageCourse.jpeg" width="400" alt="Manage Course">
  <img src="https://github.com/itspiyush3451/Student-Exam-Portal/raw/main/UI/ManageExam.jpeg" width="400" alt="Manage Exam">
</div>

### Student Experience
<div align="center">
  <img src="https://github.com/itspiyush3451/Student-Exam-Portal/raw/main/UI/Result.jpeg" width="400" alt="Result">
  <img src="https://github.com/itspiyush3451/Student-Exam-Portal/raw/main/UI/Rank.jpeg" width="400" alt="Rank">
</div>

### Feedback System
<div align="center">
  <img src="https://github.com/itspiyush3451/Student-Exam-Portal/raw/main/UI/Feedback.jpeg" width="400" alt="Feedback">
  <img src="https://github.com/itspiyush3451/Student-Exam-Portal/raw/main/UI/FeedbackForm.jpeg" width="400" alt="Feedback Form">
</div>

## Prerequisites
- XAMPP or any local server environment with PHP and MySQL support
- Knowledge of PHP, PostgreSQL, HTML, CSS, and JavaScript

## Installation
### 1. Clone the Repository
```bash
git clone https://github.com/itspiyush3451/Student-Exam-Portal.git
```

### 2. Copy Project Files
Move the Student-Exam-Portal folder to your server's web directory:
- Windows: `C:/xampp/htdocs/`
- Linux/Mac: `/opt/lampp/htdocs/`

### 3. Database Setup
- Open phpMyAdmin in your browser
- Create a new database named `cee_db`
- Import the SQL file from the project's `db/cee_db.sql`

### 4. Launch the Application
- Start Apache and MySQL services in XAMPP Control Panel
- Access the application:
  - Student Interface: `http://localhost/Student-Exam-Portal/`
  - Admin Panel: `http://localhost/Student-Exam-Portal/adminpanel/`

## Admin Access
Use these credentials to access the admin panel:
- **Username:** admin@username
- **Password:** admin@password

## How to Use
### For Administrators
1. Log in to the admin panel
2. Create courses and manage users
3. Create exams and add questions
4. View student results and feedback

### For Students
1. Log in to the student interface
2. Select available exams
3. Complete exams within the allocated time
4. View results and rankings

## Contributing
Contributions are welcome to help improve this system:
1. Fork the repository
2. Create a new branch for your feature (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is open-source and available for educational purposes only. You may use, modify, and distribute it as long as it's for non-commercial purposes.

## Contact
Project Link: [https://github.com/itspiyush3451/Student-Exam-Portal](https://github.com/itspiyush3451/Student-Exam-Portal)
