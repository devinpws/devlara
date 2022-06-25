# Devlara
File belajar laravel documentation

### Instalasi Laravel 9
Masuk ke htdocs (sudah install xampp  dan git terlebih dahulu) buka git bash lalu jalankan perintah berikut, dengan catatan sudah install composer terlebih dahulu :
```
composer create-project laravel/laravel example-app
 
cd example-app
 
php artisan serve
```
Selanjutnya setelah semuanya jalan akan muncul link localhost untuk akses laravel project kita. yaitu sebagai berikut:
```
http://127.0.0.1:8000/
```
### Koneksi ke database
masuk ke folder project dan temukan file ```.env``` lalu ubah database (buat db dulu di phpmyadmin), berikut adalah file yang diubah:
```
DB_DATABASE=devlara #sesuaikan ya
DB_USERNAME=root
DB_PASSWORD=
```
Jalankan migrate tabel dengan perintah berikut di git bash:
```
php artisan migrate
```
Buat tabel baru jalankan perintah berikut:
```
php artisan make:migration create_masyarakat_table
```
