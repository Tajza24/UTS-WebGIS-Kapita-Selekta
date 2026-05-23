# 🌊 Peta Kerawanan Banjir Kota Bekasi

> WebGIS interaktif untuk visualisasi dan analisis kawasan rawan banjir di Kota Bekasi, Jawa Barat.

---

## 🗺️ Informasi Proyek

| | |
|---|---|
| **Wilayah** | Kota Bekasi, Jawa Barat, Indonesia |
| **Tema** | Kerawanan Banjir |
| **Mata Kuliah** | Kapita Selekta Sistem Informasi (SIF610) |
| **Institusi** | Universitas Bakrie |
| **Tahun** | 2026 |

---

## 📋 Deskripsi

WebGIS ini menampilkan peta kerawanan banjir Kota Bekasi berdasarkan jarak terhadap jaringan sungai. Wilayah diklasifikasikan menjadi 5 kelas kerawanan — dari Sangat Tinggi hingga Sangat Rendah — dan dilengkapi dengan sebaran fasilitas publik (sekolah dan rumah sakit) serta jaringan sungai yang ada di Kota Bekasi.

---

## 🧩 Layer Data

| Layer | Tipe | Sumber |
|-------|------|--------|
| Badan Air | Point | HOT OSM Export Tool |
| Sekolah | Point | HOT OSM Export Tool |
| Rumah Sakit | Point | HOT OSM Export Tool |
| Batas Kecamatan | Polygon | GADM v4.1 |

---

## 🎯 Klasifikasi Kerawanan Banjir

| Kelas | Jarak dari Sungai | Warna |
|-------|------------------|-------|
| Sangat Tinggi | 0 – 100 meter | 🔴 Merah |
| Tinggi | 100 – 300 meter | 🟠 Oranye |
| Sedang | 300 – 500 meter | 🟡 Kuning |
| Rendah | 500 – 1.000 meter | 🟢 Hijau |

---

## ⚙️ Teknologi

- **Frontend:** HTML, CSS, JavaScript
- **Peta Interaktif:** [Leaflet.js](https://leafletjs.com/)
- **Basemap:** OpenStreetMap
- **Data Format:** GeoJSON
- **Source Data:** [HOT OSM Export Tool](https://export.hotosm.org), [GADM v4.1](https://gadm.org)
- **Version Control:** GitHub
- **Deployment:** [Vercel](https://vercel.com)

---

## 🚀 Fitur WebGIS

- 🔍 Zoom & pan interaktif
- 🗂️ Layer toggle (nyala/matikan layer)
- 💬 Popup informasi saat objek diklik (nama, kategori, kecamatan)
- 🗺️ Basemap OpenStreetMap
- 📊 Legenda interaktif

---

## 🌐 Demo

🔗 **URL WebGIS:** `https://nama-proyek.vercel.app`  

---

## 📂 Struktur Folder

```
📁 webgis-kerawanan-banjir-bekasi/
├── 📄 index.html
├── 📁 data/
│   ├── clipping_boundary.geojson
│   ├── WEB_GIS_2.geojson
├── 📁 css/
│   └── style.css
├── 📁 js/
│   └── main.js
└── 📄 README.md
```

---

## 👤 Pembuat

| | |
|---|---|
| **Nama** | [Raditya Tajza Indrasyah] |
| **NIM** | [1242002081] |
| **Kelas** | [SIF 61] |
| **Email** | [tajza24@gmail.com] |

---

## 📄 Sumber Data

- OpenStreetMap contributors via [HOT Export Tool](https://export.hotosm.org) — ODbL License
- GADM v4.1 — [gadm.org](https://gadm.org)
