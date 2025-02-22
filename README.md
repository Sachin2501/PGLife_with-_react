# 🏠 PGLife - Find the Best PGs Easily!

PGLife is a **PHP & MySQL-based** web application that helps students and professionals find **PG (Paying Guest) accommodations** easily in different cities.

---

## 🚀 Features
✅ **User Authentication** – Login & Signup System  
✅ **PG Listings** – View available PGs by city  
✅ **Advanced Search & Filters** – Find the perfect PG based on preferences  
✅ **PG Details Page** – View details, images, and reviews  
✅ **Booking & Contact Option** – Users can book or contact the owner  
✅ **Admin Panel** – Manage PG listings and users  

---

## 🛠 Technologies Used
- **Frontend:** HTML, CSS, Bootstrap  
- **Backend:** PHP (Core PHP)  
- **Database:** MySQL  
- **Server:** Apache (XAMPP / LAMP)  

---

## 🏗 Installation Guide

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/Sachin2501/PGLife_with-_react.git
```
---
2️⃣ Setup MySQL Database
1. Open phpMyAdmin 👉 http://localhost/phpmyadmin/
2. Create a new database named pglife
3. Go to the Import section
4. Click Choose File and select ``pglife.sql`` (inside the project folder)
5. Click Go to import the database
6. ✅ Done! Your MySQL database is now set up 🎉
---

3️⃣ Configure Database Connection

Edit the file ``includes/database_connect.php`` and update the database connection:
```
$conn = mysqli_connect("localhost", "root", "", "pglife");
```
If you're using XAMPP, use:
```
$conn = mysqli_connect("127.0.0.1", "root", "", "pglife");
```
Save the file and restart Apache/MySQL in XAMPP. ✅
---
4️⃣ Start the Project
1. Start Apache & MySQL in XAMPP
2. Open your browser and go to:
```
http://localhost/PGLife/
```
🎉 Enjoy using PGLife!

---

🌎 Deployment Guide
Deploy on Render (Free Cloud Hosting)
1. Create a free account on ``Render``
2. Click on "New Web Service"
3. Connect your GitHub repository
4. Set Environment = PHP 8.x
5. Configure MySQL Database & Update ``database_connect.php``
6. Click Deploy ✅

For other deployment methods, check the Deployment Guide.
--- 
📸 Screenshots
🏠 Homepage
🔍 PG Listings
---
🤝 Contributing
Want to improve PGLife? Follow these steps:

1. Fork this repository
2. Create a new branch`` (feature-branch)``
3. Make changes and commit
4. Submit a Pull Request (PR)
   
---
📧 Contact
For any queries or support ,feel free to contact: 📧 Email: sachinkumar.gheura@gmail.com

🔗 Live Demo: pglife.example.com 🚀
---

### **📌 Step 3: Save & Push to GitHub**  
After adding this content, save the `README.md` file and push it to GitHub:

```sh
1. git add README.md
2. git commit -m "Added README documentation"
3. git push origin main  # or your branch name
```







