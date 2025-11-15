# Library Management System (PHP + MySQL)

This project is a lightweight Library Management System built using **PHP**, **MySQL**, **HTML/CSS**, and **AJAX**. It supports user roles, book issuing, admin operations, and dynamic data management.

---

## 🚀 Features

### **👤 User Features**

* Login & logout system
* Request a book
* View issued books
* Browse available books
* Manage personal profile

### **🛠️ Admin Features**

* Add, update, delete books
* Add persons/users
* Approve book requests
* View and manage all users
* Dashboard with quick stats
* Manage issued books

### **📁 File Uploading**

* Book images stored in `/uploads` directory

---

## 📂 Project Structure

```
project-root/
│
├── images/                     # Frontend images/assets
├── uploads/                    # Uploaded book images
│
├── admin_service_dashboard.php # Admin dashboard UI
├── approvebookrequest.php      # Approve book request UI
├── addbooksserver_page.php     # Backend for adding books
├── addpersonserver_page.php    # Backend for adding users
├── deletebook_dashboard.php    # Delete book handler
├── deleteuser.php              # Delete user handler
├── issuebook_server.php        # Backend for issuing book
├── login_server_page.php       # User login
├── loginadmin_server_page.php  # Admin login
├── otheruser_dashboard.php     # User dashboard
├── index.php                   # Home page / login UI
├── requestbook.php             # User book request handler
├── viewbook.php                # Book viewer (currently empty)
│
├── db.php                      # DB connection
├── data_class.php              # PHP class handling DB queries
│
├── library_managment.sql       # Database dump
└── style.css                   # Custom styles
```

---

## 🗄️ Database Setup

1. Create a database in MySQL
2. Import `library_managment.sql`
3. Update `db.php` with your credentials:

```php
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "library";
```

---

## ▶️ Running the Project

1. Install XAMPP / WAMP / LAMP
2. Place project folder inside `htdocs`
3. Start **Apache** and **MySQL**
4. Access the site:

```
http://localhost/library_project/
```

---

## 💡 Technologies Used

* PHP (Procedural + OOP mix)
* MySQL
* HTML5, CSS3
* AJAX (for async calls)
* Tailwind CSS (partially, if added)

---

## 🔐 Login Credentials (Default)

```
Admin:
User: admin
Pass: admin
```

> Update inside DB after import.

---

## 📌 Notes

* `viewbook.php` appears to be incomplete.
* File upload path must exist (`/uploads`).
* Some dashboard pages rely on data_class.php for DB operations.

---

## 📣 Future Improvements

* Full CRUD for users & books
* Notifications system
* Search & filter for books
* Responsive UI redesign
* Role-based access control (RBAC)

---

## 🧑‍💻 Author

Developed by Noor (BSE in CSE)

---

## ⭐ Contribution

Feel free to fork & improve! Pull requests are welcome.
