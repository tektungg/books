# Nama : Rama Pramudhita Bhaskara
# NIM : 2241720128
# Kelas : TI 3-H

## Praktikum 1: Mengunduh Data dari Web Service (API)
### Soal 1
![Alt text](assets\img\soal1.png)
### Soal 2
![Alt text](assets\img\soal2.png)
### Soal 3
Substring digunakan untuk menampilkan karakter sesuai dengan parameter yang dikirimkan. pada contoh di atas menggunakan substring(0, 450) dimana nilai string akan ditampilkan mulai dari karakter pertama (0) hingga karakter terakhir (450). Sedangkan untuk catchError digunakan untuk menangani kesalahan yang mungkin terjadi saat program sedang berjalan.

![Alt text](assets\img\soal3.png)

## Praktikum 2: Menggunakan await/async untuk menghindari callbacks
### Soal 4
Pada langkah 1 kita menambahkan 3 method yang digunakan untuk menambahkan waktu tunggu selama 3 detik per method (total 9 detik) dan ketiga method tersebut mengembalikan nilai mereka masing-masing. Pada langkah 2 kita menambahkan metod count() untuk menjumlahkan nilai yang dikirimkan oleh 3 method sebelumnya.

![Alt text](assets\img\soal4.gif)

## Praktikum 3: Menggunakan Completer di Future
### Soal 5
Pada langkah 2 kita menambahkan 2 method baru pada main.dart. method pertama digunakan untuk mendapatkan angka, sedangkan completer digunakan untuk menyelesaikan method dengan waktu yang sudah ditentukan. Sedangkan method kedua digunakan untuk memberikan/mengirimkan angka saat method ini dipanggul/digunakan.

![Alt text](assets\img\soal5.gif)

### Soal 6
Pada langkah 5 kita membungkus kode yang sudah kita buat sebelumnya pada langkah 2 menggunakan try-catch. Penggunaan try-catch ini berfungsi untuk menghandle error yang muncul saat program sedang berjalan. Sedangkan langkah 6 memiliki fungsi yang hampir sama dengan langkah 5, tetapi pada langkah ini berguna untuk menghandle error saat button ditekan.

![Alt text](assets\img\soal6.gif)

## Praktikum 4: Memanggil Future secara paralel
### Soal 7
![Alt text](assets\img\soal7.gif)

### Soal 8
Perbedaan dalam penggunaan FutureGroup dan Future.wait terletak pada tingkat fleksibilitas kedua metode tersebut. Pada FutureGroup kita dapat menambahkan Future/method secara dinamis, berbeda dengan Future.wait, kita tidak dapat melakukan hal yang sama seperti pada FutureGroup karena metode ini akan menambahkan Future/method saat Future.wait dijalankan. Oleh karena itu, FutureGroup dinilai lebih fleksibel dalam penambahan Future/method baru

## Praktikum 5: Menangani Respon Error pada Async Code
### Soal 9
![Alt text](assets\img\soal9.gif)

### Soal 10
Pada langkah 1 kode tersebut hanya menampilkan pesan error ketika fungsi tersebut dipanggil, sedangkan pada langkah 4 memanfaatkan try-catch untuk memastikan proses pemanggiran fungsi returnError() berjalan dengan benar dan jika terdapat error, kode pada bagian catch akan dijalankan untuk menampilkan pesan error,


## Praktikum 6: Menggunakan Future dengan StatefulWidget
### Soal 12
 Apakah Anda mendapatkan koordinat GPS ketika run di browser? Mengapa demikian?
 Jawaban: Bisa, Hal ini dikarenakan pada saat browser terbuka dan meminta izin akses lokasi saya izinkan.

 ![Alt text](assets\img\soal12.gif)

## Praktikum 7: Manajemen Future dengan FutureBuilder

## Praktikum 8: Navigation route dengan Future Function

## Praktikum 9: Memanfaatkan async/await dengan Widget Dialog