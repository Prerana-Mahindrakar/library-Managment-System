# 📚 Library Management System

A simple and efficient **Library Management System** built using **PHP, HTML, CSS, and JavaScript**. It allows users to **add books**, **register persons**, **request books**, and enables the admin to **approve or reject requests**. This system is designed to manage library operations quickly and with minimal complexity.

---

## 🔧 Features

- 📖 Add new books to the library
- 👤 Register library members
- 📬 Members can request books
- ✅ Admin can approve or reject requests
- ⏱️ Fast response and minimal load time
- 💻 Simple and responsive UI using HTML, CSS, and JavaScript

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL

---

## 🚀 Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/Prerana-Mahindrakar/Library-Managment-System.git


## ▶️ How to Run the Project

1. **Install a local server** like [XAMPP](https://www.apachefriends.org/) or [WAMP](http://www.wampserver.com/)

2. **Place the project in your server directory**
   - For XAMPP: Copy the entire `librarymanage` folder into `C:\xampp\htdocs\`

3. **Start Apache and MySQL** from the XAMPP Control Panel

4. **Import the Database**
   - Open `http://localhost/phpmyadmin`
   - Create a new database (e.g., `ma_db`)
   - Import the `ma.sql` file provided in the project

5. **Configure Database**
   - Open `db.php` and update with your database info:

     ```php
     $conn = new mysqli("localhost", "root", "", "ma_db");
     ```

6. **Run the Project**
   - Open your browser and go to:  
     `http://localhost/librarymanage/`

   - You should now see the homepage (like login)

   

## 📷 Screenshots

### 🔹 Home Page
![Home Page](Screenshots/login page.png)

### 🔹 User login Page
![User login Page](Screenshots/user login.png)

### 🔹 Admin login Page
![Admin login Page](Screenshots/admin login.png)
