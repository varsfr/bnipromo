# Cara Setup Aplikasi BNI Promo

1. Pastikan versi PHP yg terinstall adalah PHP 7.2 keatas, cek dengan cara buka cmd lalu ketik:
   php -v

2. Pastikan MySQL sudah running di komputer Anda

3. Buka cmd di folder root aplikasi, lalu ketik seperti dibawah ini untuk install package composer
   `composer install`

4. Buka file `.env` untuk memastikan konfigurasi MYSQL (host, username, pass) sdh sesuai, lalu buat database dengan nama 'bnipromo'.
   Setelah itu di cmd ketik:

    `php artisan migrate`

5. Untuk menjalankan server, ketik di cmd:

    `php artisan serve`

6. Buka http://localhost:8000 di browser untuk mengakses aplikasi
