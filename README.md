# absensi-login-system

Proyek ini mengimplementasikan sistem login sederhana dengan fitur berikut:

- Halaman login (`login.html`) untuk pengguna memasukkan email dan kata sandi.
- Fitur "Remember Me" yang menyimpan email di `localStorage` untuk memudahkan login berikutnya.
- Halaman selamat datang (`welcome.html`) yang menyapa pengguna dengan nama mereka dan menyediakan tombol logout.

## Prasyarat

Untuk menjalankan aplikasi ini, Anda hanya membutuhkan browser modern yang mendukung JavaScript dan `localStorage`. Tidak diperlukan perangkat lunak tambahan atau pengaturan server.

## Cara Memulai

1. **Kloning atau Unduh Repository:**
   ```
   git clone <repository_url>
   cd <project_folder>
   ```

2. **Buka Aplikasi:**
   - Navigasikan ke folder tempat file berada.
   - Buka `login.html` di browser Anda.

## Petunjuk Penggunaan

### Halaman Login (`login.html`)
1. Masukkan kredensial berikut untuk login:
   - **Email:** `admin@gmail.com`
   - **Password:** `123456`
2. Centang kotak "Remember Me" jika Anda ingin email Anda disimpan untuk sesi berikutnya.
3. Klik tombol **Login**.
   - Jika kredensial benar, Anda akan diarahkan ke `welcome.html`.
   - Jika salah, pesan kesalahan akan ditampilkan.

### Halaman Selamat Datang (`welcome.html`)
- Halaman ini menampilkan sapaan personal berdasarkan email yang dimasukkan saat login.
- Klik tombol **Logout** untuk:
  - Menghapus data sesi yang tersimpan (jika ada).
  - Mengarahkan kembali ke `login.html`.

## Struktur File
```
.
├── login.html         # Halaman login dengan fitur Remember Me
├── welcome.html       # Halaman selamat datang dengan sapaan personal dan tombol logout
├── login.css          # File css untuk tampilan login
├── style.css          # File css untuk tampilan welcome
├── README.md          # File dokumentasi
```

## Catatan

- Pastikan file `login.html` dan `welcome.html` berada di direktori yang sama untuk memastikan pengalihan halaman berjalan dengan baik.
- Proyek ini tidak memiliki backend. Ini hanya merupakan demonstrasi antarmuka front-end.

## Kustomisasi

- Untuk mengubah kredensial default, ubah bagian berikut di `login.html`:
  ```javascript
  if (this.email === "admin@gmail.com" && this.password === "123456") {
  ```
- Anda juga dapat meningkatkan desain `login.html` dan `welcome.html` dengan memodifikasi CSS-nya.

## Dukungan

Jika Anda mengalami masalah atau memiliki saran untuk perbaikan, silakan hubungi pemilik repository atau ajukan issue.
