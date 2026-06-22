# MoneyTrack - Smart Personal Finance Manager

MoneyTrack adalah aplikasi manajemen keuangan pribadi berbasis Android Native (Java & XML) yang dikembangkan sebagai proyek tugas akhir (UAS) mata kuliah Pemrograman Mobile 2. Aplikasi ini berfokus pada integrasi fitur keamanan biometrik, otomatisasi input data keuangan berbasis kecerdasan buatan sederhana (Rule-Based), dan visualisasi data yang dinamis.

##  Fitur Utama (Semester 4 Upgrade)
1. **Biometric Security:** Mengamankan data keuangan pengguna menggunakan enkripsi sidik jari (Fingerprint) atau PIN bawaan perangkat.
2. **Location-Aware UI:** Secara otomatis menyesuaikan bahasa tampilan aplikasi (Indonesia/Inggris) berdasarkan deteksi lokasi GPS pengguna secara real-time.
3. **AI Category Predictor:** Sistem pintar menggunakan *TextWatcher* untuk mendeteksi ketikan pengguna secara real-time dan memprediksi serta memilih kategori transaksi (Pemasukan/Pengeluaran) secara otomatis.
4. **AI Smart Auto-Correct:** Fitur pembersihan data otomatis yang mendeteksi singkatan atau typo (contoh: mengubah otomatis kata 'mkn' menjadi 'Makan') demi menjaga integritas dan kerapian database laporan.
5. **Dynamic Financial Analytics:** Visualisasi data pengeluaran dan pemasukan menggunakan grafik interaktif (BarChart) berbasis library **MPAndroidChart** yang diproses secara dinamis lewat kode Java dan didesain menggunakan XML.

---

##  Antarmuka Pengguna (User Interface)

> *Mohon maaf pak apabila foto kurang lengkap.*

### 1. Splash Screen
Halaman awal pemuatan aplikasi yang bersih dengan logo identitas MoneyTrack.
[Splash Screen](<img width="610" height="1356" alt="image" src="https://github.com/user-attachments/assets/f33e404f-109f-41ff-b14b-a775c02849e8" />

### 2. Security Screen (Biometric/PIN)
Halaman gerbang keamanan sebelum masuk ke aplikasi untuk memvalidasi sidik jari atau PIN user.
![Security Screen](https://via.placeholder.com/200x400.png?text=Security+Screen)

### 3. Dashboard Analytics
Halaman utama yang menampilkan ringkasan saldo, sisa budget, dan grafik visualisasi transaksi (MPAndroidChart).
![Dashboard](https://via.placeholder.com/200x400.png?text=Dashboard+UI)

### 4. Form Add Transaction
Formulir input transaksi yang sudah dilengkapi dengan fitur *AI Category Predictor* dan *Smart Auto-Correct*.
![Add Transaction](https://via.placeholder.com/200x400.png?text=Add+Transaction+UI)

---

##  Teknologi & Library Pendukung
* **Language:** Java (Logika Bisnis & Rendering Data) & XML (Desain Komponen Layout)
* **IDE:** Android Studio
* **Local Storage:** SharedPreferences (Arsitektur Modular)
* **Libraries:** 
  * `MPAndroidChart` (Untuk visualisasi grafik keuangan)
  * `AndroidX Biometric` (Untuk sistem keamanan sidik jari)

---

## Manajemen Proyek (SCRUM)
Pengembangan aplikasi ini terdokumentasi dan dimanajemen menggunakan metodologi SCRUM pada platform **ClickUp**[cite: 1]. Seluruh pembagian tugas, timeline pengerjaan sprint, hingga pelacakan bug tertera pada tautan ClickUp yang dilampirkan pada sistem akademik[cite: 1].# TUGAS-UAS-PEMOGRAMAN-MOBILE-SEMESTER-4
