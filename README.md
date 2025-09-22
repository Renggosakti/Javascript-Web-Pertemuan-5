# Javascript-Web-Pertemuan-5
# 🌐 Aplikasi Web Interaktif: Registrasi Mahasiswa, Pencarian Kode Pos, dan Dropdown Produk  

**Nama:** Arya Rangga Putra Pratama  
**NRP:** 5025241072  
**Kelas:** Pemrograman Web A  
**Dosen Pengampu:** Bapak Fajar Baskoro, S.Kom., M.T.  

---

## 📌 Pendahuluan
Proyek ini dibuat sebagai bagian dari mata kuliah **Pemrograman Web (PWEB)**.  
Aplikasi berbasis **HTML, CSS, dan JavaScript murni** ini memiliki tampilan modern dengan nuansa futuristik (gradient background, animasi transisi, dan card interaktif).  

Fitur utama yang dikembangkan adalah:  
1. **Login dengan validasi email**  
2. **Form Registrasi Mahasiswa** (dengan autosuggest nama dan dropdown dinamis)  
3. **Pencarian Kode Pos Indonesia** (berbasis provinsi, kabupaten/kota, dan kecamatan)  
4. **Dropdown Produk Dinamis** (pilih jenis produk → muncul daftar merek)  
5. **Halaman Akhir** (ucapan terima kasih + reset ke login)  

Data disimpan menggunakan **localStorage**, sehingga meskipun halaman direfresh, pengguna bisa melanjutkan dari halaman terakhir.

---

## 🚀 Fitur Utama

### 🔑 Login
- Validasi email (wajib ada `@`).  
- Jika email valid → simpan ke `localStorage` dan masuk ke halaman registrasi.  
- Jika salah → muncul pesan error.  

### 📝 Form Registrasi Mahasiswa
- Input **nama mahasiswa** (dengan autosuggest).  
- Input **NRP**.  
- Dropdown **mata kuliah → menyesuaikan daftar kelas & dosen**.  
- Dropdown tambahan: **jenis kelamin** dan **tahun ajaran**.  
- Data tersimpan ke `localStorage`.

### 📮 Pencarian Kode Pos
- Input bertingkat: **Provinsi → Kabupaten/Kota → Kecamatan**.  
- Menampilkan **kode pos dan informasi daerah**.  
- Setelah hasil muncul, sistem menunggu **4 detik** sebelum otomatis lanjut ke halaman produk.  

### 🛒 Dropdown Produk Dinamis
- Pilih jenis produk: **Laptop, HP, atau TV**.  
- Dropdown merek menyesuaikan produk yang dipilih.  
- Pilihan disimpan di `localStorage`.

### ✅ Halaman Akhir
- Menampilkan ucapan terima kasih.  
- Terdapat tombol reset → membersihkan data di `localStorage` dan kembali ke login.  

---

Tampilan aplikasi:

- Halaman Login  
- Form Registrasi Mahasiswa  
- Pencarian Kode Pos  
- Dropdown Produk Dinamis  
- Halaman Akhir

## 📂 Struktur File
index.html # Halaman utama (gabungan semua fitur)
style.css # (opsional, bisa inline di index.html)
script.js # Logika aplikasi (bisa juga inline)

## 🏁 Kesimpulan
Melalui proyek ini, saya belajar menghubungkan beberapa fitur interaktif berbasis **HTML, CSS, dan JavaScript** dengan penyimpanan sederhana di **localStorage**.  
Aplikasi ini melatih saya dalam:
- Validasi input,
- Dropdown dinamis,
- Manajemen alur multi-page tanpa reload,
- Desain web modern yang interaktif.  

---

## 📂 Str
