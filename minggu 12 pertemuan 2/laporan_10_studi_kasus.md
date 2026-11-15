# Laporan 10 Studi Kasus JavaScript

## Pendahuluan

Laporan ini menjelaskan sepuluh contoh dasar JavaScript yang telah dibuat. Setiap studi kasus menyertakan gambaran output dan penjelasan mengenai hasilnya. Output untuk contoh yang meminta input atau menunggu aksi pengguna ditampilkan menggunakan contoh input yang disebutkan.

## 1. Pengenalan JavaScript

**File:** [pengenalanjavascript.html](./pengenalanjavascript.html)

**Output di halaman:**

```text
Belajar JavaScript
Hello World!
```

**Penjelasan:** Elemen `<h2>` menampilkan judul. Perintah `document.write()` menambahkan teks `Hello World!` ke halaman. Contoh ini memperlihatkan cara sederhana JavaScript menampilkan teks.

## 2. Variabel

**File:** [variabel.html](./variabel.html)

**Output di halaman:**

```text
Jurusan : Tekonologi Informasi
Prodi : Teknik Informatika
Semester : 1
Status : true
```

**Penjelasan:** Variabel menyimpan data dengan tipe berbeda: teks (`jurusan` dan `prodi`), angka (`semester`), dan boolean (`status`). Output mengikuti nilai yang ditulis di dalam program. Ejaan `Tekonologi` pada output mengikuti isi file sumber.

## 3. Operator Aritmatika

**File:** [operator.html](./operator.html)

**Output di halaman:**

```text
Hasil Penjumlahan : 15
Hasil Pengurangan : 5
Hasil Perkalian : 50
Hasil Pembagian : 2
Hasil Modulo : 0
```

**Penjelasan:** Program menghitung operasi antara `a = 10` dan `b = 5`. Operator `+`, `-`, `*`, dan `/` masing-masing menghasilkan penjumlahan, pengurangan, perkalian, dan pembagian. Operator `%` menghasilkan sisa pembagian; sisa dari 10 dibagi 5 adalah 0.

## 4. Percabangan IF

**File:** [percabangan.html](./percabangan.html)

**Output di halaman:**

```text
Selamat, kamu lulus Matakuliah Workshop Desain Aplikasi!
```

**Penjelasan:** Nilai pada program adalah 80. Kondisi `nilai >= 75` bernilai benar, sehingga blok `if` dijalankan dan pesan kelulusan ditampilkan. Jika nilainya kurang dari 75, program menampilkan pesan pada blok `else`.

## 5. Pengulangan (Loop)

**File:** [perulangan.html](./perulangan.html)

**Output di halaman:**

```text
Perulangan ke-1
Perulangan ke-2
Perulangan ke-3
Perulangan ke-4
Perulangan ke-5
```

**Penjelasan:** Perulangan `for` dimulai dari `i = 1`, berjalan selama `i <= 5`, dan menambah nilai `i` satu per satu. Karena itu, perintah untuk menampilkan teks dijalankan sebanyak lima kali.

## 6. Fungsi

**File:** [fungsi.html](./fungsi.html)

**Output di halaman:**

```text
Halo Mahasiswa Program Studi, Teknik Informatika!
```

**Penjelasan:** Fungsi `salam(prodi)` menerima nama program studi sebagai parameter, lalu mengembalikan teks sapaan. Fungsi dipanggil dengan argumen `Teknik Informatika`, sehingga nama tersebut muncul pada hasil.

## 7. Event Klik

**File:** [event.html](./event.html)

**Output awal di halaman:**

```text
[Tombol: Klik Saya]
```

**Output setelah tombol diklik:** Browser menampilkan kotak dialog dengan pesan:

```text
Halo! Kamu baru saja menekan tombol.
```

**Penjelasan:** Atribut `onclick` memanggil fungsi `sapa()` ketika tombol ditekan. Fungsi tersebut menggunakan `alert()` untuk menampilkan pesan dialog.

## 8. DOM (Document Object Model)

**File:** [dom.html](./dom.html)

**Output awal di halaman:**

```text
Teks awal
[Tombol: Ubah]
```

**Output setelah tombol diklik:**

```text
Teks sudah diubah!
[Tombol: Ubah]
```

**Penjelasan:** Fungsi `ubahTeks()` mencari elemen yang memiliki `id="teks"` menggunakan `document.getElementById()`, lalu mengganti isinya. Perubahan terjadi langsung pada halaman tanpa memuat ulang.

## 9. Input dari Pengguna

**File:** [inputpengguna.html](./inputpengguna.html)

**Contoh input:** `Budi`

**Output di halaman:**

```text
Selamat datang, Budi!
```

**Penjelasan:** `prompt()` meminta pengguna memasukkan nama. Nilai yang dimasukkan disimpan dalam variabel `nama`, kemudian digabungkan dengan teks sapaan. Output akan berubah sesuai nama yang dimasukkan.

## 10. Menghitung Luas Persegi Panjang

**File:** [persegipanjang.html](./persegipanjang.html)

**Contoh input:**

```text
Panjang: 10
Lebar: 5
```

**Output setelah tombol Hitung ditekan:**

```text
Luas = 50
```

**Penjelasan:** Program membaca nilai panjang dan lebar dari input, mengubahnya menjadi angka dengan `Number()`, lalu menghitung luas menggunakan rumus `panjang × lebar`. Dengan input 10 dan 5, luasnya adalah 50 satuan persegi.

## Kesimpulan

Sepuluh studi kasus ini memperkenalkan konsep dasar JavaScript: menampilkan teks, menyimpan data dalam variabel, melakukan operasi aritmatika, mengambil keputusan dengan percabangan, menjalankan perulangan, membuat fungsi, merespons event, mengubah elemen melalui DOM, menerima input pengguna, dan mengolah input untuk perhitungan. Hasil untuk contoh yang bersifat interaktif bergantung pada input atau aksi pengguna.
