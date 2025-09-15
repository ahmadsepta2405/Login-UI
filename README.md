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

## 7. tampilan akhir
![WhatsApp Image 2025-09-15 at 19 44 34_2af7a2c0](https://github.com/user-attachments/assets/9a715bc0-804e-4af3-b347-8b38addabffd)
![WhatsApp Image 2025-09-15 at 19 39 47_c79e66da](https://github.com/user-attachments/assets/ff3800bf-3d67-457e-85b4-b1a6af7af788)
![WhatsApp Image 2025-09-15 at 19 40 48_bdf40778](https://github.com/user-attachments/assets/853688d9-d018-4508-aa36-0f28725cc39f)



