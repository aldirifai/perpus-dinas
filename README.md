<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Cara Install

### Clone Github Repository

```bash
git clone https://github.com/aldirifai/perpus-dinas.git
```

### Masuk ke Folder Hasil Clone

```bash
cd perpus-dinas
```

### Install Semua Dependensi yang Dibutuhkan

```bash
composer install
```

### Buat Database Baru

Buat database sebagai tempat penyimpanan sistem ini

### Copy .env.example to .env

Copy file .env.example ke .env

```bash
cp .env.example .env
```

### Setting Database di File .env

```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=nama_database
DB_USERNAME=username
DB_PASSWORD=password
```

### Generate Key Aplikasi

```bash
php artisan key:generate
```

### Migrasi Database

Migrasi semua table dan data yang sudah disediakan

```bash
php artisan migrate --seed
```

### Jalankan Aplikasi

```bash
php artisan serve
```

### Informasi Login Pengguna

| Jenis         | Username | Password |
| ------------- | -------- | -------- |
| Administrator | admin    | admin    |
| Petugas       | petugas  | petugas  |
| Peminjam      | peminjam | peminjam |

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
