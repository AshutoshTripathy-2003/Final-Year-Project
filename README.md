# RUniverse

This repository contains the source code for the Academic Management System developed for Ravenshaw University, Mahanadi Campus. The system aims to streamline the administration of student, faculty, and course management. It provides features for both admin and student users, supporting functionalities like student registration, mark entry, profile management, internal communications, and more.

📂 Folder Structure
adminpage/: Contains the admin panel with functionalities to manage students, upload marks, and promote students.

studentpage/: Includes pages for student login, profile management, and accessing study materials.

teacherpage/: Contains the teacher dashboard for profile management and student interaction.

self_assesment/: Includes self-assessment tests on various topics for student mental health and stress management.

assets/: Static files such as images, logos, and CSS files.

uploads/: Folder for uploaded student and teacher profile pictures.

includes/: Contains the database connection script.

PHPMailer/: Handles email functionalities for password reset and notifications.

homepage/: Landing page of the university with features like events, courses, and institutional vision.

🚀 Features
Admin Features:

Manage students' profiles and marks.

Promote students to the next year/semester.

View and manage notices and events.

Upload and manage study materials.

Student Features:

View marks and academic progress.

Edit personal profile and change passwords.

Access and download study materials.

Self-assessment for mental well-being.

Teacher Features:

Manage and upload marks.

View student profiles and internal communications.

🛠️ Technologies Used
Frontend: HTML, CSS, JavaScript

Backend: PHP

Database: MySQL

Email: PHPMailer for email functionalities (password reset, notifications)

Other: Responsive design using custom CSS files

⚡ Installation
To run this project locally:

Clone the repository:

bash
Copy
Edit
git clone https://github.com/AshutoshTripathy-2003/Final-Year-Project.git
cd Final-Year-Project
Set up the database:

Create a MySQL database and import the schema.

Update the db_connection.php file with your database credentials.

Start a local server:

You can use XAMPP or any local PHP server to run the project.

Place the project in the htdocs folder (for XAMPP) or your server directory.

Access the system:

Admin page: http://localhost/adminpage/login.php

Student page: http://localhost/studentpage/login.php

📝 Configuration
Database Configuration: Update your MySQL credentials in the includes/db.php file.

Email Configuration: Ensure the correct email settings are configured in the PHPMailer folder for functionalities like password reset.
