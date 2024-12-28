# Student Exam Portal

An online examination system built with PHP and MySQL, designed to provide a seamless experience for both administrators and students. The system includes a timer for each exam and a user-friendly interface for exam management.

## Table of Contents

- [Project Overview](#project-overview)
- [Implementation](#implementation)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [How To Run](#how-to-run)
- [Admin Login Access Information](#admin-login-access-information)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The Student Exam Portal provides a platform for online examinations, where administrators can create and manage exams, and students can take exams in a controlled environment. The platform features a real-time timer for exams and is built with PHP and MySQL.

## Implementation

The system allows the following:

- **Admin Panel:** Admins can create exams, manage questions, view results, and more.
- **Student Interface:** Students can take exams with a real-time countdown timer.

The application is designed to be easily extendable and customizable for various use cases and can be deployed in any PHP-supported server environment.

## Prerequisites

Before you begin, ensure you have the following software installed:

- [XAMPP](https://www.apachefriends.org/index.html) or any local server environment that supports PHP and MySQL.
- Basic knowledge of PHP, MySQL, and web application deployment.

## Getting Started

To get the project up and running, follow the steps below:

### 1. Clone the repository

Clone the repository to your local machine:

```bash
git clone https://github.com/itspiyush3451/Student-Exam-Portal.git

### 2. Copy the Project Folder

Move the `Student-Exam-Portal` folder into the `htdocs` directory of your XAMPP installation. The path is usually:

- On **Windows:** `C:/xampp/htdocs/`
- On **Linux/Mac:** `/opt/lampp/htdocs/`

### 3. Database Configuration

- Open [phpMyAdmin](http://localhost/phpmyadmin/) in your browser.
- Create a new database named `cee_db`.
- Import the SQL file (`cee_db.sql`) provided in the `db` folder of the project.

### 4. Launch the Application

After setting up the database, you can access the application:

- **Student Interface:** Go to `http://localhost/Student-Exam-Portal/` in your browser.
- **Admin Panel:** Go to `http://localhost/Student-Exam-Portal/adminpanel/` in your browser.

## How To Run

To run the system locally:

1. Start **Apache** and **MySQL** in the XAMPP Control Panel.
2. Follow the steps above to copy the project to `htdocs` and set up the database.
3. Open your browser and access the system at the provided URLs.

## Admin Login Access Information

- **Username:** admin@username
- **Password:** admin@password

Use these credentials to access the admin panel.

## Features

- **Real-time Timer:** A timer counts down during the exam.
- **Admin Panel:** Admins can create and manage exams, view student results, etc.
- **Student Panel:** Students can take the exam, view questions, and submit answers.
- **Question Management:** Admins can create, edit, and delete exam questions.

## Contributing

We welcome contributions to improve the system. If you want to contribute, you can:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make changes and commit them.
4. Submit a pull request.

Your contributions can help others build upon and improve this system.

## License

This project is open-source and available for educational purposes only. Feel free to use, modify, and distribute it as long as it's used for non-commercial purposes.

---

