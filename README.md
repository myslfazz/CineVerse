# 🎬 CineVerse – Online Movie Ticket Booking System
> 🍿 A dynamic web-based Movie Ticket Booking System built using PHP and MySQL that allows users to browse movies, select showtimes, and book seats online with secure payment handling.

<p align="center">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg"/>
</p>

---

## 📚 Table of Contents
- [About](#-about)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Setup](#-how-to-run)
- [Project Structure](#-project-structure)
- [Screenshots](#-screenshots)
- [Future Enhancements](#-future-enhancements)
- [Author](#-author)

---

## 🧾 About
**CineVerse** is an online movie ticket booking web application that provides users with a simple and convenient interface to browse movies, check available showtimes, select seats, and make bookings.  
The system includes an **Admin Dashboard** for managing movie listings, show schedules, user details, and ticket transactions.  

This project demonstrates integration of **frontend (HTML, CSS, JS)** with **backend (PHP & MySQL)**, database design, and real-world CRUD operations.

---

## 🗂️ Project Structure
```CineVerse-Movie-Booking-System/
├── admin/
│   ├── dashboard.php
│   ├── manage_movies.php
│   ├── manage_users.php
│   ├── manage_bookings.php
│   └── logout.php
├── user/
│   ├── register.php
│   ├── login.php
│   ├── book_ticket.php
│   ├── my_bookings.php
│   └── profile.php
├── includes/
│   ├── config.php
│   └── functions.php
├── database/
│   └── cineverse_db.sql
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
├── docs/
│   ├── home.png
│   ├── booking.png
│   └── dashboard.png
└── index.php
```
---

## 🚀 Features
- 🎥 Browse now showing and upcoming movies  
- 🕒 Select theater, showtime, and seats  
- 💳 Book tickets and generate booking confirmation  
- 👩‍💼 Admin panel for managing movies, users, and bookings  
- 🔐 User authentication with session management  
- 📱 Responsive design with Bootstrap  

---

## ⚙️ Tech Stack
- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap  
- **Backend:** PHP  
- **Database:** MySQL  
- **Server:** Apache (XAMPP / LAMP)  

---

## 🧩 How to Run
```bash
# 1️⃣ Clone this repository
git clone https://github.com/your-username/CineVerse-Movie-Booking-System.git

# 2️⃣ Move project to XAMPP htdocs folder
cp -r CineVerse-Movie-Booking-System /xampp/htdocs/

# 3️⃣ Start Apache and MySQL from XAMPP Control Panel

# 4️⃣ Import the database
Open phpMyAdmin → Create new DB `cineverse_db` → Import `database/cineverse_db.sql`

# 5️⃣ Run in browser
http://localhost/CineVerse-Movie-Booking-System/
```
---

🛠️ Future Enhancements
- 💳 Integration with Razorpay or Stripe for real-time payments
- 🎟️ QR-based ticket validation
- 📱 Mobile app integration using Flutter / React Native
- ☁️ Cloud deployment on AWS / Render / Netlify

---
<p align="center"> Developed by <b>Azmath Pasha</b><br/> 🔗 <a href="https://github.com/myslfazz">GitHub</a> • <a href="https://linkedin.com/in/myslfazz">LinkedIn</a> </p> ```
