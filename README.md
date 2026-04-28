🚀 Proyek Pemrograman Berorientasi Objek (PBO)
Proyek ini dikembangkan untuk memenuhi tugas besar mata kuliah PBO dengan fokus pada penerapan struktur data, persistensi database, dan pola desain objek yang efisien.

📌 Deskripsi Proyek
Aplikasi ini dibangun menggunakan bahasa Java dengan mengimplementasikan prinsip-prinsip utama OOP dan integrasi database untuk mengelola data secara dinamis.

🛠️ Stack Teknologi & Konsep Utama
Proyek ini wajib mengimplementasikan komponen berikut:

Java Collections Framework (JCF): Digunakan untuk manajemen data di dalam memori (seperti List, Map, atau Set).

Inheritance (Pewarisan): Struktur kelas yang efisien menggunakan konsep parent dan child class untuk menghindari redundansi kode.

JDBC (Java Database Connectivity): Koneksi langsung ke database untuk operasi CRUD.

ORM dengan Data Mapper Pattern: Memisahkan logika bisnis (objek) dari logika database (SQL) sehingga kode lebih rapi dan mudah diuji.

📂 Struktur Folder (Rencana)
```
Agar tim tidak bingung, berikut adalah usulan struktur paket (package):
src/
 ├── model/          # Berisi class utama (Plain Old Java Object)
 ├── mapper/         # Interface & Implementation Data Mapper (Logika SQL)
 ├── repository/     # Logika tambahan untuk akses data
 ├── util/           # Koneksi JDBC (DatabaseConnection.java)
 └── Main.java       # Titik masuk aplikasi
