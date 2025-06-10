# DBS-PROJECT
# 📚 Library Management System (PHP + MySQL)

This is a **Library Management System** developed using **PHP**, **MySQL**, **Bootstrap**, and **jQuery**. It allows admins to manage books, categories, students, borrowing records, and returns. Students can view their own transaction history.

---

## 🔧 Features

### 👨‍💼 Admin Panel:
- Add / Edit / Delete Books
- Add / Edit / Delete Categories
- Manage Students
- Track Borrow and Return Records
- View system activity via transactions

### 👨‍🎓 Student Panel:
- Log in using Student ID
- View borrowed books
- View returned books
- Toggle between borrow and return history

---

## 🛠️ Technologies Used

- **Frontend:** HTML5, CSS3, Bootstrap, AdminLTE
- **Backend:** PHP
- **Database:** MySQL
- **AJAX/JS:** jQuery, DataTables, JSON (for dynamic updates)

---

## 🗂️ Folder Structure

/includes # Reusable PHP files (e.g., DB connection, session)
admin/ # Admin dashboard pages
student/ # Student transaction view
css/ # Stylesheets
js/ # JavaScript files
book.php # Main book management page
index.php # Student login page
transaction.php # Student's transaction history



---

## 📦 Database

The system uses MySQL. Required tables include:
- `books`
- `category`
- `students`
- `borrow`
- `returns`
- `users` (for admin login)

You can find the database SQL file in the `/db` folder (if provided), or export it from phpMyAdmin after running the system.

---


