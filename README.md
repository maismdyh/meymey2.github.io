# 📚 Management Perpustakaan

Aplikasi desktop untuk sistem manajemen perpustakaan yang dibangun menggunakan **JavaFX** dengan arsitektur **MVC (Model-View-Controller)**. Aplikasi ini menyediakan interface yang user-friendly untuk mengelola data buku dan anggota perpustakaan.

## ✨ Fitur Utama

### 🏠 Beranda (Home Page)
- Tampilan utama dengan navigasi ke fitur-fitur aplikasi
- Tombol akses ke "Daftar Buku" dan "Daftar Anggota"
- Header aplikasi "Management Perpustakaan"

### 📖 Manajemen Buku
- Tampilkan daftar lengkap koleksi buku
- Informasi detail: ID buku, nama buku, status peminjaman
- Tracking peminjam (ID anggota yang meminjam)
- Operasi CRUD: Tambah, Edit, dan Hapus buku

### 👥 Manajemen Anggota
- Daftar anggota perpustakaan
- Data anggota: ID anggota, nama lengkap
- Operasi CRUD: Tambah, Edit, dan Hapus anggota
- Tampilkan Riwayat Aktivitas anggota

## 🏗️ Struktur Proyek

```
Management-Perpustakaan/
├── app/
│   └── src/
│       └── main/
│           ├── java/
│           │   └── management.perpustakaan/
│           │       ├── App.java                 // Main Application
│           │       ├── HomeController.java      // Controller untuk Home
│           │       ├── BookController.java      // Controller untuk Buku
│           │       ├── MemberController.java    // Controller untuk Anggota
│           │       └── models/
│           │           ├── Book.java           // Model Buku
│           │           ├── Member.java         // Model Anggota
│           │           ├── Library.java        // Model Perpustakaan
│           │           └── LibraryItem.java    // Abstract Model Item
│           └── resources/
│               └── management.perpustakaan/
│                   ├── HomeView.fxml          // UI Home Page
│                   ├── BookView.fxml          // UI Manajemen Buku
│                   └── MemberView.fxml        // UI Manajemen Anggota
```

## 🛠️ Teknologi yang Digunakan

- **Java** - Bahasa pemrograman utama
- **JavaFX** - Framework untuk GUI desktop
- **FXML** - Markup untuk desain interface
- **Scene Builder** - Tool untuk mendesain FXML (opsional)

## ⚡ Cara Menjalankan

### Prasyarat
- Java Development Kit (JDK) 11 atau lebih baru
- JavaFX SDK (jika tidak included dalam JDK)
- IDE yang mendukung JavaFX (IntelliJ IDEA, Eclipse, NetBeans)

### Langkah Instalasi

1. **Clone atau download** repositori ini
```bash
git clone [repository-url]
cd Management-Perpustakaan
```

2. **Buka di IDE favorit Anda**

3. **Jalankan aplikasi**
```bash
java management.perpustakaan.App
```

Atau jika menggunakan Gradle:
```bash
./gradlew run
```

### Konfigurasi JavaFX (jika diperlukan)
Jika JavaFX tidak terdeteksi, tambahkan VM options:
```
--module-path /path/to/javafx/lib --add-modules javafx.controls,javafx.fxml
```

## 🏛️ Arsitektur Aplikasi

Aplikasi ini menggunakan pola **MVC (Model-View-Controller)**:

- **Model**: Mengelola data dan logika bisnis (`Book.java`, `Member.java`, `Library.java`)
- **View**: Interface pengguna yang didefinisikan dalam file FXML
- **Controller**: Menghubungkan Model dan View, menangani interaksi pengguna

## 👨‍💻 Tim Pengembang

| Nama | NIM | Kontribusi |
|------|-----|------------|
| **Hilmy Affayyad Akbar** | H071241013 | • Desain tampilan Daftar Buku<br>• Implementasi fitur CRUD buku<br>• Tracking status peminjaman |
| **Muhammad Hairi** | H071241055 | • Desain Home Page<br>• Navigasi antar halaman<br>• Layout aplikasi utama |
| **Maisyah Mahdiyyah** | H071241053 | • Desain tampilan Daftar Anggota<br>• Manajemen data anggota<br>• 

## 📋 Informasi Akademik

- **Program Studi**: Sistem Informasi
- **Fakultas**: Matematika & Ilmu Pengetahuan Alam (MIPA)
- **Mata Kuliah**: Pemrograman Berorientasi Objek
- **Dosen Pengampu**: [Nama Dosen]
- **Kelas**: A

## 📄 Lisensi

Proyek ini dibuat untuk keperluan akademik dan pembelajaran.

---
