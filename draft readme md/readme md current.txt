# Group Seller - SI4405

Halo, Selamat datang di halaman Dokumentasi API Kelompok 6 (Seller) 👋

**TokoTelu05** adalah website yang berperan sebagai seller dalam Tugas Besar SI-44-05. Website kami menyediakan data katalog produk yang dapat diconsume oleh kelompok lain.

![preview](https://github.com/albidaud/TokoTelu05-Seller/blob/main/asset/TUBES%20EAI.png)

## About Us

Members of this Group:
| No | Nama | NIM | Role
| ------ | ------ | ------ | ------
| 1 | [Anisa Wahyu Pratiwi](https://www.instagram.com/anisawpr_/) | 1202204051 | `Project Manager`, `System Analyst`
| 2 | [Albi Daud](https://www.instagram.com/the.dwd/) | 1202203332 | `Back-End`
| 3 | [Donna Lolita Harahap](https://www.instagram.com/donalolitaaaa/) | 1202204067 | `Database Administrator`
| 4 | [Muh. Alfikri Tri Anggoro Pamungkas](https://www.instagram.com/mhmmd_alfikri05/) | 1202204169 | `Back-End`
| 5 | [Muhammad Afif Aminuddin](https://www.instagram.com/afifld/) | 1202200320 | `Front-End`

## Features

- Menampilkan katalog produk pada halaman utama website
- Provide API katalog produk yang dapat diconsume kelompok lain

## Tech

Website ini dibangun menggunakan:

- `HTML` - HTML (Hypertext Markup Language) merupakan bahasa markup yang digunakan untuk membangun kerangka website
- `CSS` - CSS (Cascading Style Sheets) merupakan bahasa yang dapat digunakan untuk menentukan tampilan dan format halaman website, seperti jenis font, warna tulisan, dan latar belakang halaman.
- `PHP` - PHP (Hypertext Preprocessor) adalah bahasa pemrograman yang digunakan secara luas untuk penanganan pembuatan dan pengembangan sebuah situs web dan bisa digunakan bersamaan dengan HTML.
- `XAMPP` - XAMPP adalah perangkat lunak berbasis web server yang mendukung di berbagai sistem operasi, baik Windows, Linux, atau Mac OS. XAMPP dapat digunakan sebagai standalone server
- `Visual Studio Code` - Visual Code Studio adalah sebuah code editor gratis yang bisa dijalankan di perangkat desktop berbasis Windows, Linux, dan MacOS
- `Bootstrap` - Bootstrap merupakan framework CSS yang di dalamnya berisi template HTML, CSS, dan JavaScript yang untuk membuat sebuah website yang responsif dengan cepat dan mudah.
- `Microsoft Edge` - Microsoft Edge merupakan browser yang dikembangkan oleh Microsoft. Kami menggunakan browser ini untuk dapat mengakses website yang telah kami hosting
- `000Webhost` - 000Webhosting merupakan web yang menyediakan layanan hosting secara gratis dengan PHP, MySQL, Website Builder, dan cPanel

## Endpoints Usage

**Base URL** : `http://tokotelu05.000webhostapp.com/`
| No | Usage | Endpoint | Method
| ------ | ------ | ------ | ------ 
| 1 | view product catalog | `/get-api.php` | `GET`
| 2 | add product | `/post-api.php` | `POST`
| 3 | update product | `/put-api.php` | `POST`

**1. View Product Catalog**
- Method : `GET`

- Endpoint : `/get-api.php`

Endpoint ini digunakan untuk menampilkan katalog produk dari TokoTelu05 dengan menggunakan method `GET`. Jika request berhasil dilakukan, Postman akan merespon dengan memanggil atau menampilkan semua data katalog produk.


**How to Request**
- Buka aplikasi Postman desktop atau melalui website [Postman](postman.com)
- Pilih method `GET` lalu masukkan link *http://tokotelu05.000webhostapp.com/get-api.php*

```sh
GET http://tokotelu05.000webhostapp.com/get-api.php
``` 
- Klik **Send**

Jika method `GET` berhasil, maka semua data akan ditampilkan seperti pada gambar berikut:

Pada Postman
![get-postman](https://github.com/albidaud/TokoTelu05-Seller/blob/main/asset/get%20tokotelu.png)

Pada Website
![get-website](https://github.com/albidaud/TokoTelu05-Seller/blob/main/asset/LandingPage.png)

---

**2. Add Product**
- Method : `POST`

- Endpoint : `/post-api.php`

Gunakan endpoint ini untuk menambahkan produk baru ke katalog website TokoTelu05. Jika request berhasil, maka Postman akan merespon dengan menampilkan pesan "Berhasil menambahkan data". Dan produk tersebut akan secara otomatis ditampilkan pada website.


**How to Request**
- Buka aplikasi Postman desktop atau melalui website [Postman](postman.com)
- Pilih method `POST` lalu masukkan link *http://tokotelu05.000webhostapp.com/post-api.php*.

```sh
POST http://tokotelu05.000webhostapp.com/post-api.php
```
- Klik **Send**

Jika method `POST` berhasil, maka akan muncul tampilan seperti berikut:

Pada Postman
![post-postman](https://github.com/albidaud/TokoTelu05-Seller/blob/main/asset/post%20nambahin%20produk.png)

Pada Website
![post-website](https://github.com/albidaud/TokoTelu05-Seller/blob/main/asset/tampilan%20post%20produk%20yang%20berhasil%20ditambahkan.png)

---

**3. Update Product**
- Method : `POST`

- Endpoint : `/put-api.php`

Endpoint ini digunakan untuk mengupdate informasi produk pada website TokoTelu05. User perlu menyertakan parameter "ID" agar dapat mengupdate produk berdasarkan ID nya. Jika request berhasil dilakukan, Postman akan merespon dengan menampilkan pesan "Berhasil mengupdate data", dan informasi produk pada website akan terupdate secara otomatis.

**How to Request**
- Buka aplikasi Postman desktop atau melalui website [Postman](postman.com)
- Pilih method `POST` lalu masukkan link berikut _http://tokotelu05.000webhostapp.com/put-api.php_ , dengan menambahkan id produk yang akan diupdate.

```sh
POST http://tokotelu05.000webhostapp.com/put-api.php?id_product=17
```
- Klik **Send**

Jika pada Postman muncul tampilan seperti berikut, maka produk telah berhasil diupdate

Pada Postman
![update-postman](https://github.com/albidaud/TokoTelu05-Seller/blob/main/asset/post%20update%20produk.png)

Sebelum update website
![update-beforewebsite](https://github.com/albidaud/TokoTelu05-Seller/blob/main/asset/sebelum%20update%20website.png)

Sesudah update website
![update-afterwebsite](https://github.com/albidaud/TokoTelu05-Seller/blob/main/asset/pada%20website%20sesudah%20di%20update.png)

Copyright © 2023 TokoTelu05

Made with 💜 by Group 6