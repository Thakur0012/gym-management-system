# 🏋️ Gym & Fitness Club Management System

A web-based **Gym and Fitness Club Management System** developed as a Bachelor's degree learning project.

The project was created to learn and practice **PHP, MySQL, HTML, CSS, JavaScript, Bootstrap, and web application development**. It provides an admin dashboard for managing gym members, membership plans, workout routines, payments, health information, and revenue.

> **Note:** This project was developed for educational and learning purposes.

---

## 📌 Project Overview

The Gym & Fitness Club Management System is designed to help gym administrators manage day-to-day gym activities from a centralized web application.

The system provides an administrative dashboard where the administrator can manage:

* Gym members
* Membership plans
* Workout routines
* Member health information
* Payments
* Revenue
* Membership records
* Admin profile and settings

The project also includes authentication and session-based access to the administration area.

---

## ✨ Features

### 🔐 Admin Authentication

* Admin login system
* Password-based authentication
* Session management
* Logout functionality
* Change password functionality

### 👥 Member Management

* Add new gym members
* View member details
* Edit member information
* Delete members
* View all registered members
* Track member joining dates

### 📋 Membership Plan Management

* Create membership plans
* View available plans
* Edit plans
* Delete plans
* View plan details
* Manage plan duration and pricing

### 🏋️ Workout Routine Management

* Add workout routines
* View routines
* Edit routines
* Delete routines
* Assign/manage routines for gym members

### ❤️ Health Status Management

* Add member health information
* View health status
* Manage member health records

### 💳 Payment Management

* Record membership payments
* View payment information
* Manage member payments
* Track payment dates

### 💰 Revenue Management

* View monthly revenue
* View yearly/monthly member statistics
* Track current income
* Display dashboard statistics

### 📊 Admin Dashboard

The dashboard provides an overview of important gym information such as:

* Total members
* Current income
* New members
* Membership information
* Revenue statistics

---

## 🛠️ Technologies Used

| Technology | Purpose                         |
| ---------- | ------------------------------- |
| PHP        | Backend/server-side development |
| MySQL      | Database management             |
| HTML5      | Web page structure              |
| CSS3       | Styling                         |
| JavaScript | Client-side functionality       |
| Bootstrap  | Responsive UI components        |
| jQuery     | Frontend interactions           |
| Apache     | Local web server                |
| XAMPP      | Local development environment   |

---

## 💻 Requirements

To run this project locally, you will need:

* PHP 7.x or later
* MySQL
* Apache Web Server
* XAMPP / WAMP / LAMP
* A modern web browser

---

## 🚀 Installation & Setup

### 1. Install XAMPP

Download and install XAMPP or another PHP development environment.

Start:

* Apache
* MySQL

### 2. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/gym-fitness-management-system.git
```

Move the project into the XAMPP `htdocs` directory:

```text
C:\xampp\htdocs\
```

For example:

```text
C:\xampp\htdocs\gym-fitness-management-system\
```

### 3. Create the Database

Open phpMyAdmin:

```text
http://localhost/phpmyadmin
```

Create a MySQL database named:

```text
mayuri_fitness
```

Import the project's SQL database file if available.

> If the SQL database file is not included in this repository, you should export your project database from phpMyAdmin and add the `.sql` file to the repository before publishing the project.

### 4. Configure Database Connection

Open:

```text
constant/connect.php
```

Update the database configuration according to your local MySQL setup.

Example:

```php
$host = "localhost";
$username = "root";
$password = "";
$db_name = "mayuri_fitness";
```

Do not upload real production database passwords or credentials to GitHub.

### 5. Run the Project

Open your browser and visit:

```text
http://localhost/gym-fitness-management-system/
```

The login page should appear.

---

## 🔑 Admin Login

The admin credentials depend on the data available in your MySQL database.

After importing the database, use the admin credentials stored in the `admin` table.

> For security reasons, do not publish real passwords in this README.

---

## 📸 Screenshots

Screenshots can be added here to demonstrate the project interface.

Example:

```markdown
## 📸 Screenshots

### Login Page

![Login Page](screenshots/login.png)

### Admin Dashboard

![Dashboard](screenshots/dashboard.png)

### Member Management

![Members](screenshots/members.png)

### Membership Plans

![Plans](screenshots/plans.png)
```

You can create a `screenshots` folder in the repository and keep your screenshots there.

---

## 🎯 Learning Objectives

This project was developed as part of my Bachelor's degree learning experience.

Through this project, I practiced:

* PHP web development
* MySQL database integration
* CRUD operations
* User authentication
* Session management
* Form handling
* Database queries
* Admin dashboard development
* Responsive web design
* Bootstrap components
* JavaScript and jQuery
* Basic software project organization

---

## 🔮 Future Improvements

Some improvements that could be added in future versions:

* Improve authentication security
* Use prepared SQL statements
* Add role-based access control
* Improve password hashing and password management
* Add REST APIs
* Add member-side login
* Add online payment integration
* Add email notifications
* Improve dashboard charts and reports
* Improve responsive design
* Add automated database backups
* Improve database structure and validation

---

## ⚠️ Disclaimer

This project was created for **educational and learning purposes** during my Bachelor's degree.

It is not intended to be used as a production-ready gym management system without additional security, testing, validation, and architectural improvements.

---

## 👨‍💻 Author

**Purushottam Thakur**

Bachelor's Degree Project

---

## ⭐ Acknowledgement

This project helped me gain practical experience in PHP, MySQL, web development, database management, and building a complete CRUD-based web application.

If you find this project useful for learning, feel free to explore the source code and improve it.

---

## 📄 License

This project is available for educational and learning purposes.
