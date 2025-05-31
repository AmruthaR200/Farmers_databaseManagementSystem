
#  Farm Management System - DBMS Mini Project

A web-based application to manage and monitor farming activities such as crop cultivation, farmer records, sales, and equipment management. This project was developed as part of a Database Management Systems (DBMS) mini project using **PHP**, **MySQL**, **HTML**, and **CSS**.

---

## 📚 Project Description

The Farm Management System aims to digitalize and streamline various aspects of farming operations. It provides an interactive interface for farmers and an admin panel to oversee operations. The system supports functions such as registering farmers, recording crop details, handling sales data, and managing farm equipment.

This project demonstrates database connectivity, CRUD operations, form handling, and basic UI/UX practices.

---

## 🧰 Technologies Used

| Technology       | Description                          |
|------------------|--------------------------------------|
| PHP              | Backend scripting language           |
| MySQL            | Relational database                  |
| HTML & CSS       | Frontend markup and styling          |
| Bootstrap        | Responsive UI components             |
| XAMPP / LAMP     | Server environment for testing       |
| phpMyAdmin       | For database import and management   |

---

## 📁 Folder Structure

```plaintext
Farm-management-sysem-dbmsminiproject/
│
├── admin/                  # Admin panel pages
├── farmer/                 # Farmer dashboard pages
├── images/                 # Icons, logos, UI images
├── css/                    # Stylesheets
├── js/                     # JavaScript files (if any)
├── database/
│   └── farmdb.sql          # SQL dump file
├── index.php               # Landing page
├── login.php               # Login handler
├── register.php            # Farmer registration
├── README.md               # Project documentation

## 🛠 Setup Instructions

Follow the steps below to run the project locally using XAMPP:

### Step 1: Clone the Repository

```bash
git clone https://github.com/AmruthaR200/Farmers_databaseManagementSystem.git

### Step 2: Move Project to XAMPP Directory

Move the cloned project folder to your XAMPP `htdocs` directory:

```bash
C:\xampp\htdocs\Farmers_databaseManagementSystem\

### Step 3: Start XAMPP Server

- Open the **XAMPP Control Panel**.
- Start the following services:
  - Apache
  - MySQL

### Step 4: Import the Database

1. Open your browser and go to:  
   `http://localhost/phpmyadmin`

2. Create a new database named:  
   `farmersdb`

3. Click the **Import** tab.

4. Choose the file:  
   `database/farmersdb.sql`

5. Click **Go** to import the database.

### Step 5: Run the Application

Open your browser and navigate to:  
`http://localhost/Farmers_databaseManagementSystem/`

---

## 🔐 Default Login Credentials

### Admin:
- Username: `admin`  
- Password: `admin123`

### Farmer:
- Username: `farmer1`  
- Password: `farmer123`

---

## 📜 License

This project is for educational purposes only.  
Feel free to use and modify it as needed.

---
