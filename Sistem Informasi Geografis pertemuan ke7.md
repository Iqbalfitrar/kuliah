nama : iqbal fitra ramadhan
npm : 1144023
kelas : D4TI 3C

Mapserver dan Mapproxy
1. Latar Belakang 
MAP Server, adalah aplikasi untuk mngubah data vektor geospasial menjadi gambar ditampilkan sebagai web service. MAP PROXY ,berfungsi untuk menampung hasil gambar dari mapserver agar konsumsi komputasi bisa direduksi.

2.  Pembahasan

a. Pengertian MapServer

MapServer adalah sebuah lingkungan pengembangan open source untuk membangun aplikasi internet spasial diaktifkan. Hal ini dapat dijalankan sebagai program CGI atau melalui Mapscript yang mendukung beberapa bahasa pemrograman (menggunakan SWIG). MapServer dikembangkan oleh University of Minnesota - jadi, sering dan lebih khusus disebut sebagai "UMN MapServer", untuk membedakannya dari komersial "peta server". MapServer awalnya dikembangkan dengan dukungan dari NASA, yang membutuhkan cara untuk membuat citra satelit yang tersedia untuk umum.

b. Pengertian MapProxy

MapProxy adalah open source ubin geospasial proxy yang mendukung proyeksi ulang. Awalnya dikembangkan oleh Omniscale Mapproxy adalah server proxy python untuk gambar geospasial. Hal ini dapat membaca data dari WMS, ubin, mapserver dan mapnik, dan cache dan melayani data bahwa sebagai WMS, WMTS, TMS dan KML. Hal ini juga dapat melakukan reprojections antara berbagai sistem koordinat referensi

c. Fitur MAP Server

• Mendukung format data standar industri dan database spasial
• On-the-fly klasifikasi fitur
• Canggih label berbasis aturan
• On-the-fly proyeksi untuk kedua raster dan data vektor
• Menyediakan berbagai macam pertanyaan spasial dan atribut berbasis
• Mendukung populer Terbuka Geospatial Consortium (OGC) standar termasuk WMS, WFS dan WCS
• Memanfaatkan best-of-breed teknologi open source geospatial seperti GDAL / OGR, PostGIS dan PROJ.4
• Terintegrasi dengan lingkungan front-end populer seperti ka-Peta, Chameleon, Mapbender, MapBuilder dan Cartoweb

d. Install MapServer 

-          Jika tidak menggunakan centos maka jalankan melalui Virtual Box.
-          Setelah itu pastikan koneksi jaringan virtual box bisa diakses dari komputer host
-          Buka terminal, login sebagai root
-          Ketikkan “#install mapserver 5
-          Tunggu hingga proses install selesai.
e. Install MapProxy
 
-          Ketikkan “#install python-pip dan python-dev”
-          Lalu “#pip install mapproxy”
-          Setelah itu ketikkan “#install Vwsqi”
-          Tunggu hingga proses selesai.

3.  Penutup
A. Kesimpulan :  
MapServer adalah sebuah lingkungan pengembangan open source untuk membangun aplikasi internet spasial diaktifkan. MapProxy adalah open source ubin geospasial proxy yang mendukung proyeksi ulang.
   
B. Saran :  
Selanjutnya untuk mendalami materi MapServer dan Map Proxy diharuskan membaca sumber-sumber yang lain serta melakukan praktikum mandiri.

