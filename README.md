# 🗺️ Peta Topikal Interaktif

Repo ini adalah template sederhana untuk membuat **peta interaktif berbasis Leaflet** yang membaca data dari **file CSV**.  
Cukup update `data.csv`, maka peta otomatis menampilkan lokasi baru tanpa perlu mengubah kode.

---

## 🚀 Fitur
- Peta interaktif menggunakan [Leaflet](https://leafletjs.com/).
- Data lokasi diambil dari file `data.csv`.
- Marker dikelompokkan berdasarkan **Kategori**.
- Tersedia menu kontrol layer (hidup/matikan kategori).
- Popup pada marker menampilkan **Nama** + **Kategori**.

---

## 📂 Struktur Folder
```
peta-topik/
│── index.html     # Halaman utama peta
│── style.css      # Styling peta
│── data.csv       # Data input (update sesuai kebutuhan)
│── README.md      # Dokumentasi repo
```

---

## 📝 Format Data CSV
Gunakan format seperti berikut:

```csv
Nama,Kategori,Latitude,Longitude
Monas,Rekreasi,-6.175392,106.827153
RS Cipto Mangunkusumo,Kesehatan,-6.201,106.845
UI Depok,Pendidikan,-6.362,106.823
Masjid Istiqlal,Religi,-6.170,106.830
Taman Mini,Rekreasi,-6.302,106.895
```

📌 Kolom wajib:
- **Nama** → nama lokasi  
- **Kategori** → jenis/topik lokasi (misal: Rekreasi, Kesehatan, Pendidikan, Religi, dll.)  
- **Latitude** & **Longitude** → koordinat lokasi  

---

## 🌍 Cara Menjalankan di GitHub Pages
1. Fork atau clone repo ini.  
2. Upload data Anda ke `data.csv`.  
3. Commit & push ke branch `main`.  
4. Aktifkan **GitHub Pages** di repo:  
   - Settings → Pages → pilih `Branch: main` dan folder `/root`.  
5. Akses peta melalui URL GitHub Pages, misalnya:  
   ```
   https://username.github.io/peta-topik/
   ```

---

## 🛠️ Customisasi
- Ganti **basemap** dengan opsi lain dari Leaflet (misalnya: `Stamen`, `Carto`, dll.).  
- Tambahkan kolom lain di CSV (misalnya `Deskripsi`) lalu modifikasi popup di `index.html`.  

---

## 📜 Lisensi
MIT License – bebas digunakan, dimodifikasi, dan dikembangkan.
