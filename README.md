**#🚀 Proyek Pemrograman Berorientasi Objek (PBO)**
Proyek ini dikembangkan untuk memenuhi tugas besar mata kuliah PBO dengan fokus pada penerapan struktur data, persistensi database, dan pola desain objek yang efisien.
---
**##📌 Deskripsi Proyek**
Aplikasi ini dibangun menggunakan bahasa Java dengan mengimplementasikan prinsip-prinsip utama OOP dan integrasi database untuk mengelola data secara dinamis.
---
**##🛠️ Stack Teknologi & Konsep Utama**
Proyek ini wajib mengimplementasikan komponen berikut:

Java Collections Framework (JCF): Digunakan untuk manajemen data di dalam memori (seperti List, Map, atau Set).

Inheritance (Pewarisan): Struktur kelas yang efisien menggunakan konsep parent dan child class untuk menghindari redundansi kode.

JDBC (Java Database Connectivity): Koneksi langsung ke database untuk operasi CRUD.

ORM dengan Data Mapper Pattern: Memisahkan logika bisnis (objek) dari logika database (SQL) sehingga kode lebih rapi dan mudah diuji.

```
**##📂 Struktur Folder (Rencana)**

Agar tim tidak bingung, berikut adalah usulan struktur paket (package):
src/
 ├── model/          # Berisi class utama (Plain Old Java Object)
 ├── mapper/         # Interface & Implementation Data Mapper (Logika SQL)
 ├── repository/     # Logika tambahan untuk akses data
 ├── util/           # Koneksi JDBC (DatabaseConnection.java)
 └── Main.java       # Titik masuk aplikasi
```
---
**##📝 Daftar Tugas (TODO List)**
```
🔴 Prioritas Utama: JDBC & ORM
Anggota tim yang memegang bagian ini bertanggung jawab untuk:

[1] Membuat kelas DatabaseConnection menggunakan Driver JDBC yang sesuai.

[2] Mendesain skema database (Tabel dan Relasi).

[3] Mengimplementasikan Data Mapper: Membuat class yang memetakan hasil query database menjadi objek Java.

[4] Memastikan tidak ada kode SQL yang bercampur di dalam kelas Model.

🟡 Implementasi Objek & JCF**

[1] Membuat hierarki kelas menggunakan Inheritance.

[2] Menggunakan JCF untuk menampung data sementara sebelum atau sesudah diambil dari database.

[3] Validasi data pada setiap fungsi input.

```
---
```
📅 Timeline & Deadline
Target Selesai: Week 15
```
---
Status Saat Ini: Perancangan Arsitektur & Database
```
---
```
🤝 Cara Berkontribusi (Workflow Tim)
Pull: Selalu lakukan git pull origin main sebelum mulai bekerja.

Branch: Kerjakan tugas di branch masing-masing (contoh: feature/jdbc-setup atau feature/model-design).

Commit: Gunakan pesan commit yang deskriptif.

Pull Request: Lakukan PR jika fitur sudah selesai dan mintalah minimal satu rekan tim untuk melakukan review kode.
