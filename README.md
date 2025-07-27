# 🌸 Flower Store Website

A dynamic Flower Store web application that allows users to browse and purchase flowers, while providing an admin panel for managing products, users, and orders.

## 🔧 Technologies Used

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: PHP  
- **Database**: MySQL (via phpMyAdmin)

## ✨ Features

### 👤 User Features:
- User registration and login
- View flower products
- Add to cart
- Place orders
- View order history
- Logout

### 🛠️ Admin Features:
- Admin login
- Add/Delete flower products
- View and manage registered users
- Track and manage orders


## 🗄️ Database Setup

- The SQL file `shop_db.sql` is already included in the project.
- Import it into your MySQL server using phpMyAdmin or the MySQL CLI.

### How to Import:
1. Go to [phpMyAdmin](http://localhost/phpmyadmin)
2. Create a database named `shop_db`
3. Click **Import**
4. Select `shop_db.sql` from the project folder
5. Click **Go**

## ⚙️ Configuration

Open `db/connection.php` and update credentials if needed:

```php
$host = "localhost";
$username = "root";
$password = "";
$dbname = "shop_db";
$conn = mysqli_connect($host, $username, $password, $dbname);


Admin Login
URL: /admin/login.php

Default credentials (check in your database if set manually):


Email: admin01@gmail.com  
Password: 111

🚀 Running the Project
Place the project folder in your web server directory (htdocs if using XAMPP)

Start Apache and MySQL

Open browser and go to:
http://localhost/store/

🧠 Future Improvements
Search/filter functionality

Order tracking by users

Email notifications

Mobile responsiveness

Payment integration
