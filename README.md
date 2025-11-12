# 🌐 Lang Lá Web Portal (PHP + MySQL)

A complete web portal for the **Lang Lá MMORPG** project.  
This website allows players to **register, log in, recharge (VietQR/PayOS)**, and view **leaderboards** such as top level and top recharge.  
It also includes an admin panel to manage recharge transactions.

---

## 💡 Features

### 👤 User Features
- 🔐 **Login & Register** — linked directly to the game’s MySQL database.  
- 💰 **Recharge System** — integrate **PayOS VietQR** for fast & secure nạp tiền.  
- 📜 **Recharge History** — track past transactions.  
- 🏆 **Leaderboards**:
  - **Top Level** — highest level players.
  - **Top Recharge** — players with highest total top-up.

### 🛠️ Admin Features
- View and approve recharge requests.  
- Edit or delete top-up records.  
- Manage leaderboard updates.

---

## 🧰 Technologies Used
| Component | Technology |
|------------|-------------|
| Backend | PHP 8.0+ |
| Frontend | HTML, CSS, JavaScript, Bootstrap |
| Database | MySQL / MariaDB |
| Server | XAMPP (Apache + PHP + MySQL) |
| Payment API | PayOS VietQR Webhook |

---

## ⚙️ Setup Guide

### 🧩 Requirements
- XAMPP (with Apache & MySQL)  
- PHP 8.0 or higher  
- Database file: `langla.sql`

---

### 🪜 Installation Steps

1. Copy the project folder to XAMPP:
2. Open **phpMyAdmin** → create database `langla`  
→ Import file `langla.sql`
3. Edit database connection inside:
  Example:
```php
$db_host = "localhost";
$db_user = "root";
$db_pass = "";
$db_name = "langla";
4. Configure PayOS webhook inside:
nap-tien/webhook_vietqr.php
5. Start XAMPP.
🎥 Demo Video

▶️ Watch Web Demo (Google Drive / YouTube)

The demo shows:

User login & recharge flow

VietQR payment callback working

Viewing recharge history

Displaying Top Level & Top Recharge

📦 Download Project

Because the project includes many PHP modules and assets,
please download the full version here:

➡ Download LangLa-Web.zip (Google Drive)

🖼️ Screenshots

	
	
🧑‍💻 Author

Nguyen Thanh Duy
📧 duynguyen.codes@gmail.com

🌐 github.com/dev-duynguyen

