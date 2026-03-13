# TUGAS ARRAY STRUKTUR DATA

## Konsep Array :mag_right:

Array adalah struktur data yang digunakan untuk menyimpan sekumpulan data dengan tipe yang sama dalam satu variabel. Data dalam array disimpan secara berurutan di dalam memori dan setiap elemen dapat diakses menggunakan indeks. Indeks biasanya dimulai dari angka 0, sehingga elemen pertama memiliki indeks 0, elemen kedua memiliki indeks 1, dan seterusnya.

Dalam program ini, array digunakan untuk menyimpan nilai mahasiswa. Dengan menggunakan array, proses pengolahan data seperti mencari nilai tertinggi, nilai terendah, menghitung rata-rata, serta menghitung jumlah mahasiswa yang lulus dapat dilakukan dengan lebih mudah dan terstruktur.

Contoh penggunaan Array dalam pemrograman python

```
nilai = [90, 80, 70]
```
Pada contoh tersebut, semua nilai disimpan dalam satu variabel yaitu nilai.

## Screenshot hasil eksekusi :floppy_disk:

![image alt](https://github.com/BebekTerbang334/01-Array/blob/85b66a12e80ee38031bed6f383d1b3abe12f7b09/Screenshot%202026-03-13%20234117.png)

![image alt](https://github.com/BebekTerbang334/01-Array/blob/85b66a12e80ee38031bed6f383d1b3abe12f7b09/Screenshot%202026-03-13%20234127.png)

![image alt](https://github.com/BebekTerbang334/01-Array/blob/85b66a12e80ee38031bed6f383d1b3abe12f7b09/Screenshot%202026-03-13%20234136.png)

![image alt](https://github.com/BebekTerbang334/01-Array/blob/85b66a12e80ee38031bed6f383d1b3abe12f7b09/Screenshot%202026-03-13%20234146.png)

![image alt](https://github.com/BebekTerbang334/01-Array/blob/85b66a12e80ee38031bed6f383d1b3abe12f7b09/Screenshot%202026-03-13%20234152.png)

## Analisis Kompleksitas :bookmark_tabs:

| Operasi | Kompleksitas |
| --- | --- |
| Input Nilai | O(n) |
| Mencari Nilai Tertinggi | O(n) |
| Mencari Nilai Terendah | O(n) |
| Menghitung Rata - Rata | O(n) |
| Menghitung Jumlah Lulus | O(n) |
| Menampilkan Jumlah Grafik | O(n) |

### Input Nilai Mahasiswa
Program melakukan proses pengulangan untuk memasukkan setiap nilai mahasiswa ke dalam array. Setiap data dimasukkan satu per satu sampai jumlah nilai yang dibutuhkan terpenuhi. Karena jumlah langkah bergantung pada banyaknya data yang dimasukkan, maka waktu yang dibutuhkan akan meningkat seiring bertambahnya jumlah mahasiswa.

**Kompleksitas waktu: O(n)**

### Menentukan Nilai Tertinggi dan Nilai Terendah
Untuk mendapatkan nilai maksimum dan minimum, program harus membandingkan seluruh nilai yang terdapat dalam array. Proses ini dilakukan dengan membaca setiap elemen hingga semua data diperiksa. Oleh karena itu, waktu eksekusi bergantung pada jumlah data yang ada.

**Kompleksitas waktu: O(n)**

### Menghitung Rata-rata Nilai
Rata-rata diperoleh dengan menjumlahkan seluruh nilai mahasiswa terlebih dahulu, kemudian hasil penjumlahan tersebut dibagi dengan jumlah data yang tersedia. Karena semua nilai harus diproses untuk mendapatkan totalnya, maka proses ini memerlukan pemeriksaan terhadap seluruh elemen array.

**Kompleksitas waktu: O(n)**

### Menghitung Jumlah Mahasiswa yang Lulus
Program melakukan pengecekan pada setiap nilai untuk menentukan apakah nilainya memenuhi syarat kelulusan, yaitu minimal 60. Jika nilai memenuhi kriteria, maka jumlah mahasiswa yang lulus akan bertambah. Proses ini harus dilakukan untuk semua data nilai yang ada.

**Kompleksitas waktu: O(n)**

### Menampilkan Grafik Data Nilai
Grafik dibuat dengan memanfaatkan data yang telah diperoleh dari proses sebelumnya, seperti nilai tertinggi, nilai terendah, serta jumlah mahasiswa yang lulus dan tidak lulus. Proses pembuatan grafik bergantung pada data yang tersedia sehingga waktu yang diperlukan tetap berkaitan dengan jumlah data yang diproses sebelumnya.

**Kompleksitas waktu: O(n)**

> Sebagian besar operasi dalam tugas ini memiliki kompleksitas waktu O(n) karena setiap proses perlu memeriksa seluruh data nilai mahasiswa yang tersimpan dalam array. Proses seperti memasukkan nilai, mencari nilai tertinggi dan terendah, menghitung rata-rata, serta menentukan jumlah mahasiswa yang lulus dilakukan dengan cara membaca setiap elemen satu per satu. Oleh karena itu, semakin banyak data mahasiswa yang diproses, maka waktu yang dibutuhkan oleh program juga akan meningkat secara linear.

## Refleksi Pembelajaran :mortar_board:

Melalui pembuatan program ini, saya dapat memahami bagaimana konsep array digunakan untuk menyimpan dan mengolah sekumpulan data secara efisien. Selain itu, saya juga belajar bagaimana melakukan berbagai operasi dasar pada array seperti mencari nilai maksimum dan minimum, menghitung rata-rata, serta melakukan pengecekan kondisi pada setiap elemen data.

Saya juga memahami pentingnya analisis kompleksitas algoritma untuk mengetahui seberapa efisien suatu program dalam memproses data. Dengan mengetahui kompleksitas waktu, kita dapat memperkirakan performa program ketika jumlah data semakin besar.
