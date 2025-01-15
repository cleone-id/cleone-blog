---
title: 'Laragon: Aplikasi Web Server Lokal yang Powerful untuk Pengembangan PHP, Node.js, dan Lainnya'
description: >-
  Pelajari tentang Laragon, aplikasi web server lokal yang ringan, cepat, dan powerful untuk pengembangan PHP, Node.js, Python, dan lainnya.
date: 2024-10-18 10:37:24 +0700
categories: [IT, Programmer]
tags: [it, programmer, komputer, dev, php]
authors: mahaputera
image:
  path: /images/programmer/laragon.webp
  alt: Laragon
---

## Pembuka
Laragon adalah solusi web server lokal yang ringan dan cepat, dirancang untuk memudahkan pengembangan aplikasi berbasis PHP, Node.js, Python, dan lainnya. Dalam artikel ini, kami akan membahas keunggulan Laragon sebagai alternatif XAMPP dan bagaimana Anda dapat menginstalnya untuk mempercepat alur kerja pengembangan.

## Apa itu Aplikasi Web Server?
Aplikasi web server adalah perangkat lunak yang menyediakan layanan HTTP atau HTTPS kepada klien, memungkinkan halaman web diakses melalui internet.
Web server biasanya diinstal dan dijalankan di server, tetapi untuk keperluan pengembangan aplikasi web, server ini juga dapat diinstal pada komputer lokal seorang programmer. Ini memungkinkan programmer menguji halaman web yang sedang mereka buat.

Terdapat beberapa jenis aplikasi web server diantaranya yang populer adalah XAMPP, aplikasi web server untuk development halaman web berbasis PHP. Tetapi XAMPP mempunyai beberapa kekurangan yang terkadang merepotkan seorang programmer, diantaranya config yang rumit, hanya support PHP, kesulitan untuk berganti versi PHP, dan banyak keterbatasan lainnya.

Dari pengalaman saya menggunakan XAMPP, saya berharap ada aplikasi web server lokal yang mudah dalam konfigurasi, instalasi, dan fleksibel dalam development aplikasi. Sampai ada rekan yang menyarankan Laragon. 
Aplikasi web server alternatif selain XAMPP dan aplikasi web server lainnya. Dengan banyak fitur dan sistem yang sangat memudahkan proses development aplikasi.

## Apa itu Laragon?
Laragon bisa dibilang _all in one_ untuk sekelas aplikasi web server. Tidak hanya PHP dan Apache yang biasa ada pada satu aplikasi web server, Laragon juga mengakomodir fitur lain seperti Node.JS, Golang, Ngingx, Python, dan masih banyak lagi.

Konfigurasi Laragon sangat mudah karena pada _interface_ aplikasi konfigurasi sudah ada. Selain sebagai web server Laragon juga membawa aplikasi open source untuk memudahkan development, seperti HeidiSQL, Notepad++, dan Cmder. Testing SSL untuk _environtment_ lokal juga sudah termasuk dalam fitur dan dapat langsung diaktifkan.

### Keunggulan Laragon untuk Pengembangan Web
Laragon mempunyai fitur unggulan diantaranya:
- Performa yang bagus untuk lokal environtment
- Mudah dan Fleksibel
- Auto virtual host untuk URL testing (misalnya: http://app.test), memudahkan pembuatan domain lokal yang disesuaikan.
- Modern dan Powerful

### Download Laragon
Untuk mendownload Laragon, bisa langsung ke website officialnya di: [**DOWNLOAD LARAGON**][laragon]

### Cara Install Laragon

Setelah download versi installer Laragon, silahkan lakukan instalasi. Pada halaman berikut pilih folder tempat dimana akan menyimpan aplikasi dan file Laragon.
Jika sudah kemudian ke tahap selanjutnya yaitu konfigurasi tambahan.

![Install Laragon](/posts/20241018/install_laragon2.png){: width="493" height="385" .w-50 .left}
Pada halaman ini centang "Run Laragon when Windows start", untuk secara otomatis menjalankan Laragon saat menyalakan komputer/laptop. Centang "Auto virtual hosts", untuk otomatisasi vhost menjadi custom domain sementara. (default: app.test), lokal domain ini dapat diubah pada pengaturan.
Kemudian "Add Notepad++ & Terminal" untuk menambahkan fitur Notepad++ dan Cmder pada Laragon. Aplikasi open source tambahan ini akan memudahkan proses development dan konfigurasi Laragon nantinya. Klik next dan selesaikan instalasi.

## Penutup
Itulah cara menginstal Laragon sebagai aplikasi web server lokal untuk pengembangan web. Dengan Laragon, pengaturan yang sederhana namun powerful akan mempercepat alur kerja Anda. Laragon bisa jadi solusi alternatif untuk programmer yang ingin berfokus pada aplikasi karena konfigurasi Laragon simpel dan powerful.
Tertarik mencoba Laragon? Unduh sekarang dan tingkatkan kecepatan pengembangan aplikasi Anda. Nantikan update post dari kami ya untuk info lainnya. Jika ada pertanyaan silahkan tinggalkan di kolom komentar, atau gabung ke diskusi hobi di discord cleone kita, [Join Cleone.ID][cleone.id]

Salam~

[cleone.id]: https://discord.gg/cleone
[laragon]: https://laragon.org/download/




