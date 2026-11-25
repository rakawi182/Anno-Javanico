# Anno Javanico

Kalender Jawa (Aji Saka & Pawukon): konversi Masehi ↔ Jawa, Anggara Kasih, kalender bulanan, Pranata Mangsa, Palakrama, dan Petangan Pejah. Tersedia dalam tiga bahasa (Indonesia, Inggris, Krama Inggil). Satu halaman HTML, semua perhitungan berjalan di peramban, dan bisa dipasang sebagai aplikasi (PWA).

**Aplikasi:** https://rakawi182.github.io/Anno-Javanico/

## Memasang
- **Android / Chrome:** buka tautan di atas, lalu menu ⋮ → *Install app* / *Add to Home screen*.
- **iPhone / Safari:** tombol Bagikan → *Add to Home Screen*.
- **Desktop (Chrome/Edge):** ikon pasang di bilah alamat.

## Struktur
| Berkas | Fungsi |
|---|---|
| `index.html` | Aplikasi |
| `manifest.webmanifest` | Nama, ikon, warna, mode standalone |
| `sw.js` | Service worker (cache offline) |
| `favicon.svg`, `icons/` | Ikon aplikasi |
| `.nojekyll` | Menonaktifkan pemrosesan Jekyll di GitHub Pages |

## Memperbarui
Setelah mengubah `index.html`, naikkan `VERSION` di `sw.js` (mis. `anno-javanico-v2`) supaya pengguna mendapat versi baru.
