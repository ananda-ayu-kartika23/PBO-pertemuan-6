# Tugas Pertemuan 6 — Penerapan JDialog pada Aplikasi CRUD Database  

Repository ini berisi implementasi aplikasi desktop sederhana menggunakan **Java Swing**, dengan penerapan **JDialog** untuk membuat form dialog interaktif pada operasi **CRUD (Create, Read, Update, Delete)** yang terhubung ke database.  

---

## 🎯 Tujuan  
- Memahami penggunaan **JDialog** sebagai dialog modal dan non-modal.  
- Menghubungkan aplikasi GUI dengan database.  
- Mengimplementasikan operasi CRUD melalui pop-up dialog.  
- Memberikan pengalaman pengguna (UX) yang lebih baik saat mengelola data.  

---

## 🧰 Teknologi yang Digunakan  
- **Java** (minimal versi 8 atau yang lebih baru)  
- **Swing** (GUI bawaan Java)  
- **JDBC Driver** (MySQL / SQLite / PostgreSQL)  
- (Opsional) Library tambahan untuk logging, validasi, atau koneksi database  

---

## 📌 Fitur Utama  

### Jendela Utama (Main Frame)  
- Menampilkan tabel data dari database (contoh: data penduduk, produk, siswa, dll).  
- Tombol aksi: **Tambah**, **Edit**, **Hapus**, **Refresh**.  

### Dialog Form (JDialog)  
- **Tambah Data** → Membuka dialog kosong untuk input baru.  
- **Edit Data** → Membuka dialog dengan data lama yang bisa diedit.  
- **Hapus Data** → Menampilkan dialog konfirmasi sebelum menghapus data.  
- **Lihat Detail** (opsional) → Menampilkan data lengkap secara read-only.  

### Validasi Input  
- Cek field kosong, panjang karakter, serta format data sebelum eksekusi query.  

### Koneksi Database  
- Terdapat kelas khusus untuk manajemen koneksi database.  
- Query CRUD dijalankan menggunakan **PreparedStatement** untuk keamanan.  

---

## 🚀 Cara Menjalankan Aplikasi  
1. Buat database sesuai kebutuhan (contoh: MySQL dengan tabel `penduduk`).  
2. Atur konfigurasi database (URL, username, password) di kelas koneksi.  
3. Jalankan aplikasi dari kelas utama (misalnya `Main.java`).  
4. Gunakan tombol **Tambah**, **Edit**, **Hapus**, atau **Refresh** untuk mengelola data.  

---
