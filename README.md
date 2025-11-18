# TutorConnect

A PHP-based platform designed to connect students with tutors, featuring user authentication, chat system, request management, reviews, and profile management.

---

## 🚀 Features

### 👨‍🎓 Student Features

* Register & login
* Browse tutors
* Send tutoring requests
* Chat with tutors
* Rate and review tutors
* Edit profile

### 👨‍🏫 Tutor Features

* Register & login
* Manage student requests
* Chat with students
* Update profile
* View received reviews
* Mark sessions as completed

### 🔐 Authentication System

* Secure login/logout
* Session-based access control

### 🗃️ Database

* Includes `database.sql` with all required tables

---

## 📂 Folder Structure

```
tutorconnect/
│── index.php
│── login.php
│── register.php
│── logout.php
│── database.sql
│
├── assets/
│   ├── css/style.css
│   ├── js/scripts.js
│   └── images/
│        ├── student.jpg
│        └── tutor.jpg
│
├── includes/
│   ├── auth.php
│   ├── data.php
│   └── functions.php
│
├── student/
│   ├── dashboard.php
│   ├── send_request.php
│   ├── edit_profile.php
│   ├── chat.php
│   └── rate_tutor.php
│
└── tutor/
    ├── dashboard.php
    ├── respond_request.php
    ├── mark_completed.php
    ├── edit_profile.php
    ├── chat.php
    └── view_reviews.php
```

---

## 🛠️ Tech Stack

* **PHP** (Core backend)
* **MySQL** (Database)
* **HTML / CSS / JavaScript** (Frontend)

---

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/Adithyavarma1804/tutorconnect.git
cd tutorconnect
```

2. Import the database:

   * Open **phpMyAdmin**
   * Create a new database
   * Import `database.sql`

3. Configure database connection inside `includes/data.php`:

```php
$host = "localhost";
$user = "root";
$pass = "";
$db   = "tutorconnect";
```

4. Run project on local server (XAMPP, WAMP, etc.)
   Place the project folder inside:

```
htdocs/ (XAMPP)
www/ (WAMP)
```

---

## ▶️ Usage

### Student

1. Register or log in
2. Browse tutors
3. Send tutoring request
4. Chat & learn!

### Tutor

1. Log in
2. View student requests
3. Respond and chat
4. Mark sessions as completed

---

Example embed:

```md
![Student](assets/images/student.jpg)
![Tutor](assets/images/tutor.jpg)
```

---

## 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first to discuss your idea.

---

## 👤 Author

**Adithya Varma**
GitHub: [Adithyavarma1804](https://github.com/Adithyavarma1804)

---
