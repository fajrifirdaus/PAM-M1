# Tugas 1: Pengenalan KMP & Setup Environment 🚀

![Kotlin](https://img.shields.io/badge/Kotlin-2.0-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Compose Multiplatform](https://img.shields.io/badge/Compose_Multiplatform-UI-4285F4?style=for-the-badge&logo=jetpack-compose&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Android_%7C_iOS_%7C_Desktop-success?style=for-the-badge)

Repository ini berisi hasil pengerjaan **Tugas Praktikum Minggu 1** untuk mata kuliah **Pengembangan Aplikasi Mobile (IF25-22017)** di Institut Teknologi Sumatera (ITERA). Proyek ini dibangun menggunakan **Kotlin Multiplatform (KMP)** dengan antarmuka **Compose Multiplatform**.

---

## 👤 Identitas Mahasiswa

| Informasi | Detail |
| :--- | :--- |
| **Nama** | **Muhammad Fajri Firdaus** |
| **NIM** | **123140050** |
| **Program Studi** | Teknik Informatika |
| **Instansi** | Institut Teknologi Sumatera (ITERA) |

---

## 📱 Hasil Aplikasi (Screenshot)

Berikut adalah tampilan aplikasi yang dijalankan pada **Android Emulator (API 36)**:

<p align="center">
  <img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/511bcfac-1d1f-4b3a-8e31-d8163b8006aa" />
</p>

> *Aplikasi menampilkan Logo ITERA (Vector), Identitas Mahasiswa, dan deteksi Platform secara dinamis.*

---

## 🛠️ Fitur & Modifikasi Kode

Sesuai instruksi tugas, berikut adalah modifikasi yang telah dilakukan pada template *Hello World* bawaan:

1.  **UI Modern dengan Material3**:
    * Menggunakan `Card` dengan elevasi dan sudut membulat (`RoundedCornerShape`).
    * Tata letak terpusat (*Central Alignment*) menggunakan `Box` dan `Column`.
2.  **Identitas Personal**:
    * Menampilkan Nama Lengkap dan NIM.
3.  **Logo Kustom (Vector XML)**:
    * Mengganti logo default Compose dengan **Logo ITERA**.
    * Logo dibuat ulang menggunakan format `.xml` (Vector Drawable) agar tajam dan tidak pecah.
4.  **Platform Detection**:
    * Menggunakan pola `expect`/`actual` untuk mendeteksi sistem operasi perangkat (Android/iOS/Desktop).
    * Fitur *Interactive Button* untuk menampilkan/menyembunyikan info platform.

---

## 🚀 Cara Menjalankan Project

Clone repository ini, lalu buka di **Android Studio**.

### Menjalankan di Android
Jalankan perintah berikut di terminal atau gunakan tombol **Run** di Android Studio:
```bash
./gradlew :composeApp:installDebug
