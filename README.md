# Distribusi Air Bersih PMI Sulawesi Selatan 2023–2024

Presentasi interaktif analisis distribusi air bersih oleh PMI untuk operasi kekeringan di Sulawesi Selatan, mencakup 7 kabupaten/kota dengan 1.012 titik distribusi dan 6,8 juta liter air.

## Stack

- **Reveal.js 4** — framework presentasi HTML
- **Leaflet.js** — peta interaktif bahaya kekeringan
- **Chart.js** — visualisasi data distribusi & armada
- **GeoJSON** — batas administrasi 24 kab/kota Sulsel
- **GitHub Pages** — hosting statis

## Struktur File

```
├── index.html                        ← Presentasi utama
├── README.md
├── assets/
│   ├── data/
│   │   ├── wilayah_terdampak_dan_berisiko.csv
│   │   ├── sumber_daya.csv
│   │   └── kekeringan_sulsel.md
│   ├── peta-analisis-kekeringan-sulsel.svg
│   └── templates/                   ← (untuk template pelaporan)
```

## Sumber Data

- Data distribusi air bersih dari Form Laporan Harian PMI Sulawesi Selatan (2023–2024)
- Data bahaya kekeringan dari Peta Skenario Bahaya Kekeringan Provinsi Sulsel
- GeoJSON batas administrasi dari [AlfianAliM/Indonesia-GeoJSON](https://github.com/AlfianAliM/Indonesia-GeoJSON)

## Penggunaan

Buka `https://[username].github.io/distribusi-air-bersih-sulsel/` di browser, atau jalankan lokal dengan:

```bash
npx serve .
```

## Catatan

- Bukan dokumen resmi PMI/IFRC
- Untuk tujuan pembelajaran dan dokumentasi internal
- Data kendaraan 2024 masih perlu dilengkapi
