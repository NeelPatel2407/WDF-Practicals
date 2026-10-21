# CampusCore – Student Portal

**Subject:** Web Development Frameworks (ITUE203)  
**Institution:** CHARUSAT – Devang Patel Institute of Advance Technology and Research  
**Academic Year:** 2026–27  
**Semester:** 3  
**Student:** Neel Patel  
**Enrollment No.:** 25DCS093

## GitHub Repository

**Repository:** [WDF-Practicals](https://github.com/NeelPatel2407/WDF-Practicals)

Clone the repository:

git clone https://github.com/NeelPatel2407/WDF-Practicals.git
cd WDF-Practicals

## 1. Project Overview

CampusCore is a student portal developed as part of the Web Development Frameworks practical course. It integrates frontend pages, JavaScript interactivity, PHP server-side processing, and MySQL database operations into a single web application.

The project covers user authentication, student management, event management, administrative dashboards, and audit logging.

## 2. Objectives

- Integrate the modules developed across Practicals 1–14.
- Ensure navigation and application functionality work end-to-end.
- Implement and verify authentication, sessions, roles, and input validation.
- Verify database connectivity and CRUD operations.
- Test AJAX/Fetch functionality.
- Document installation, configuration, and testing.
- Submit the source code and supporting files through GitHub.
- Deploy and verify the application locally using XAMPP and Apache.

## 3. Features

- **User Registration:** Account creation, duplicate email checking, and password hashing.
- **Authentication:** Login, logout, session management, and role-based access.
- **Student Management:** Student CRUD operations, search, and filtering.
- **Event Management:** Event CRUD operations and poster uploads with file validation.
- **JSON API:** PHP API with AJAX/Fetch-based operations without full-page reloads.
- **Admin Dashboard:** Administrative navigation and dynamic statistics.
- **Audit Logs:** Recording and displaying administrative activities.
- **Frontend Interactivity:** JavaScript validation, DOM manipulation, and Fetch API integration.

## 4. Technologies Used

- HTML5
- CSS3
- JavaScript
- PHP
- MySQL
- XAMPP and Apache
- Git and GitHub
- Visual Studio Code

## 5. Project Structure


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
├── README.md

The structure above illustrates the intended submission layout. Keep only files and folders that actually exist in the repository, and include the relevant SQL export, test report, and screenshots.

## 6. Requirements

- XAMPP with Apache and MySQL
- A modern web browser
- Visual Studio Code or another code editor
- Git installed for repository management

## 7. Installation and Local Deployment

1. Install and open XAMPP.
2. Start Apache and MySQL.
3. Clone the repository or download its source code from GitHub.
4. Place the project folder inside the XAMPP `htdocs` directory.
5. Open phpMyAdmin at [http://localhost/phpmyadmin/](http://localhost/phpmyadmin/).
6. Create or import the databases and tables required by the project using the supplied SQL export.
7. Check the PHP database connection settings and update them for your local MySQL configuration.
8. Open the project through the appropriate `http://localhost/...` URL.
9. For static HTML pages configured to use Live Server, start Live Server separately.
10. Test the application in the browser and verify that its pages, database operations, and authentication work correctly.

**Note:** The exact URL depends on the folder name inside `htdocs`. Update the example URL if your local folder is named `WDF` rather than `WDF-Practicals`.

## 8. Database Configuration

CampusCore uses MySQL for authentication, student records, events, registrations, and audit logs.

Before running the application:

- Create all required databases and tables.
- Import the SQL dump supplied with the submission.
- Verify database names, usernames, passwords, and connection settings.
- Confirm that the application can read and write records correctly.

Do not commit real passwords or private credentials to GitHub.

## 9. Testing and Verification

The following checks must be performed before submission:

| Test Area | Verification |
|---|---|
| Navigation | All relevant pages and links open correctly |
| Registration | Valid inputs are accepted and duplicate emails are handled |
| Authentication | Login and logout work correctly |
| Sessions and roles | Protected pages enforce the appropriate role |
| Student management | Create, read, update, delete, search, and filter operations work |
| Event management | Event operations and permitted poster uploads work |
| JSON API | Fetch/AJAX requests return valid responses |
| Database | Required tables and database operations work |
| Admin dashboard | Statistics and administrative links work |
| Audit logs | Relevant activity records are displayed correctly |
| Security | Input validation, password hashing, and access checks are verified |
| Accessibility | Labels, headings, image alternatives, and navigation are checked |
| Deployment | Application runs locally using XAMPP and Apache |

Record the actual result of each test in the accompanying test report. Do not mark a test as passed until it has been performed.

## 10. Security and Accessibility Checklist

- Passwords are stored using password hashing rather than plaintext.
- Database queries use appropriate prepared statements.
- Server-side validation is applied to relevant inputs.
- Session and role checks protect restricted pages.
- File uploads are validated.
- Output is escaped where appropriate.
- Forms have associated labels and useful validation messages.
- Images have appropriate alternative text.
- Navigation and interactive controls can be used clearly.

## 11. GitHub Submission

The final repository should contain:

- Complete project source code
- `README.md` with setup instructions
- SQL database export
- Test report with test cases and actual results
- Screenshots of important application pages
- Any other files required by the practical instructions

Review the repository before submission and remove temporary files, debugging output, passwords, and sensitive credentials.

**GitHub Repository:**  
https://github.com/NeelPatel2407/WDF-Practicals

## 12. Screenshots and Project Demo

Capture screenshots of the actual running application, including relevant pages such as:

- Login and registration
- Student dashboard
- Admin dashboard
- Student management
- Event management
- Audit logs

Demonstrate the integrated application, including authentication, database operations, role-based access, and other implemented features.

## 13. Deployment Extension

The practical list suggests local deployment using an Apache virtual host as an intermediate extension. An advanced extension is to deploy the frontend/static component online and document backend deployment limitations, or use PHP-compatible hosting.

These extensions should be included only if they are actually completed.

## 14. Learning Outcome

This practical integrates the semester's web development work into a complete, documented, testable, and locally deployable full-stack application. It reinforces integration, testing, debugging, security, accessibility, documentation, and version control.

## 15. Author

**Name:** Neel Patel  
**Enrollment No.:** 25DCS093  
**Institution:** DEPSTAR, CHARUSAT  
**Course:** ITUE203 – Web Development Frameworks  
**Academic Year:** 2026–27