# LaravelRESTAPI

Adinda Hashina - 18104026

## Instalasi

1.  Clone repository ini
2.  Buka cmd/terminal pada folder yang telah di clone lalu jalankan perntah berikut

         composer install

3.  Lalu migrate database dengan menjalankan perintah

         php artisan migrate

4.  Gunakanlah seeder untuk data dummy awalan, jalankan perintah berikut

    php artisan db:seed --class=MahasiswaSeeder

5.  Terakhir jalankan server dengen menggunaan perintah

         php artisan serve

## Cara Penggunaan

- Daftar endpoint api

| Method | Endpoint     | Parameter                    |
| ------ | ------------ | ---------------------------- |
| get    | /person      | none                         |
| post   | /person      | body(nik, nama, alamt, umur) |
| put    | /person/{id} | body(nik, nama, alamt, umur) |
| delete | /person      | none                         |
