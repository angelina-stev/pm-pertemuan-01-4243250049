# Tugas Rutin 1 - Pemrograman Mobile

Nama    : Angelina S. Saragih  
NIM     : 4243250049 
Kelas   : PSIK 24C 


## Spesifikasi Perangkat & Tangkapan Layar

-Flutter Version: ![Flutter Version](<screenshot/Flutter Version.png>)

-Flutter Doctor: ![Flutter Doctor](<screenshot/Flutter Doctor.png>)

-Tampilan Aplikasi: ![Tampilan Aplikasi](<screenshot/Tampilan Aplikasi.png>)


## Kendala & Solusi

1. Kendala : Perintah 'flutter' tidak langsung terdeteksi di Terminal VS Code saat baru pertama kali menjalankan proyek.  
   Solusi : Memeriksa dan menambahkan path folder SDK Flutter ke dalam Environment Variables sistem, lalu memuat ulang (restart) VS Code agar perintah dapat dieksekusi.

2. Kendala : Kebingungan menentukan versi Flutter yang aktif di perangkat untuk dimasukkan ke dalam dokumentasi README.  
   Solusi : Menjalankan perintah 'flutter --version' di terminal untuk mengecek versi SDK dan Dart yang terpasang secara tepat.


## Pernyataan Penggunaan AI

Dalam pengerjaan Tugas Rutin 1 ini, AI (Gemini) digunakan sebagai media diskusi untuk membantu memahami penataan layout dasar widget Flutter (SizedBox, Card, Column), pencarian referensi, memberikan petunjuk struktur dokumentasi README.md serta penggunaan Git dan Github.



## Esai (150–250 Kata): Perbandingan Native, Hybrid, dan Cross-Platform

Pengembangan aplikasi mobile umumnya menggunakan tiga pendekatan utama: Native, Hybrid, dan Cross-Platform.

Native adalah pengembangan aplikasi yang ditulis menggunakan bahasa khusus platform, seperti Kotlin untuk Android atau Swift untuk iOS. Pendekatan ini memberikan performa paling tinggi serta akses penuh ke fitur hardware. Contoh kasus penggunaannya adalah aplikasi game 3D berkinerja tinggi atau aplikasi pengolah grafis berat seperti *Adobe Lightroom Mobile*.

Hybrid menggunakan teknologi web seperti HTML, CSS, dan JavaScript yang dijalankan di dalam wadah webview native (misalnya Ionic). Pendekatan ini sangat hemat waktu dan biaya karena berbasis web, namun performanya relatif paling rendah. Contoh kasusnya adalah aplikasi portal berita sederhana atau katalog produk internal perusahaan.

Cross-Platform memungkinkan developer menulis satu codebase saja untuk dijalankan di Android dan iOS (misalnya Flutter atau React Native). Pendekatan ini memberikan keseimbangan terbaik antara kecepatan pengembangan dan performa yang mendekati native. Contoh kasus penggunaannya adalah aplikasi e-commerce dan media sosial modern seperti Instagram dan Grab.