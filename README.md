# Pertemuan 15 praktikum13
## Nama : Sheila Antica Oktaviani
## Kelas: 312410002
## NIM : 312410002
## Mata Kuliah : Pemograman Web
# Tampilan Home
<img width="1913" height="952" alt="image" src="https://github.com/user-attachments/assets/e8c86b9a-8ece-403e-a113-d7435f845ef4" />
Aplikasi Database Barang Sederhana

# Deskripsi Aplikasi

Aplikasi Database Barang Sederhana adalah aplikasi berbasis web yang digunakan untuk mengelola data barang. Aplikasi ini dibuat menggunakan PHP dan MySQL serta dijalankan secara lokal menggunakan XAMPP.
Fungsi utama aplikasi ini adalah melakukan CRUD (Create, Read, Update, Delete) data barang.

# Tujuan Pembuatan

- Mempelajari koneksi database MySQL dengan PHP
- Menerapkan konsep CRUD
- Menampilkan data dalam bentuk tabel
- Mengelola data barang secara sederhana
- Fitur Aplikasi
## Aplikasi ini memiliki beberapa fitur utama, yaitu:
1. Menampilkan Data Barang
2. Menampilkan daftar barang dalam bentuk tabel yang berisi:
3. Gambar barang
4. Nama barang
5. Kategori
6. Harga jual
7. Harga beli
8. Stok
## Tambah Barang
Pengguna dapat menambahkan data barang baru melalui tombol Tambah Barang.
- Edit Barang
- Pengguna dapat mengubah data barang yang sudah ada melalui tombol Edit.
- Hapus Barang
- Pengguna dapat menghapus data barang melalui tombol Delete.
## Pencarian Data
Tersedia fitur Cari Data untuk mempermudah pencarian barang berdasarkan nama atau kategori.
Pagination
Digunakan untuk membagi data ke dalam beberapa halaman agar tampilan lebih rapi.
## Tampilan Halaman
Menu Navigasi: Home dan Login
Halaman Utama: Menampilkan daftar barang
Footer: Informasi copyright
## Struktur Database (Contoh)
Database terdiri dari tabel barang dengan field:
id_barang
nama_barang
kategori
harga_jual
harga_beli
stok
gambar
## Teknologi yang Digunakan
Bahasa Pemrograman: PHP
Database: MySQL
Web Server: Apache (XAMPP)
Frontend: HTML, CSS, Bootstrap

# Tampilan Jika Ingin Menambahkan Barang
<img width="1912" height="773" alt="image" src="https://github.com/user-attachments/assets/6f3c9c4e-6346-4e24-9e49-1c5ffc498738" />
Halaman Tambah Barang

# Deskripsi Halaman Tambah Barang
Halaman Tambah Barang digunakan untuk menambahkan data barang baru ke dalam database. Pada halaman ini, pengguna dapat mengisi informasi lengkap mengenai barang yang akan disimpan, termasuk gambar barang.
Halaman ini merupakan bagian dari proses Create (CRUD) dalam aplikasi Database Barang Sederhana.
## Form Input Data
Pada halaman ini terdapat beberapa field input, yaitu:
1. Nama Barang
Digunakan untuk memasukkan nama barang yang akan ditambahkan.
2. Kategori
Digunakan untuk menentukan kategori dari barang, misalnya elektronik, panahan, atau terbaru.
3. Harga Jual
Digunakan untuk memasukkan harga jual barang kepada pelanggan.
4. Harga Beli
Digunakan untuk memasukkan harga beli barang dari supplier.
5. Stok
Digunakan untuk memasukkan jumlah stok barang yang tersedia.
6. Gambar Barang
Digunakan untuk mengunggah gambar barang agar data lebih informatif dan menarik saat ditampilkan.
## Tombol Aksi
- Simpan
Berfungsi untuk menyimpan data barang yang telah diinput ke dalam database MySQL.
- Batal
Berfungsi untuk membatalkan proses penambahan data dan kembali ke halaman utama.
## Proses yang Terjadi
Pengguna mengisi seluruh data pada form tambah barang
Sistem memvalidasi data yang diinput
Data disimpan ke dalam tabel barang di database
Gambar barang diunggah dan disimpan ke folder tertentu
Setelah berhasil, pengguna diarahkan kembali ke halaman daftar barang

# Tampilan Jika ingin mencari barang
<img width="1915" height="723" alt="image" src="https://github.com/user-attachments/assets/be1ca214-ed23-48b8-9fc8-4fab73b89a3e" />

# Tampilan Saat ingin Edit barang
<img width="1909" height="781" alt="image" src="https://github.com/user-attachments/assets/6bd7559a-5440-4610-aa4a-a892aec587fc" />

