# CampusCore – Student Portal

**Subject:** Web Development Frameworks (ITUE203)  
**Institution:** CHARUSAT – Devang Patel Institute of Advance Technology and Research  
**Academic Year:** 2026–27  
**Semester:** 3  
**Student:** Neel Patel  
**Enrollment No.:** 25DCS093

## GitHub Repository

**Repository:** [WDF-Practicals](https://github.com/NeelPatel2407/WDF-Practicals)

Clone the repository using:

git clone https://github.com/NeelPatel2407/WDF-Practicals.git
cd WDF-Practicals

## Project Overview

CampusCore is a student portal developed as part of the Web Development Frameworks practical course. It brings together frontend web pages, JavaScript interactivity, PHP server-side processing, and MySQL database functionality.

## Features

- **User Registration and Authentication:** User registration, secure password hashing, login, and logout.
- **Session Management:** Session-based authentication, role-based access control, and inactivity timeout.
- **Student Management:** Create, view, update, delete, search, and filter student records.
- **Event Management:** Manage campus events and event poster uploads.
- **JSON API:** Fetch/AJAX-based CRUD operations without reloading the page.
- **Admin Dashboard:** Display project statistics and provide access to administrative features.
- **Audit Logs:** Record and view administrative activity.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- PHP
- MySQL
- XAMPP
- Git and GitHub

## Project Structure

WDF-Practicals/
├── PRACTICAL-01/
├── PRACTICAL-2/
├── PRACTICAL-03/
├── PRACTICAL-04/
├── PRACTICAL-05/
├── PRACTICAL-06/
├── PRACTICAL-7/
├── PRACTICAL-8/
├── PRACTICAL-9/
├── PRACTICAL-10/
├── PRACTICAL-11/
├── PRACTICAL-12/
├── PRACTICAL-13/
├── PRACTICAL-14/
└── README.md

Each practical folder contains the files associated with its respective exercise. File names and contents may vary.

## Requirements

- XAMPP with Apache and MySQL
- A modern web browser
- Visual Studio Code or another code editor
- Git for version control

## Installation and Setup

1. Install and open XAMPP.
2. Start Apache and MySQL.
3. Clone the repository or download the project from GitHub.
4. Place the project folder inside XAMPP's `htdocs` directory.
5. Open phpMyAdmin at [http://localhost/phpmyadmin/](http://localhost/phpmyadmin/).
6. Import or create the required databases and tables using the SQL files or schema prepared for the project.
7. Check the database connection settings in the PHP configuration files.
8. Open the required PHP pages through `http://localhost/WDF-Practicals/` or the appropriate local project URL, depending on the folder name.
9. For static pages configured to use Live Server, start Live Server separately and open the corresponding HTML page.

## Database Configuration

The project uses MySQL databases for authentication, student records, event management, registrations, and audit logs.

Before running the project, ensure that the required databases and tables exist and that the PHP connection settings match your local MySQL configuration.

**Security note:** Do not publish passwords, private credentials, or other sensitive configuration details in the repository.

## Testing

The following areas should be tested before submission:

- User registration and login/logout
- Session timeout and role-based permissions
- Student management CRUD operations
- Event management and poster uploads
- JSON API and Fetch/AJAX operations
- Dashboard statistics and audit logs
- Database connectivity and navigation links

## Deployment

The application is intended to run locally using XAMPP and MySQL. Verify that the complete application works correctly in the browser before submitting it.

## Author

**Neel Patel**  
**Enrollment No.:** 25DCS093  
**Course:** ITUE203 – Web Development Frameworks
