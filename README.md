# praktikum6

# Program Input Nilai 

# Mahasiswa 

program sederhana untuk mengelole

data nilai maha siswa menggunakan

python dengan struktur data dictonary

# Flow chart 

![image](https://github.com/user-attachments/assets/66cbc86c-0771-45dd-a1d4-53b9344de9f3)

# Demo program

![image](https://github.com/user-attachments/assets/3477028a-fb72-488e-ac2f-01e6d705c4f4)

fitur lihat

![image](https://github.com/user-attachments/assets/6a24415a-8a36-47b8-9008-7a473a8b8b0f)

Untuk Fitur lainnya bisa dicoba sendiri

# Deskripsi program 

Program ini merupakan implementasi sistem manajemen data nilai mahasiswa dengan fitur CRUD (Create, Read, Update, Delete) menggunakan bahasa pemrograman Python.

Program menyimpan data dalam bentuk dictionary dengan NIM sebagai key dan data mahasiswa sebagai value.

# fitur program 

Lihat Data (L)

Menampilkan daftar nilai seluruh mahasiswa

Format tampilan menggunakan tabel dengan header yang jelas

Menampilkan "TIDAK ADA DATA" jika belum ada data yang tersimpan

Tambah Data (T)

Input data mahasiswa baru (NIM, Nama, Nilai Tugas, UTS, UAS)

Perhitungan nilai akhir otomatis dengan bobot:

Tugas: 30%

UTS: 35%

UAS: 35%

Data langsung ditampilkan setelah penambahan

Ubah Data (U)

Mencari data berdasarkan NIM

Memungkinkan perubahan semua komponen data

Menampilkan pesan error jika NIM tidak ditemukan

Data langsung diperbarui setelah perubahan

Hapus Data (H)

Menghapus data berdasarkan NIM

Konfirmasi penghapusan data

Menampilkan pesan error jika NIM tidak ditemukan

Cari Data (C)

Mencari dan menampilkan data berdasarkan NIM

Menampilkan detail lengkap data mahasiswa

Menampilkan pesan error jika NIM tidak ditemukan

# struktur program

# class data nilai 

         class Datanilai:
            def__init__(self):
                self.data = {} # Dictionary untuk menyimpan data


# metode - metode dalam class : 

       tampilkan_menu()

 program

 format :[(l)ihat,(T)ambah,

  (U)bah, (H)apus, (C)ari (K)eluar]

        tampilkan_daftar()

Menampilkan data dalam format tabel

Menggunakan string formatting untuk alignment

Menghitung nilai akhir otomatis

      tambah_data()

Input dan validasi data baru

Menyimpan data ke dictionary

Menampilkan data setelah penambahan

      ubah data()

Mencari data berdasarkan NIM

Input data baru

Update dictionary

Menampilkan data setelah perubahan

      hapus_data()

Mencari dan menghapus data berdasarkan NIM

Konfirmasi penghapusan

Menampilkan data setelah penghapusan

      cari_data()

Mencari dan menampilkan detail data

Format tampilan yang rapi

# cara penggunaan 

1. jalankan program dengan perintah:

           python program_nilai.py

2. pilih menu dengan memasukkan

   harus sesuai pilihan :

  
L: Lihat data

T: Tambah data

U: Ubah data

H: Hapus data

C: Cari data

K: Keluar program

3.ikuti intruksi yang mucul untuk

  setiap operasi 

# Alogaritma program

Loop Utama Program

Terima input pilihan menu

Jalankan metode sesuai pilihan

Ulangi sampai pilihan 'K' (Keluar)

Pengelolaan Data

Data disimpan dalam dictionary

NIM sebagai key

Data mahasiswa sebagai value dalam bentuk dictionary

Perhitungan Nilai

Nilai Akhir = (Tugas * 30%) + (UTS * 35%) + (UAS * 35%)

Hasil ditampilkan dengan 2 desimal

# persyaratan sistem 

Python 3.x

Tidak memerlukan library eksternal

# Kontribusi 

Silakan berkontribusi dengan cara:

Fork repository

Buat branch baru

Commit perubahan

Push ke branch

Buat Pull Request

# lisensi 

Program ini dibuat untuk tujuan pembelajaran dan bebas digunakan sesuai kebutuhan.














