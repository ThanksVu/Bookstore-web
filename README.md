

---

## 📚 Bookstore Web Application

A simple web-based Bookstore application built using **PHP** and **MySQL**. This project allows users to browse books, view book details, and manage a shopping cart. Admins can add, update, or delete books from the store.

---

## 🚀 Features

### 🧑‍💻 For Users:

- View all available books  
- Search books by title or author  
- View detailed book information  
- Add books to cart  
- Checkout and place orders  

### 🔐 For Admins:

- Admin login/logout  
- Add new books  
- Edit or delete existing books  
- Manage orders (optional)  

---

## 🛠️ Technologies Used

- **Frontend**: HTML, CSS, JavaScript (Bootstrap optional)  
- **Backend**: PHP  
- **Database**: MySQL  
- **Other tools**: phpMyAdmin (for managing the database)  

---

# ⚙️ Setup Instructions

---
### 1. Clone the repository


git clone https://github.com/ThanksVu/Bookstore-web
cd bookstore

### 2. Import the database

* Open **phpMyAdmin**
* Create a database (e.g., `bookstore`)
* Import the `shop_db.sql` file from the project

### 3. Configure database connection

Open `config.php` or similar config file and update the following with your MySQL credentials:

```php
$host = 'localhost';
$user = 'root';
$pass = 'root';
$dbname = 'bookstore';
```

### 4. Run the application

* Place the project folder inside the `htdocs/` directory (if using XAMPP) or in `MAMP/htdocs` if using **MAMP**
* Start Apache and MySQL
* Visit: [http://localhost/bookstore/](http://localhost/bookstore/)

---

## 📁 Project Structure

```
Bookstore-web/
├── about.php
├── add_to_cart.php
├── admin_contacts.php
├── admin_header.php
├── admin_orders.php
├── admin_page.php
├── admin_products.php
├── admin_users.php
├── cart.php
├── checkout.php
├── config.php
├── contact.php
├── css/
├── footer.php
├── header.php
├── home.php
├── images/
├── login.php
├── logout.php
├── register.php
├── search_page.php
├── shop.php
├── shop_db.sql
└── uploaded_img/
```

---

## 🙋‍♂️ Team Members

* 👨‍💻 [Tạ Thanh Vũ](#ITITIU21352)
* 👨‍💻 [Lê Quang Nguyên](#ITITIU21265)

---

## 📄 License

This project is for educational purposes only.

---

## 📬 Contact

If you have any questions or suggestions, feel free to open an issue or contact the authors.

```

---

✅ You can copy-paste the above into your `README.md` file. It will render beautifully on GitHub with headers, code blocks, emoji icons, and clean layout.

Let me know if you want:
- A Vietnamese version 🇻🇳  
- Dark-mode optimized badges or shields  
- A demo video/GIF embed  

I'm happy to help!
```
