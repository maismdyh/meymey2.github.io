```markdown
# Management Perpustakaan - JavaFX

Aplikasi desktop sederhana untuk mengelola perpustakaan berbasis **JavaFX** dan menerapkan pola arsitektur **MVC (Model-View-Controller)**. Aplikasi ini memiliki tampilan user-friendly dan modular, serta cocok untuk latihan dasar Java OOP dan GUI.

---

## Fitur Aplikasi

- **Beranda (Home Page)**  
  Menampilkan tombol navigasi ke daftar buku & anggota, serta judul aplikasi.

- **Manajemen Buku**  
  Tampilkan daftar buku, ID, status peminjaman, serta tombol aksi:
  - Tambah buku  
  - Edit buku  
  - Hapus buku

- **Manajemen Anggota**  
  Menampilkan data anggota: ID, nama anggota, dan denda (opsional).

---

## Pembagian Tugas Kelompok

| No. | Nama Anggota       | Tugas                                                                                                                                     |
|-----|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| 1.  | **Hairi**          | - Mendesain tampilan **Home Page**<br>- Menambahkan tombol navigasi: "Daftar Buku" & "Daftar Anggota"<br>- Menampilkan teks **"Management Perpustakaan"** |
| 2.  | **Hilmy**          | - Mendesain tampilan **Daftar Buku**<br>- Menampilkan nama buku, ID buku, dan status peminjaman<br>- Menampilkan ID anggota peminjam<br>- Menambahkan tombol: Tambah, Edit, dan Hapus buku |
| 3.  | **Maisyah**        | - Mendesain tampilan **Daftar Anggota**<br>- Menampilkan ID anggota, nama anggota, dan denda (opsional) |

---

## 📂 Struktur Folder

```

Management-Perpustakaan/
├── app/
│   └── src/
│       └── main/
│           ├── java/
│           │   ├── management.perpustakaan/
│           │   │   ├── App.java
│           │   │   ├── HomeController.java
│           │   │   ├── BookController.java
│           │   │   ├── MemberController.java
│           │   │   └── services/ (opsional)
│           │   └── models/
│           │       ├── Book.java
│           │       ├── Member.java
│           │       ├── Library.java
│           │       └── LibraryItem.java
│           └── resources/
│               └── management.perpustakaan/
│                   ├── HomeView\.fxml
│                   ├── BookView\.fxml
│                   └── MemberView\.fxml

````

---

## Cara Menjalankan Aplikasi

1. **Clone/download** repositori.
2. Buka di **IDE (IntelliJ/NetBeans/Eclipse)** yang mendukung JavaFX.
3. Jalankan file `App.java`.

Jika menggunakan **Gradle**:

```bash
./gradlew run
````

---

## Keterangan

* **Prodi**: Sistem Informasi
* **Kelas**: (Isikan kelas kalian di sini)
* **Mata Kuliah**: Pemrograman Berorientasi Objek
* **Dosen Pengampu**: (Isikan nama dosen kalian)

---

## 🙌 Terima Kasih

Dikerjakan sebagai tugas kelompok oleh:
**Hairi**, **Hilmy**, dan **Maisyah**

````
