# Takar Ternak untuk Android

Proyek ini membungkus halaman Takar Ternak menjadi aplikasi Android dengan Capacitor 8. Seluruh isi aplikasi ada di dalam paket, jadi aplikasi jalan tanpa internet.

Mulai dari `docs/PANDUAN.md`. Di sana ada langkah dari membuka proyek sampai uji tertutup di Google Play.

## Isi paket

| Folder atau file | Isi |
|---|---|
| `www/` | Halaman aplikasi (`index.html`) dan huruf yang dibundel |
| `android/` | Proyek Android, dibuka dengan Android Studio |
| `assets/` | Gambar sumber ikon dan layar pembuka |
| `store/` | Ikon 512 px, feature graphic, dan tangkapan layar untuk halaman toko |
| `docs/` | Panduan, teks halaman toko, dan kebijakan privasi |
| `capacitor.config.json` | Nama aplikasi dan ID paket |

## Perintah singkat

```
npm install            # sekali saja, mengunduh Capacitor
npx cap sync android   # salin isi www/ ke proyek Android
npx cap open android   # buka di Android Studio
```

## Yang sudah diatur

- ID paket: `id.takarternak.app` (bisa diganti sebelum unggah pertama, lihat panduan)
- Versi: 1.0, kode versi 1
- Target Android 16 (API level 36), minimum Android 7.0 (API level 24)
- Aplikasi gratis, tanpa iklan, tanpa fitur pembayaran
