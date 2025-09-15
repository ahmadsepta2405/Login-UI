## 1. Membuat Struktur File

- Buat file `login_page.dart` di dalam folder `lib`.
- Import package yang diperlukan seperti `flutter/material.dart` dan `shared_preferences` untuk penyimpanan status login.

## 2. Membuat Form Login

- Tambahkan widget `TextField` untuk input email dan password.
- Tambahkan ikon pada setiap field agar tampilan lebih menarik.
- Gunakan properti `obscureText` pada field password untuk menyembunyikan karakter.

## 3. Validasi Input

- Pastikan email dan password tidak kosong.
- Validasi format email agar mengandung karakter `@`.
- Validasi panjang password minimal 6 karakter.

## 4. Proses Autentikasi

- Cek data user pada file `user_data.dart` (dummy data).
- Jika data sesuai, simpan status login menggunakan `shared_preferences`.
- Jika gagal, tampilkan dialog error.

## 5. Navigasi Setelah Login

- Jika login berhasil, arahkan pengguna ke halaman utama (`home_page.dart`).
- Jika login gagal, tampilkan pesan kesalahan.

## 6. Fitur Tambahan

- Tambahkan tombol untuk navigasi ke halaman registrasi (`register_page.dart`).
- Gunakan widget `Hero` untuk animasi ikon login.

Untuk menjalankan aplikasi:
flutter run
