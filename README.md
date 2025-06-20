DATABASE RUMAH SAKIT

A). BACKEND DATABASE RUMAH SAKIT
Backend adalah bagian logika dari aplikasi yang akan dijalankan, berikut penjelasan secara singkat :

1. Mengelola data (simpan, ambil, ubah, hapus) di database.

2. Menyediakan API agar data bisa diakses oleh frontend (misalnya HTML, aplikasi mobile, dsb.).

3. Mengatur proses bisnis atau aturan aplikasi (contoh: cek stok obat, validasi input pasien, dsb.).

4. Mengatur autentikasi & keamanan (login, hak akses admin/dokter/pasien).

B). FRONTEND DATABASE RUMAH SAKIT
Laravel adalah framework PHP untuk membangun aplikasi web modern dengan lebih cepat, rapi, dan aman.Laravel menyediakan banyak fitur bawaan (auth, routing, database, API, template view, dsb.) agar developer tidak perlu membuat semuanya dari nol. 
Syarat untuk menginstall Laravel 11 yaitu,
Pastikan sudah terinstal:

1. PHP (versi 8.1 atau lebih baru)

2. Composer (https://getcomposer.org/)

3. Database (MySQL, MariaDB, atau SQLite)

4. Web server (bisa pakai XAMPP, Laragon, atau langsung php artisan serve)

Selanjutnya cara untuk install Laravelsebagai berikut ;
1. Cara Instalasi Laravel Baru
Buka terminal/command prompt lalu jalankan: composer create-project laravel/laravel nama-proyek
2. Kemudian konfigurasi ke database : Buka file .env di root folder Laravel, ubah bagian ini sesuai database
   DB_DATABASE=rumahsakit
   DB_USERNAME=root
   DB_PASSWORD=
3. Membuat migration : php artisan make:migration create_pasien_table, contoh.
4. Jika ingin menjalankan project dapat menggunakan perintah php artisan serve pada terminal.


