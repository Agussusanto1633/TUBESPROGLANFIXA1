# **Rumah Sakit Management System**

Aplikasi ini merupakan sistem manajemen rumah sakit berbasis JavaFX, dirancang untuk membantu administrasi rumah sakit dalam mengelola data pasien, obat, dan pengambilan obat.

## **Fitur Utama**
- **Login Admin**: Akses menu admin untuk mengelola data pasien dan obat.
- **Login Pasien**: Akses menu pasien untuk pengambilan obat.
- **Manajemen Data**: Menambahkan, melihat, dan mengelola data pasien dan obat.

## **Prasyarat**
Pastikan Anda telah memenuhi persyaratan berikut sebelum menjalankan aplikasi:

1. **Java Development Kit (JDK)**
    - Pastikan JDK versi 8 atau lebih baru telah terinstal di komputer Anda.

2. **JavaFX**
    - Pastikan library JavaFX telah diinstal dan dikonfigurasi dengan benar di sistem Anda.

3. **Integrated Development Environment (IDE)**
    - Gunakan IDE seperti IntelliJ IDEA, Eclipse, atau NetBeans yang mendukung JavaFX.

4. **File Gambar**
    - Pastikan file gambar yang digunakan dalam aplikasi tersedia di lokasi yang ditentukan (lihat jalur file pada kode). Contohnya:
        - `file:C:\\Users\\MSI GSAMING\\OneDrive\\Gambar\\Saved Pictures\\5101.jpg_wh860.jpg`


Berikut adalah struktur proyek:
# Struktur Proyek
Berikut adalah struktur proyek:
Dokumen ini menjelaskan struktur proyek, termasuk tujuan dari setiap file dan direktori.

## Struktur Direktori

```
src/
  tugasbesar/
    LoginAdmin.java
    LoginPasien.java
    Admin/
      MenuAdmin.java
      ListPasien.java
      ListObat.java
      ObatAdd.java
      PasienAdd.java
    Pasien/
      MenuPasien.java
      PengambilanObat.java
      Pengembalian.java
```

## Deskripsi File

### Level Root (`tugasbesar`)
- **LoginAdmin.java**: Mengelola fungsi login untuk administrator.
- **LoginPasien.java**: Mengelola fungsi login untuk pasien.

### Modul Admin (`tugasbesar/Admin/`)
- **MenuAdmin.java**: Menyediakan antarmuka menu utama untuk administrator.
- **ListPasien.java**: Menampilkan daftar pasien yang terdaftar.
- **ListObat.java**: Menampilkan daftar obat yang tersedia.
- **ObatAdd.java**: Memungkinkan administrator untuk menambahkan data obat baru.
- **PasienAdd.java**: Memungkinkan administrator untuk menambahkan data pasien baru.

### Modul Pasien (`tugasbesar/Pasien/`)
- **MenuPasien.java**: Menyediakan antarmuka menu utama untuk pasien.
- **PengambilanObat.java**: Mengelola proses pengambilan obat oleh pasien.
- **Pengembalian.java**: Mengelola proses pengembalian item yang dipinjam (jika berlaku).

## Catatan
- Proyek ini disusun untuk memisahkan fungsionalitas yang terkait dengan administrator dan pasien ke dalam modul yang terdedikasi untuk kejelasan dan kemudahan pemeliharaan.
- Semua file sumber dikelompokkan dalam direktori `src/`.














## **Langkah-langkah Menjalankan Aplikasi**

1. **Clone atau Unduh Proyek**
    - Clone repository atau unduh file proyek ke komputer Anda.

2. **Buka Proyek di IDE**
    - Import folder proyek ke IDE Anda.

3. **Konfigurasi JavaFX**
    - Pastikan library JavaFX sudah ditambahkan ke classpath proyek.

4. **Jalankan Aplikasi**
    - Pilih file utama untuk dijalankan (contoh: `LoginAdmin.java`).
    - Klik kanan pada file dan pilih opsi `Run`.

5. **Login ke Sistem**
    - **Admin**: Gunakan kredensial berikut:
        - Username: `rumahsakit@gmail.com`
        - Password: `12345`
    - **Pasien**: Tambahkan pasien melalui menu admin terlebih dahulu.

## **Troubleshooting**

Jika Anda mengalami masalah saat menjalankan aplikasi, periksa langkah-langkah berikut:

- **Gambar Tidak Muncul**:
  Pastikan file gambar tersedia di jalur yang benar seperti yang disebutkan di kode.

- **Library Tidak Ditemukan**:
  Tambahkan library JavaFX ke classpath IDE Anda.

- **Aplikasi Tidak Berjalan**:
  Periksa error log di IDE Anda untuk mengetahui penyebabnya.

## **Kontribusi**
Kontribusi untuk proyek ini dipersilakan. Silakan lakukan fork pada repository dan ajukan pull request untuk perubahan yang diusulkan.

## **Lisensi**
Proyek ini dilisensikan di bawah [MIT License](LICENSE).
