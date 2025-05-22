<<<<<<< HEAD
<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>
# 📚 Bookstore – Laravel Project

A fully functional **Bookstore Management System** built with Laravel. This application allows users to manage a vast collection of books (1000+ entries) along with their respective authors, ISBNs, prices, and stock levels.

---

## 🚀 Features

- 📖 **Book Management**
  - Add, edit, delete, and view books.
  - Each book includes title, author, ISBN, price, and stock quantity.
  - Supports pagination and search functionality.

- 👨‍💼 **Author Management**
  - Add, update, or remove authors.
  - Associate books with authors.

- 🔎 **Advanced Search**
  - Search books by title, author, ISBN.
  - Filter books by price range and availability in stock.
---

## 🛠️ Tech Stack

- **Backend**: Laravel 10+
- **Database**: MySQL / MariaDB
- **Frontend**: Blade templating / Bootstrap / Tailwind CSS (if used)
- **Others**: Laravel Eloquent ORM, Artisan Console, Laravel Validation

---📂 Project Structure
├── app/
│   ├── Models/Book.php
│   ├── Models/Author.php
│   ├── Http/Controllers/
│   └── ...

├── resources/views/
│   ├── books/
│   ├── authors/
│   └── layouts/
├── routes/web.php
└── database/seeders/

---🙌 Acknowledgements
|-Laravel Framework
|-Bootstrap
|-Community packages and contributors


## ⚙️ Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/bookstore.git
cd bookstore

# Install dependencies
composer install

# Copy .env and configure
cp .env.example .env
php artisan key:generate

# Set your database credentials in .env
DB_DATABASE=your_database
DB_USERNAME=your_username
DB_PASSWORD=your_password

# Run migrations and seeders
php artisan migrate --seed

# Serve the application
php artisan serve


---

## ⚙️ Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/bookstore.git
cd bookstore

# Install dependencies
composer install

# Copy .env and configure
cp .env.example .env
php artisan key:generate

# Set your database credentials in .env
DB_DATABASE=your_database
DB_USERNAME=your_username
DB_PASSWORD=your_password

# Run migrations and seeders
php artisan migrate --seed

# Serve the application
php artisan serve
>>>>>>> 349591ee8b3be9fbf397bbf9243ab63755b7a1d1
