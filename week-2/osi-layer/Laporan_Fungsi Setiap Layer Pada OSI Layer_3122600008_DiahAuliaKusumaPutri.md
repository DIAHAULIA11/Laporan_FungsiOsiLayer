# KONSEP JARINGAN / 2 D4 IT A / 3122600008 / Diah Aulia Kusuma Putri

# Laporan Deskripsi Fungsi Setiap Layer pada OSI Layer

## 1. Physical Layer

<div align="center">
<img src="../Image/physical-layer.png">
<p><i><strong>gambar 1. </strong>physical layer</i></p>
</div>

Physical layer merupakan lapisan pertama atau paling bawah dalam OSI Layer. Fungsinya yaitu sebagai transmisi terhadap bit data dimana menggunakan sinyal yang harus didukung media fisik seperti kabel, infrared, frekuensi radio, dan tegangan listrik.

## 2. Data Link Layer

<div align="center">
<img src="../Image/data-link-layer.png">
<p><i><strong>gambar 2. </strong>data link layer</i></p>
</div>

Data Link layer merupakan lapisan kedua setelah lapisan Physical layer yang mengirimkan data dalam bentuk paket. Fungsi dari Data Link layer yaitu mendeteksi dan memperbaiki kesalahan ketika proses penyaluran transmisi terhadap bit data. Pada Data Link layer juga dilakukan pengaturan alamat hardware pada MAC address dan juga flow control.

## 3. Network Layer

<div align="center">
<img src="../Image/network-layer.png">
<p><i><strong>gambar 3. </strong>network layer</i></p>
</div>

Network layer memiliki fungsi mendefinisikan setiap alamat IP (Internet Protocol) sehingga setiap komputer dapat terkoneksi dalam satu jaringan. Pada layer ini juga dilakukan proses routing.

## 4. Transport Layer

<div align="center">
<img src="../Image/transport-layer.png">
<p><i><strong>gambar 4. </strong>transport layer</i></p>
</div>

Transport layer berfungsi memecah data kemudian dimasukkan dalam paket data, melakukan transmisi data dari session layer sampai ke network layer, melakukan penomoran untuk setiap paket data agar mudah untuk disusun ulang, melakukan looping terhadap proses transmisi yang ada dalam paket data yang hilang. Protokol seperti TCP (Transmission Control Protocol) dan UDP (User Datagram Protocol) beroperasi dalam lapisan ini.

## 5. Session Layer

<div align="center">
<img src="../Image/session-layer.png">
<p><i><strong>gambar 5. </strong>session layer</i></p>
</div>

Session layer berfungsi mengelola pembukaan, pemeliharaan, dan penutupan sesi komunikasi antara dua perangkat mencakup pengendalian dialog, sinkronisasi, dan pemulihan jika sesi terputus. Contoh protokol yang berada di layer ini adalah NFS, RTP, SMB, dan lainnya.

## 6. Presentation Layer

<div align="center">
<img src="../Image/presentation-layer.png">
<p><i><strong>gambar 6. </strong>presentation layer</i></p>
</div>

Lapisan Presentasi mengelola enkripsi, kompresi, dan konversi format data agar dapat dipahami oleh perangkat penerima. Fungsinya adalah memastikan data dapat diinterpretasikan dengan benar oleh aplikasi penerima. Beberapa protokol yang berada pada layer ini adalah MIME, TLS, SSL, dan lainnya.

## 7. Application Layer

<div align="center">
<img src="../Image/application-layer.png">
<p><i><strong>gambar 7. </strong>application layer</i></p>
</div>

Application layer merupakan layer pusat interaksi dimana terjadi interaksi langsung antara aplikasi dan pengguna sehingga layer ini berada pada bagian paling atas dalam susunan OSI layer. Ini menyediakan layanan seperti pengiriman email, browsing web, transfer file, dan lainnya. Protokol aplikasi seperti HTTP, FTP, SMTP, dan DNS beroperasi dalam lapisan ini.

## Kesimpulan

<div align="center">
<img src="../Image/OsiLayer.png">
<p><strong><i>gambar 8. </strong>OsiLayer</i></p>
</div>

_Model OSI adalah kerangka kerja yang menggambarkan tujuh lapisan berurutan dalam komunikasi jaringan. Setiap lapisan memiliki fungsi uniknya sendiri dan bekerja bersama-sama untuk memungkinkan komunikasi yang efisien di seluruh jaringan. Memahami peran setiap lapisan dalam proses komunikasi membantu dalam perancangan, pengembangan, dan pemeliharaan jaringan yang andal._
