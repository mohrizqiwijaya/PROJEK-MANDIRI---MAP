# 📍 Sebaran Sekolah Dasar di Daerah Cisaat

## 📝 Informasi Proyek
- **Mata Kuliah** : Sistem Informasi Geografis  
- **Nama**       : R. Tb. Moh. Rizqi Wijaya  
- **Judul**      : Sebaran Sekolah Dasar di Daerah Cisaat  

---

## 📖 Deskripsi
Proyek ini bertujuan untuk menganalisis dan memvisualisasikan **sebaran sekolah dasar** di Kecamatan Cisaat, Sukabumi menggunakan **Sistem Informasi Geografis (SIG)**.  
Dengan analisis spasial, proyek ini diharapkan membantu memberikan gambaran mengenai distribusi sekolah dasar serta keterjangkauannya bagi masyarakat sekitar.

---

## 🎯 Tujuan
- Menampilkan peta sebaran sekolah dasar di Kecamatan Cisaat.  
- Membandingkan tampilan peta pada dua sistem koordinat:  
  - 🌍 **Web Mercator (EPSG:3857)**  
  - 🗺️ **WGS84 (EPSG:4326)**  
- Menambahkan data GeoJSON sebagai contoh titik lokasi sekolah dasar.  

---

## 🗂️ Data yang Digunakan
- 🗺️ Shapefile batas administrasi Kecamatan Cisaat.  
- 📍 Data titik lokasi sekolah dasar (koordinat/GeoJSON).  
- 👨‍👩‍👧‍👦 (Opsional) Data kependudukan atau peta kepadatan penduduk.  

---

## 🛠️ Tools & Teknologi
- **QGIS** / **ArcGIS** → pengolahan data spasial  
- **Leaflet.js** / **Mapbox** → visualisasi peta berbasis web  
- **GeoJSON** → penyimpanan titik lokasi sekolah dasar  

---

## 📷 Hasil
1. Peta dalam proyeksi **Web Mercator (EPSG:3857)**  
2. Peta dalam proyeksi **WGS84 (EPSG:4326)**  
3. Screenshot sebaran sekolah dasar  

---

## ✍️ Kesimpulan
- Peta **Web Mercator** mengalami sedikit distorsi terutama di wilayah kutub, sedangkan **EPSG:4326** lebih proporsional sesuai koordinat geografis.  
- **Web Mercator** lebih sering digunakan untuk peta berbasis web karena mendukung tile map global (Google Maps, OpenStreetMap).  

---
