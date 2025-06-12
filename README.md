# 🗂️ Online Task Tracker

**Developer:** Tysier Zidan  
**Project Type:** Full Stack Web App (PHP + MySQL + JS + CSS)  
**Hosting:** [ByteHost Free Hosting](https://tysier123.byethost6.com/Online-Task-Tracker/index.php?i=1)

---

## 🔗 How to Access the Website

Because this site is hosted on a free web host (ByteHost), you must **clear your browser cache and history** before visiting — OR use **Incognito/Private mode** to avoid session errors.

👉 Access via this link:  
🔗 **[https://tysier123.byethost6.com/Online-Task-Tracker/index.php?i=1](https://tysier123.byethost6.com/Online-Task-Tracker/index.php?i=1)**

---

## 🧠 Project Overview

**Online Task Tracker** is a full-stack task management application that allows users to:

- Register and log in to their own account.
- Add, edit, and delete tasks on a 7-day rolling calendar.
- Track tasks as Ongoing, Completed ✅, or Deleted 🗑️.
- Use the board interactively across mobile, tablet, and desktop.

---

## 🌟 Features

- 🧑‍💻 User Authentication (Login + Register)
- 📅 Calendar-style Task Board (7-day span)
- ✅ Task status: Ongoing, Completed, Deleted
- 🧠 Task deadline validation (no past dates allowed)
- 📝 In-place editing and deletion via modals
- 📊 Admin View: Users table with email and ID
- 📱 Fully responsive design (CSS Media Queries)
- 📩 Contact form connected to email
- 📂 Database: Users & Tasks (linked by ID)
- 📎 Interactive animations, modals, and JS logic

---

## 🧱 Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Backend**: PHP 8, MySQL
- **Hosting**: [ByteHost](https://byet.host/)
- **Tools**: Visual Studio Code, phpMyAdmin, GitHub

---

## 🔐 Admin Access

The system has an admin account defined by email:  
📧 **tysierps123@gmail.com**

When this user logs in, a new navigation item appears to view **all registered users** via the `users.php` page.

---

## 📂 Project Structure (Key Files)

/Online-Task-Tracker/
│
├── index.php # Home page (Welcome + Register shortcut)
├── login.php # Login form
├── register.php # Registration form
├── board.php # Task board (only after login)
├── profile.php # View + update profile
├── contact.php # Email form to contact developer
├── userhome.php # User's dashboard
├── users.php # Admin: user table view
│
├── includes/
│ ├── header.php
│ └── footer.php
│
├── assets/
│ └── logo.png
│
├── css/
│ └── style.css
├── js/
│ ├── main.js
│ └── board.js
├── php/
│ ├── db.php
│ ├── task_add.php
│ ├── task_edit.php
│ ├── task_delete.php
│ ├── task_fetch.php
│ ├── task_complete.php


---

## 📝 Developer

**Tysier Zidan**  
📧 zidantysier87@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/tysier-zidan-bb1565331)  
💻 Computer Engineering @ Ruppin Academic Center

---

## 📌 Final Notes

- Built as part of the ISEW Semester B Final Project
- Fully meets all checklist requirements from the assignment PDF
- Source code is available on GitHub (upon submission)

---

Thank you for visiting and testing! 🚀
