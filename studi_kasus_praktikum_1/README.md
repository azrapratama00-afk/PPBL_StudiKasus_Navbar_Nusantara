# studi_kasus_praktikum_1
# Nusantara Cerdas Mobile

**Nusantara Cerdas Mobile** adalah aplikasi mobile berbasis **Flutter** yang dirancang sebagai prototype layanan **Smart City**. Aplikasi menyediakan informasi mengenai pilar Smart City serta beberapa fitur layanan untuk warga.

## Fitur Utama

* **Beranda** — Menampilkan informasi 6 pilar Smart City.
* **Layanan** — Menampilkan daftar layanan kota.
* **Detail Layanan** — Menampilkan informasi detail dari layanan yang dipilih.
* **Warga** — Menyediakan halaman khusus untuk informasi warga.
* **Riwayat Laporan** — Menampilkan riwayat laporan warga.
* **Pengaturan Kota** — Menyediakan pengaturan terkait kota.
* **Tentang Aplikasi** — Menampilkan informasi aplikasi.
* **Route Tidak Dikenal** — Menangani route yang tidak tersedia.

## Teknologi

* **Flutter**
* **Dart**
* **Material Design**
* **Flutter Navigator / Named Routes**

## Struktur Folder

```text
lib/
├── main.dart
├── navigation/
│   ├── app_routes.dart
│   └── kerangka_navigasi.dart
└── pages/
    ├── beranda_page.dart
    ├── layanan_page.dart
    ├── detail_layanan_page.dart
    ├── warga_page.dart
    ├── riwayat_laporan_page.dart
    ├── pengaturan_kota_page.dart
    ├── tentang_aplikasi_page.dart
    └── route_tidak_dikenal_page.dart
```

### Penjelasan Singkat

* `main.dart` → Entry point aplikasi.
* `navigation/` → Mengatur routing dan kerangka navigasi.
* `pages/` → Berisi seluruh halaman aplikasi.

## Cara Menjalankan

Pastikan Flutter sudah terinstall, kemudian jalankan:

```bash
flutter pub get
flutter run
```

Untuk mengecek environment Flutter:

```bash
flutter doctor
```

## Alur Navigasi

```text
Beranda
├── Layanan
│   └── Detail Layanan
├── Warga
│   └── Riwayat Laporan
├── Pengaturan Kota
└── Tentang Aplikasi
```

## Pengembangan Selanjutnya

Project ini dapat dikembangkan lebih lanjut dengan menambahkan:

* Backend dan REST API
* Database
* Login dan registrasi
* Sistem laporan warga
* Notifikasi
* Data layanan secara real-time

## Status

Project ini merupakan **prototype aplikasi Smart City berbasis Flutter** untuk keperluan pembelajaran dan pengembangan aplikasi mobile.