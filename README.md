# Dot-Connect-Game
> Task Seleksi Lab IRK created by Nigel Sahl

versi **[Insert tanggal here]**

```bash
Note: bagian di bawah ini yang ditandai `>` bisa dihapus kalo udah ga dipake guidenya.
```

## 💡 Latar Belakang
> Bebas ini diisi apa, tapi mainly isinya brijing sebelum masuk ke main content nya di deskripsi tugas

**Contoh yang bagus by Kak Dimas - Gomoku Bot Competition:**

Masih ingatkah kalian dengan tugas besar 1 stima kalian ? Kalian diminta membuat bot untuk memenangkan sebuah game kapal perang. Tujuan dari task ini adalah sama, yaitu membuat bot dengan menggunakan algoritma greedy. Tapi pada kali ini, game yang berusaha dimenangkan adalah Gomoku atau sering disebut five in a row. Berbeda dengan task lainnya, task ini akan membandingkan hasil kerja kalian dengan teman seleksi lainnya dalam sebuah kompetisi. Jadi distribusi skor akan berdasarkan pemenang dari kompetisi. Maka kalian harus bisa membuat bot seoptimal mungkin. Good Luck Have Fun!

> Ini contoh kalo mo ngasi gambar di tengah
<div align=center>
<img src="./img/example1.PNG">
<br>
  <b>Fig 1.</b> Contoh tweet yang memiliki indikasi sebagai buzzer tweet
<br>
</div>

<br>

## 📝 Spesifikasi Tugas
> Jelasin secara detail tugasnya ngapain.

**Contoh yang bagus by Kak Kyle - LZW WebApp:**

Berfokus pada metode kompresi LZW, tugas Anda adalah membuat sebuah webapp sederhana yang dapat menerima sekuens string (text layaknya bacaan pada umumnya), mengkompresinya, dan melakukan decode dari sebuah sekuens yang telah dikompresi (decompress).

Berikut merupakan spesifikasinya:

### Spesifikasi Wajib (XXX Poin)
> Jelaskan secara detail spek wajibnya apa, mulai dari detail task sampe constraint dan techstacknya

**Contoh yang bagus by Kak Willy - Course Scheduler:**

Course Scheduler dibuat <b>berbasis web</b>. Bahasa dan Framework dibebaskan untuk Frontend dan tetapi wajib menggunakan <b>Golang</b> untuk Backend dan <b>SQL</b> untuk Basis Data. Course Scheduler harus mengandung beberapa fitur utama di bawah ini:

1. Pembagian <b>Frontend</b> dan <b>Backend</b> wajib dibuat pada repository GitHub yang terpisah.
2. Penambahan data MK (Mata Kuliah) yang dapat dilakukan baik secara satu per satu maupun batch dengan file berformat <b>.json</b>. Data MK terdiri dari:
    - Nama MK
    - Jumlah SKS MK
    - Jurusan atau Fakultas MK
    - Semester minimal pengambilan MK
    - Prediksi nilai MK
        - <b>Note:</b> Nilai berupa A, AB, B, BC, C, D, atau E
3. Aplikasi dapat menerapkan algoritma <b>Dynamic Programming</b> untuk mendapatkan seluruh MK yang dapat diambil sehingga memberikan nilai maksimal dengan input oleh pengguna sebagai berikut.
    - Jurusan atau Fakultas
    - Semester pengambilan MK saat ini
    - Batasan minimal SKS yang dapat diambil
    - Batasan maksimal SKS yang dapat diambil
4. Aplikasi dapat menampilkan <b>visualisasi</b> untuk seluruh MK yang diambil dan menampilkan nilai akhir yang akan didapatkan. Framework untuk visualisasi dibebaskan.
5. Aplikasi dapat dijalankan dengan menggunakan <b>Docker</b> pada lokal komputer baik untuk Frontend, Backend, maupun Basis Data.
    - Buatlah Dockerfile masing-masing untuk Frontend dan Backend agar dapat membuat image pada container.
    - Buatlah script docker-compose pada repository Backend untuk menjalankan container Backend dan Basis Data.
    - Buatlah script docker-compose pada repository Frontend untuk menjalankan container Frontend.
    - Aplikasi pada masing-masing repository dapat dijalankan hanya dengan command ```docker-compose up -d```.
    - Pastikan migrasi basis data dapat berlangsung ketika aplikasi dijalankan.
6. Buatlah readme pada masing-masing repository yang menjelaskan:
    - Deskripsi Program
    - Teknologi dan Framework
    - (Backend) Penjelasan Dynamic Programming
    - (Backend) Analisis Algoritma
    - (Frontend) Screenshot Hasil Percobaan
    - Cara menjalankan aplikasi (docker-compose up -d)
    - Referensi Belajar

