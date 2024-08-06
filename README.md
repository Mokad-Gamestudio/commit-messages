# Commit Message Guideline

Karena jumlah repository dan commit di Mokad Gamestudio akan terus bertambah, maka akan diterapkan suatu standarisasi commit message untuk memudahkan pengembangan di masa depan. Mulai 10 Agustus 2024, commit message yang tidak mengikuti standar dan bukan commit darurat akan ditolak.

## Aturan Umum Commit:

1. Setiap pesan commit harus terdiri dari tiga bagian utama:
    - **Tipe Commit**: Berisi deskripsi singkat yang **menggambarkan** isi dari commit.
      Format: `[Tipe] Deskripsi singkat`
  
    - **Deskripsi Lengkap *(opsional)***: 
      Deskripsi lebih mendetail tentang perubahan.
  
    - **Daftar Perubahan *(opsional)***: 
      Daftar detail perubahan yang dilakukan.

2. Pesan commit ditulis dengan huruf tidak kapital.

3. Pesan commit ditulis dalam bahasa Inggris.

## Tipe Commit:

Tipe commit digunakan untuk menjelaskan jenis perubahan yang dilakukan. Berikut adalah beberapa tipe yang umum digunakan:

- **feat**: Penambahan fitur baru
- **fix**: Perbaikan bug
- **docs**: Perubahan pada dokumentasi
- **style**: Perubahan yang tidak mempengaruhi logika program (misalnya, perbaikan format, penambahan spasi, dll.)
- **refactor**: Perubahan kode yang tidak memperbaiki bug atau menambahkan fitur
- **test**: Penambahan atau perbaikan tes
- **chore**: Perubahan pada tugas yang mendukung pengembangan (misalnya, pembaruan dependensi)

## Contoh Lengkap:
```
[feat] tambahkan halaman profil pengguna

menambahkan halaman profil pengguna dengan informasi dasar seperti nama, email, dan foto profil. halaman ini hanya dapat diakses oleh pengguna yang telah login.

- tambahkan rute baru untuk halaman profil di `routes.js`
- buat komponen `Profile` di `Profile.jsx`
- tambahkan tes untuk memastikan halaman hanya bisa diakses oleh pengguna yang login
```
