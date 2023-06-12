# Group Seller - SI4405

Halo, Selamat datang di halaman Dokumentasi API Kelompok 6 (Seller) 👋

**TokoTelu05** adalah website yang berperan sebagai seller dalam Tugas Besar SI-44-05. Website kami menyediakan data katalog produk yang dapat diconsume oleh kelompok lain.

![preview](https://github.com/albidaud/TokoTelu05-Seller/blob/main/asset/TUBES%20EAI.png)

# About Us

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
| No | Endpoint | Usage
| ------ | ------ | ------
| 1 | view product catalog | `/get-api.php`
| 2 | add product | `/post-api.php`
| 3 | update product | `/put-api.php`

**View Product Catalog**

- Buka aplikasi Postman desktop atau melalui website [Postman](postman.com)
- Pada Postman, pilih method `GET` lalu masukkan link berikut. Setelah itu klik "Send"

```sh
http://tokotelu05.000webhostapp.com/get-api.php
```

Jika method `GET` berhasil, maka akan muncul tampilan seperti berikut:
Pada Postman
![get-postman](https://github.com/albidaud/TokoTelu05-Seller/blob/main/asset/get%20tokotelu.png)

Pada Website
![get-website](https://github.com/albidaud/TokoTelu05-Seller/blob/main/asset/LandingPage.png)

**Add Product**

- Buka aplikasi Postman desktop atau melalui website [Postman](postman.com)
- Pada Postman, pilih method `POST` lalu masukkan link berikut. Setelah itu klik "Send"

```sh
http://tokotelu05.000webhostapp.com/post-api.php
```

Jika method `POST` berhasil, maka akan muncul tampilan seperti berikut:
Pada Postman
![post-postman](https://github.com/albidaud/TokoTelu05-Seller/blob/main/asset/post%20nambahin%20produk.png)

Pada Website
![post-website](https://github.com/albidaud/TokoTelu05-Seller/blob/main/asset/tampilan%20post%20produk%20yang%20berhasil%20ditambahkan.png)

**Update Product**

- Buka aplikasi Postman desktop atau melalui website [Postman](postman.com)
- Pada Postman, pilih method `POST` lalu masukkan link berikut, dengan menambahkan id produk yang akan diupdate. Setelah itu klik "Send"

```sh
http://tokotelu05.000webhostapp.com/put-api.php
```

Berikut contoh link yang sudah ditentukan id produk dari produk yang akan diupdate

```sh
http://tokotelu05.000webhostapp.com/put-api.php?id_product=17
```

Jika muncul tampilan seperti berikut, maka produk telah berhasil diupdate
Pada Postman
![update-postman](https://github.com/albidaud/TokoTelu05-Seller/blob/main/asset/post%20update%20produk.png)

Sebelum update website
![update-beforewebsite](https://github.com/albidaud/TokoTelu05-Seller/blob/main/asset/sebelum%20update%20website.png)

Sesudah update website
![update-afterwebsite](https://github.com/albidaud/TokoTelu05-Seller/blob/main/asset/pada%20website%20sesudah%20di%20update.png)

Copyright © 2023 TokoTelu05
Made with 💜 by Group 6