### Spesifikasi Bonus (XXX Poin)
> Jelaskan spek bonusnya (kalo ada)

Tulis sebuah README dalam repository mahasiswa yang berisikan:

**Contoh yang bagus by Kak Angel - Tarjans Algorithm:**

1. Implementasikan dalam bentuk Web dengan ketentuan yang sama dengan spesifikasi wajib (input dapat berupa file txt atau text box). Framework untuk frontend dibebaskan, tetapi untuk backend menggunakan Golang.
2. Menampilkan hasil Output berupa graf SCC yang didapat berdasarkan warna vertex atau graf yang berbeda, begitu juga pada bridges, dan runtime program (web tidak perlu dideploy)

### Spesifikasi Lainnya (XXX Poin)
> Tambahin kalo emang ada dan perlu aja

Bisa tambah apapun yang ga dijelasin di spesifikasi diatas

## ❓ Isi Apapun
> Ini bisa diisi dengan apapun yang kalian rasa perlu disamping spesifikasi

**Contoh : Kak Steven - Tubes, tubes, tubes:**
## Hal yang Perlu Diperhatikan
1. Beban tubes didesain untuk dikerjakan oleh 3 mahasiswa
2. Tubes didesain agar selesai dalam waktu 2 minggu
3. Anda boleh menentukan sendiri platform maupun kakas yang akan digunakan dalam
pengerjaan tubes terkait
4. Dua tugas besar yang dipilih harus ditujukan untuk mata kuliah yang berbeda.
    - Spek 1: IF2211 && Spek 2: IF2123 Benar
    - Spek 1: IF2211 && Spek 2: IF2211 Salah
5. Menyusun spek tubes untuk lebih dari 2 mata kuliah memungkinkan adanya Bonus
Point

**Contoh lain : Kak Dimas - Gomoku Bot Competition**
## Teknis Kompetisi
> atau kalo bagian lain misalnya
## Batasan
Misal harus dibawah 10 detik, atau harus $O(N^3)$.

> Anyway emoji bisa diliat di https://emojidb.org/

## 📂 Pengerjaan dan Pengumpulan
> Ini isinya guide gimana kerjainnya dan gimana ngumpulnya.
> Kalo bisa dibuat seragam sama template ini, tapi kalo emang harus beda (misal perlu bikin laporan, atau ketentuan bot misal maksimal 5 submisi), bisa diubah aja sesuai kebutuhan.
1. Buatlah repositori **private** pada github masing-masing dan invite `[your github account]` dalam repositori tersebut.
2. Berkas yang dikumpulkan berupa **link rilis tag ke repositori github** yang telah dibuat dengan ketentuan sebagai berikut.
    - Memberikan tag `vn` pada commit terakhir Anda setiap kali ingin melakukan submisi dengan `n` adalah jumlah submisi yang telah dilakukan. (contoh: `v1` untuk submisi pertama).
    - **Tidak menggunakan *url shortener*** (bit.ly, shortlink, atau yang lain) saat melakukan pengumpulan *task*.
    - Anda dapat melakukan rilis dengan panduan [berikut](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository).
3. **Lakukan submisi** pada website seleksi IRK dengan menggunakan akun std.stei.itb.ac.id, **lakukan konfirmasi** ke LINE `@[Your line ID]`, dan **jadwalkan demo** dengan cara yang sama. Lakukan hal yang sama jika membuat rilis yang baru.
4. Jika terdapat pertanyaan dapat menghubungi LINE `@[Your line ID]`.

## 📌 Penilaian
> Gaperlu yang detail2 banget (kalo mau juga boleh), tapi at least ada transparansi (ga kaya yang kemaren uhuk).

**Contoh yang bagus by Kak Dimas - Gomoku Bot Competition**

Berikut distribusi skor pada pemenang kompetisi setelah kompetisi berakhir:

| Posisi | Poin Seleksi |
| ----------- | ----------- |
| 1   | 2300 |
| 2   | 2185 |
| 3   | 2070 |
| 4   | 1955 |
| 5 - dst   | 1840 |

**Contoh yang detail by Kak Kyle - LZW WebApp**

![Screenshot](./img/kyle.png)

## 📚 Referensi
> Ya kalo emang perlu aja. Gua meng-encourage kalian buat ga ngasih kalo masih bisa dicari di internet, biar explore sendiri.

**Contoh yang susah by Kak Brian - Implementasi Kriptografi Sederhana++**

![Screenshot](./img/bryan.png)

<br>
<br>

> Nah terakhir bagian ini kalo mau nambahin kata-kata penyemangat atau credit, bebas, misalnya...

**Good Luck!**