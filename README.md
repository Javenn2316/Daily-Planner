# Daily Planner Project

This is a simple PHP-based Daily Planner project using XAMPP, HTML, PHP, CSS, and JavaScript.

## 📂 Project Structure

- `index.php` – Main calendar page
- `db_connection.php` – Handles database connection
- `newdb.sql` – SQL file to create database tables

## ✅ Requirements

- [XAMPP](https://www.apachefriends.org/index.html) (PHP + MySQL)
- Web browser

## 🚀 How to Run Locally (XAMPP)

1. **Download or Clone this Repository**
   - Click the green `Code` button > `Download ZIP`
   - Or run: `git clone https://github.com/your-username/Calendar.git`

2. **Move the folder** to:C:\xampp\htdocs\
3. **Start XAMPP** and run:
- Apache
- MySQL

4. **Import the database:**
- Open [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
- Create a database named (example): `calendar`
- Import `calendar.sql` from the `sql` folder

5. **Check the database connection settings in `db_connection.php`**
   ```php
   $servername = "localhost";
   $username = "root";
   $password = "";
   $dbname = "newdb";
   $port = 3307; // Change if needed
   $conn = new mysqli($servername, $username, $password, $dbname, $port);
    If your MySQL port is not 3307 , update the host like this:
   $port = "3306"; // Example if your MySQL runs on port 3306 (default)


6. **Visit the project in your browser**


