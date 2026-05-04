# Student Result Management System (SRMS)
Project Name: student Result Management System

How to run this Project

1. Download and Unzip file on your local system copy srms folder.

2. Put srms folder inside root directory

Database Configuration

Open phpmyadmin
Create Database srms
Import database srms.sql (available inside zip package)

For User

Open Your browser put inside browser http://localhost/srms

*********************Details of student**********************

Student name-- Gautam Gupta
Roll id--01
Student Class: Tenth(A)

Student name -- Rachit
Roll id -- 01
Student Class -- ninth(A)

********************For Admin Panel************************

Open Your browser put inside browser http://localhost/srms
Username : admin
Password : Test@123


For More Details --- https://phpgurukul.com/student-result-management-system/

A web-based application for managing student results, built with PHP and MySQL.

## Features

- **Admin Panel**: Manage classes, subjects, students, and results
- **Student Management**: Add, edit, and view student information
- **Result Declaration**: Enter and manage student marks for various subjects
- **Subject Combination**: Assign subjects to classes
- **Notice Management**: Post and display notices
- **User Authentication**: Secure login for admins
- **Responsive Design**: Built with Bootstrap for mobile-friendly interface

## Technologies Used

- **Backend**: PHP 7+
- **Database**: MySQL
- **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 4/5
- **Libraries**: jQuery, Font Awesome, CKEditor, DataTables
- **Server**: Apache (XAMPP recommended)

## Installation

### Prerequisites
- XAMPP or similar web server with PHP and MySQL
- Git (for cloning the repository)

### Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Gautamkr18/SRMS.git
   cd SRMS
   ```

2. **Set up XAMPP**:
   - Install XAMPP from [apachefriends.org](https://www.apachefriends.org/)
   - Start Apache and MySQL modules

3. **Database Setup**:
   - Open phpMyAdmin (http://localhost/phpmyadmin)
   - Create a new database named `srms`
   - Import the `srms.sql` file from the project root

4. **Configure Database Connection**:
   - Edit `includes/config.php` with your database credentials (default should work with XAMPP)

5. **Place the project**:
   - Copy the project files to `C:\xampp\htdocs\srms\` (or your web server's document root)

6. **Access the application**:
   - Open your browser and go to `http://localhost/srms/`
   - Default admin login: Check the database or contact developer

## Usage

### Admin Functions
- **Dashboard**: Overview of the system
- **Manage Classes**: Add/edit class information
- **Manage Subjects**: Create and modify subjects
- **Manage Students**: Student registration and details
- **Declare Results**: Enter marks for students
- **View Results**: Check student performance
- **Notices**: Post important announcements

### Student Functions
- View personal results
- Access notices

## Project Structure

```
srms/
├── includes/
│   ├── config.php          # Database configuration
│   ├── leftbar.php         # Admin sidebar
│   └── topbar.php          # Admin header
├── css/                    # Stylesheets
├── js/                     # JavaScript files
├── images/                 # Images and assets
├── *.php                   # PHP pages
├── srms.sql                # Database dump
└── README.md               # This file
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

All CopyRight @GG.Tech

## Contact

**Gautam Gupta**  
Phone: 7549117172  

For questions or support, please contact the developer.

---

**Note**: This is a basic implementation. For production use, ensure proper security measures are in place.</content>
<parameter name="filePath">c:\xampp\htdocs\srms\README.md