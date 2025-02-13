Repositori ini berisi website sederhana untuk mengingatkan pentingnya shalat, menyediakan Dashboard Admin dan Dashboard User, serta fitur jadwal shalat real-time menggunakan API Aladhan.

Demo

Website dapat diakses di:

branpedia.github.io/Website-Pengingat-shalat/


Fitur

1. Halaman Beranda

Memuat teks dinamis (efek typewriter) tentang pentingnya shalat.

Menampilkan manfaat shalat.

Formulir laporan pengguna (disimpan di localStorage).



2. Dashboard Admin

Login khusus admin (role: "admin").

Dapat mengelola konten beranda (preview konten).

Menampilkan laporan dari pengguna.



3. Dashboard User

Login khusus user (role: "user").

Menampilkan profil user (username, password, role).

Fitur upload foto profil (disimpan di localStorage).

Jadwal sholat real-time berdasarkan nama kota (API Aladhan).




Struktur Folder

Umumnya, struktur sederhana seperti:

.
├── index.html          # Halaman utama
├── styles.css          # (Opsional) Jika Anda pisahkan CSS
├── script.js           # (Opsional) Jika Anda pisahkan JavaScript
├── README.md           # Dokumentasi / petunjuk penggunaan
└── .nojekyll           # (Opsional) Nonaktifkan Jekyll di GitHub Pages

> Catatan: Apabila Anda memisahkan file CSS atau JS, pastikan link <link rel="stylesheet" ...> dan <script src="..."> mengarah ke path yang benar.



Cara Menggunakan

1. Kunjungi situs branpedia.github.io/Website-Pengingat-shalat/.


2. Beranda akan muncul otomatis.


3. Untuk mengakses Dashboard Admin:

Klik "Dashboard Admin" di navigasi.

Masukkan username & password akun admin (pastikan sudah terdaftar sebagai "admin").



4. Untuk mengakses Dashboard User:

Klik "Dashboard User" di navigasi.

Jika belum punya akun, daftar user baru di form pendaftaran (pastikan role: "user").



5. Fitur Jadwal Sholat ada di Dashboard User:

Masukkan nama kota (mis. "Jakarta"), klik "Cek Jadwal".

Tunggu beberapa detik hingga jadwal sholat ditampilkan.




Penyimpanan Data

Akun Admin/User dan laporan disimpan di localStorage browser. Sehingga data bersifat lokal pada perangkat/browser yang sama.

Foto Profil juga disimpan di localStorage sebagai base64 string.


Menjalankan Secara Lokal

1. Clone repo atau download file .zip.


2. Buka index.html di browser (cukup dobel klik atau seret ke tab browser).


3. Jika memisahkan CSS/JS, pastikan link <link rel="stylesheet"> dan <script src="..."> sudah mengarah dengan benar.



Kendala Tampilan di GitHub Pages?

Pastikan menambahkan file kosong .nojekyll di root repo, agar GitHub Pages tidak menimpa file statis.

Pastikan index.html berada di root (atau folder docs sesuai pengaturan) dan pengaturan Pages di Settings > Pages sudah sesuai.


Lisensi

Bebas digunakan untuk pembelajaran atau pengembangan. Jika ada penambahan fitur, mohon disesuaikan dengan kebijakan masing-masing.
