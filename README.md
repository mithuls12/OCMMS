# Online Course Material Management System

An **Online Course Material Management System** built using **PHP**, **MySQL**, **HTML**, **CSS**, and **jQuery**. This system allows instructors to manage and share course materials efficiently, while providing students with a user-friendly platform to access resources.

## Features
- **Material Management**: Upload, organize, and manage course notes, videos, assignments, and presentations.
- **User Roles**:
  - **Administrator**: Manage users and oversee the system.
  - **Instructor**: Upload and organize course materials.
  - **Student**: Access materials and download resources.
- **Interactive Dashboard**: Role-specific dashboards with detailed overviews.
- **Search Functionality**: Quickly find materials using keywords and filters.
- **Responsive Design**: Accessible on desktops, tablets, and mobile devices.
- **Secure Login System**: User authentication with password encryption.

## Technologies Used
- **Backend**: PHP (Core PHP or with frameworks like CodeIgniter/Laravel)
- **Database**: MySQL
- **Frontend**: HTML5, CSS3, and jQuery for dynamic user interfaces
- **Styling**: CSS and optional libraries like Bootstrap
- **Scripts**: jQuery for interactivity and AJAX for seamless operations

## Screenshots
Add screenshots or GIFs of the interface here to showcase your system (if available).

## Installation
### Requirements
- A web server (e.g., Apache or Nginx)
- PHP 7.x or higher
- MySQL 5.x or higher
- A browser to test the application

### Steps to Install
1. Clone the repository:
   ```bash
   git clone https://github.com/Balasunil15/OCMMS.git
   ```
2. Upload the project files to your server's root directory (e.g., `htdocs` for XAMPP).
3. Create a database in MySQL:
   ```sql
   CREATE DATABASE course_management;
   ```
4. Import the database schema:
   - Locate the SQL file in the `database` folder.
   - Use PHPMyAdmin or MySQL CLI to import it:
     ```bash
     mysql -u your_username -p course_management < database/course_management.sql
     ```
5. Configure database connection in `config.php`:
   ```php
   <?php
   $host = 'localhost';
   $user = 'your_username';
   $password = 'your_password';
   $database = 'course_management';
   $conn = new mysqli($host, $user, $password, $database);
   if ($conn->connect_error) {
       die("Connection failed: " . $conn->connect_error);
   }
   ?>
   ```
6. Start your server and navigate to the project in your browser:
   
   http://localhost/online-course-material-management

## Usage
- **Admin Login**: Use default admin credentials after importing the SQL file.
- **Instructor/Student Registration**: Register via the system or create users manually through the admin panel.

## Contributing
Feel free to contribute by:
- Reporting issues
- Submitting feature requests
- Creating pull requests for improvements

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For queries or support, email (smithul904@gmail.com)

This README provides installation steps, an overview of features, and technical details, ensuring clarity for developers and users.
