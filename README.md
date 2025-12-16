# Traveling Salesman Problem (TSP) using BFS & DFS  
📍 Studi Kasus: Kota-Kota di Jawa Timur

Proyek ini merupakan implementasi dan analisis **algoritma Breadth-First Search (BFS)** dan **Depth-First Search (DFS)** dalam menyelesaikan **Traveling Salesman Problem (TSP)** dengan studi kasus jarak antar kota di Provinsi Jawa Timur.

## 📌 Latar Belakang
Traveling Salesman Problem (TSP) adalah permasalahan optimasi klasik untuk mencari rute terpendek yang mengunjungi setiap kota tepat satu kali dan kembali ke kota asal. Permasalahan ini banyak digunakan dalam bidang logistik, transportasi, dan perencanaan rute.  
Pada proyek ini, algoritma BFS dan DFS digunakan untuk menganalisis perbedaan performa dari sisi **jarak tempuh, waktu eksekusi, dan penggunaan memori**.

## 🎯 Tujuan
- Mengimplementasikan algoritma **BFS** dan **DFS** untuk menyelesaikan TSP
- Menganalisis efisiensi dan karakteristik masing-masing algoritma
- Membandingkan performa BFS dan DFS dalam konteks optimasi rute

## 📊 Dataset
- Sumber: **Badan Pusat Statistik (BPS) Provinsi Jawa Timur**
- Data: Jarak antar kota/kabupaten di Jawa Timur
- Batasan: Maksimal **10 kota** untuk menjaga efisiensi komputasi

## ⚙️ Metodologi
1. **Pre-processing Data**
   - Pembersihan missing value
   - Normalisasi format data
   - Konversi ke graf berbobot
2. **Perancangan Algoritma**
   - Breadth-First Search (BFS)
   - Depth-First Search (DFS)
3. **Implementasi**
   - Bahasa pemrograman: Python
   - Visualisasi rute menggunakan peta
   - Deployment sederhana menggunakan **Streamlit**
4. **Evaluasi**
   - Total jarak tempuh
   - Waktu eksekusi
   - Penggunaan memori
   - Jumlah operasi

## 🧪 Hasil Singkat
- **BFS**
  - Waktu eksekusi sangat cepat
  - Penggunaan memori lebih besar
  - Jarak tempuh cenderung lebih panjang (tidak optimal)
- **DFS**
  - Jarak tempuh lebih pendek
  - Waktu eksekusi lebih lama
  - Penggunaan memori lebih efisien

➡️ **DFS unggul dalam menemukan rute lebih pendek**, sedangkan **BFS unggul dalam kecepatan eksekusi**.

## 🛠️ Tools & Teknologi
- Python
- Pandas & NumPy
- Streamlit
- Graph & Map Visualization

