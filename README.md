# cms
College Management System (SMS)
A simple and efficient College Management System developed using PHP and MySQL. This system allows you to manage student records, including adding, updating, viewing, and deleting college information, along with the management of their classes.

Features
College CRUD Operations: Add, view, edit, and delete student information.
Class Management: Create and manage student classes.
Responsive Design: Designed with Bootstrap for responsive and user-friendly interfaces.
Database Integration: Utilizes MySQL to store data securely.
Tech Stack
Frontend: HTML, CSS, JavaScript, Bootstrap
Backend: PHP
Database: MySQL
Version Control: GitHub
Installation
Prerequisites
Make sure you have the following installed on your system:

XAMPP or WAMP (for local PHP and MySQL server)
Git (for cloning the repository)
Steps to Install
Clone the repository:
git clone https://github.com/your-username/college-management-system.git
2.Set up your local server:

Move the project folder to the htdocs directory (for XAMPP) or the corresponding directory for your local server.

3.Create a MySQL database:

Open phpMyAdmin from your local server (usually http://localhost/phpmyadmin). Create a new database called student_management_system.

4.Import the database schema:

Go to the SQL tab in phpMyAdmin and paste the contents of schema.sql (provided in the project files) to create the necessary tables.

5.Configure database connection:

Open db.php in your project directory and update the database connection details (hostname, username, password, and database name).

6.Run the project:

Open your browser and go to http://localhost/college-management-system.
