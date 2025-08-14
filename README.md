# ONLINE-VEHICLE-RENTAL-SYSTEM
🎮 Car Rental Management System

A modern, dark-themed Car Rental Management System with a sleek gaming-inspired UI for client & admin login, built for efficiency and style.

✨ Features

🚗 Client Portal – Book, manage, and view car rentals easily.

🛠 Admin Dashboard – Manage cars, bookings, and customer data.

🎨 Dark Mode + Gaming Buttons – Modern UI with smooth hover animations.

🔐 Secure Login – Separate logins for Client and Admin.

📱 Responsive Design – Works perfectly on desktop, tablet, and mobile.

📸 Screenshots
Home Page	Client Login	Admin Dashboard

	
	
🛠 Tech Stack

Frontend: HTML5, CSS3, JavaScript

Backend: PHP

Database: MySQL

Hosting: XAMPP / Localhost

🚀 Installation

Clone the repository

git clone https://github.com/yourusername/car-rental-system.git


Import database

Open phpMyAdmin

Create a new database (e.g., carrentaldb)

Import database.sql from the project folder

Configure database connection

Open config.php and update database credentials:

$host = "localhost";
$user = "root";
$pass = "";
$dbname = "carrentaldb";


Run project

Move the folder to htdocs

Open in browser: http://localhost/car-rental-system

🎯 Usage

Client Login: Allows customers to browse available cars and make bookings.

Admin Login: Manage vehicle listings, confirm bookings, and view analytics.

🎮 Gaming-Style Buttons Preview
<div class="login-buttons">
    <a href="account.php" class="btn-gaming">Client Login</a>
    <a href="login.php" class="btn-gaming">Admin Login</a>
</div>

.btn-gaming {
    padding: 10px 20px;
    background: linear-gradient(90deg, #ff4b2b, #ff416c);
    color: white;
    text-decoration: none;
    font-weight: bold;
    border-radius: 8px;
    margin: 5px;
    transition: all 0.3s ease-in-out;
    box-shadow: 0 4px 15px rgba(255,65,108,0.4);
}
.btn-gaming:hover {
    transform: scale(1.05);
    box-shadow: 0 6px 20px rgba(255,65,108,0.6);
}

📜 License

This project is licensed under the MIT License – see the LICENSE file for details.

❤️ Support

If you like this project, star ⭐ the repository and share it with your friends!
For issues or feature requests, open a GitHub issue.
