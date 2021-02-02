# Big-Project-Laravel
This repository will be save for Laravel Project.
System-Olshop will be making with Framework Laravel and will be integrate with Rajaongkir API and also Payment Gateway with Midtrans.

Membuat Sistem-Olshop menggunakan Framework Laravel dan API Rajaongkir.

Cara menggunakan :

Download repository dan ekstrak atau clone repository

 $ git clone https://github.com/kadekframa/Big-Project-Laravel.git

Masuk ke direktori aplikasi dan jalankan composer

 $ cd laravel-simplePOS
 $ composer install

Setting .env dan key application

 $ mv .env.example .env
 $ php artisan key:generate

Edit database name, database username dan database password

DB_DATABASE=your_db.
DB_USERNAME=your_mysql_username.
DB_PASSWORD=your_mysql_password.

Migrate table

 $ php artisan migrate
Buka browser di 127.0.0.1:8000

Register new account

Login