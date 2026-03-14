# PROJECT ARRAY STRUKTUR DATA
# Dhananjaya(2501010023)
# Penjelasan konsep Array :
Array adalah struktur data linier yang digunakan untuk menyimpan sekumpulan data dengan tipe yang sama dalam satu variabel. Data dalam array disimpan secara berurutan di dalam memori dan setiap elemen memiliki indeks yang digunakan untuk mengakses data tersebut. Dengan adanya indeks, setiap elemen dalam array dapat diakses secara langsung tanpa harus membaca seluruh data terlebih dahulu.

Dalam program yang dibuat, array digunakan untuk menyimpan nilai mahasiswa yang dimasukkan oleh pengguna. Semua nilai yang diinput akan disimpan ke dalam satu array sehingga data tersebut dapat digunakan untuk berbagai proses perhitungan, seperti mencari nilai tertinggi, nilai terendah, menghitung rata-rata nilai, serta menentukan jumlah mahasiswa yang lulus dan tidak lulus.

Contoh penggunaan array dalam program adalah ketika nilai mahasiswa disimpan ke dalam variabel arr. Array tersebut kemudian berisi data nilai mahasiswa seperti:

[67, 70, 50, 53, 45, 90, 95, 100, 78, 47]

Pada contoh tersebut setiap nilai memiliki indeks, misalnya indeks 0 berisi nilai 67, indeks 1 berisi nilai 70, dan seterusnya. Data yang tersimpan dalam array inilah yang kemudian diproses oleh program untuk melakukan berbagai perhitungan statistik terhadap nilai mahasiswa.

# Screenshot Hasil Eksekusi
![image alt](https://github.com/Nanzz1112/Project/blob/ad60b347b00867b80cef8cea0d257108033dddf2/img/Screenshot%202026-03-14%20123641.png)

![image alt](https://github.com/Nanzz1112/Project/blob/1d240943827e191c25894446ba8848e3bede5b61/img/Screenshot%202026-03-14%20123648.png)

![image alt](https://github.com/Nanzz1112/Project/blob/1d240943827e191c25894446ba8848e3bede5b61/img/Screenshot%202026-03-14%20123702.png)

![image alt](https://github.com/Nanzz1112/Project/blob/1d240943827e191c25894446ba8848e3bede5b61/img/Screenshot%202026-03-14%20123709.png)

![image alt](https://github.com/Nanzz1112/Project/blob/1d240943827e191c25894446ba8848e3bede5b61/img/Screenshot%202026-03-14%20123718.png)

# Analisis
| Operasi | Kompleksitas |
| --- | --- |
| Input nilai mahasiswa | O(n) |
| Menghitung nilai tertinggi	| O(n) |
| Menghitung nilai terendah | O(n) |
| Menghitung rata-rata nilai | O(n) |
| Menghitung jumlah mahasiswa lulus | O(n) |
| Menghitung jumlah mahasiswa tidak lulus | O(n) |
| Menampilkan grafik batang | O(n) |

# Input Nilai Mahasiswa
Pada tahap ini program meminta pengguna memasukkan nilai mahasiswa secara berulang. Setiap nilai yang dimasukkan akan disimpan ke dalam array hingga jumlah data yang diinginkan tercapai. Karena proses ini dilakukan untuk setiap data yang dimasukkan, maka jumlah langkah yang dilakukan program akan bertambah seiring dengan bertambahnya jumlah nilai mahasiswa.

## Kompleksitas waktu: O(n)

# Menentukan Nilai Tertinggi dan Nilai Terendah
Setelah seluruh nilai tersimpan di dalam array, program kemudian mencari nilai tertinggi dan nilai terendah. Untuk mendapatkan kedua nilai tersebut, program harus membaca dan membandingkan setiap elemen yang terdapat dalam array sampai semua data diperiksa. Karena seluruh elemen harus diproses, waktu yang dibutuhkan bergantung pada banyaknya data yang ada.

## Kompleksitas waktu: O(n)

# Menghitung Rata-rata Nilai Mahasiswa
Proses selanjutnya adalah menghitung rata-rata nilai. Rata-rata diperoleh dengan menjumlahkan seluruh nilai mahasiswa yang terdapat dalam array, kemudian hasilnya dibagi dengan jumlah data yang tersedia. Agar mendapatkan total nilai, program harus membaca setiap elemen yang tersimpan di dalam array terlebih dahulu.

## Kompleksitas waktu: O(n)

# Menentukan Jumlah Mahasiswa Lulus dan Tidak Lulus
Program kemudian melakukan pengecekan terhadap setiap nilai mahasiswa untuk menentukan apakah mahasiswa tersebut lulus atau tidak. Nilai akan dibandingkan dengan batas kelulusan yang telah ditentukan. Jika nilai memenuhi syarat kelulusan maka jumlah mahasiswa yang lulus akan bertambah, sedangkan jika tidak memenuhi syarat maka akan dihitung sebagai tidak lulus. Proses ini dilakukan untuk seluruh data yang terdapat dalam array.

## Kompleksitas waktu: O(n)

# Menampilkan Grafik Nilai
Pada tahap akhir, program menampilkan hasil pengolahan data dalam bentuk grafik batang. Grafik ini dibuat berdasarkan data yang telah dihitung sebelumnya, seperti nilai tertinggi dan nilai terendah. Proses pembuatan grafik memanfaatkan data yang tersedia sehingga tetap berkaitan dengan jumlah data yang diproses dalam program.

## Kompleksitas waktu: O(n)

Secara keseluruhan, sebagian besar proses dalam program memiliki kompleksitas waktu O(n). Hal ini terjadi karena hampir setiap langkah pengolahan data membutuhkan pemeriksaan terhadap seluruh nilai mahasiswa yang tersimpan di dalam array. Dengan demikian, jika jumlah data mahasiswa bertambah, maka waktu yang diperlukan oleh program juga akan meningkat secara linear mengikuti jumlah data tersebut.
