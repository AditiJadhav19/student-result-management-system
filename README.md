# Student Result Management System

## 📌 Overview

The Student Result Management System is a web-based application designed to manage and display student results efficiently. It allows administrators to manage student records, subjects, and results, while students can view their individual results.

## 🔍 Table of Contents

- [📝 Project Summary](#-project-summary)
- [💻 Stack](#-stack)
- [⚙️ Setting Up](#-setting-up)
- [🚀 Run Locally](#-run-locally)
- [📂 Project Structure](#-project-structure)

## 📝 Project Summary

The Student Result Management System provides the following features:
- Admin panel to manage students, subjects, and results.
- User interface for students to view their results.
- Secure authentication and authorization for admin and student roles.

## 💻 Stack

- Frontend: HTML, CSS, JavaScript, Bootstrap
- Backend: PHP
- Database: MySQL

## ⚙️ Setting Up

### Prerequisites

- PHP installed
- MySQL installed
- Web server (e.g., Apache) installed

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/student-result-management-system.git
   ```

2. Navigate to the project directory:
   ```sh
   cd student-result-management-system
   ```

3. Import the database:
   - Create a database named `student_result_management` in MySQL.
   - Import the SQL file located at `database/student_result_management.sql` into the `student_result_management` database.

4. Configure the database connection:
   - Open `config.php` file.
   - Update the database connection details (host, username, password, database name).

## 🚀 Run Locally

1. Start the web server (e.g., Apache) and ensure PHP and MySQL are running.

2. Open a web browser and navigate to `http://localhost/student-result-management-system`.

3. You should see the Student Result Management System homepage.

## 📂 Project Structure

```
student-result-management-system/
│
├── add_student.php
├── add_subject.php
├── add_result.php
├── config.php
├── index.php
├── login.php
├── register.php
├── view_students.php
├── view_results.php
└── database/
    └── student_result_management.sql
```