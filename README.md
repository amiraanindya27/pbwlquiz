## Cara Instalasi
1. Clone project `https://github.com/amiraanindya27/pbwlquiz.git` 
2. Masuk ke direktori project `cd pbwlquiz` 
3. Install semua dependensi `composer install` 
4. Copy file .env.example `cp .env.example .env`
5. Generate key dengan `php artisan key:generate`
6. Konfigurasi database di file `.env`
7. Migrasi database `php artisan migrate --seed`
8. Jalankan server `php artisan serv`

### Default Login 
```
Email: admin@gmail.com
Password: admin
```
