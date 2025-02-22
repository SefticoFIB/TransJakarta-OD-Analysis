# 🚍 TransJakarta OD Analysis - Traffic Insights from Kaggle Dataset  

## 📌 Overview  
Repository ini berisi analisis data perjalanan penumpang TransJakarta menggunakan **Origin-Destination (OD) Analysis**. Studi ini bertujuan untuk memahami pola perjalanan, mengidentifikasi rute dengan permintaan tertinggi, serta menganalisis waktu perjalanan tersibuk guna memberikan rekomendasi peningkatan layanan transportasi publik.  

## 📊 Dataset  
Dataset yang digunakan berasal dari Kaggle: [TransJakarta Transportation Transaction Dataset](https://www.kaggle.com/datasets/dikisahkan/transjakarta-transportation-transaction/data).  
Dataset ini mencakup transaksi penumpang TransJakarta, dengan informasi seperti:  
- **Lokasi tap-in dan tap-out**  
- **Waktu perjalanan**  
- **Data kartu pembayaran**  
- **Identifikasi koridor dan halte**  

## 🔍 Key Analyses  
Analisis utama dalam repositori ini mencakup:  
✅ **OD Matrix Construction** → Membuat matriks Origin-Destination untuk memahami hubungan antarhalte.  
✅ **Most Frequented Routes** → Mengidentifikasi rute dengan jumlah perjalanan tertinggi.  
✅ **Peak Travel Hours Analysis** → Menentukan jam sibuk berdasarkan transaksi penumpang.  
✅ **Trip Duration Analysis** → Menghitung rata-rata waktu perjalanan dan mengidentifikasi rute dengan potensi keterlambatan.  
✅ **Passenger Flow Visualization** → Menampilkan pola pergerakan penumpang menggunakan heatmap dan grafik.  

## 🚀 Findings & Insights  
📌 **Halte dengan permintaan tertinggi:**  
- **Penjaringan**, **BKN**, dan **Cibubur Junction** memiliki jumlah penumpang tertinggi berdasarkan transaksi.  

📌 **Jam sibuk utama:**  
- **06.00-07.00 pagi** dan **17.00-18.00 sore** menunjukkan lonjakan signifikan dalam jumlah tap-in dan tap-out.  

📌 **Rata-rata durasi perjalanan:**  
- **1,2 jam** (1 jam 12 menit) dengan perjalanan terlama mencapai **3 jam**, menunjukkan potensi inefisiensi di beberapa rute.  

📌 **Rekomendasi:**  
- **Optimasi jadwal bus** pada jam sibuk.  
- **Redistribusi armada bus** untuk mengurangi kepadatan pada rute tertentu.  
- **Peningkatan layanan dan kapasitas** di halte-halte dengan volume tinggi.  

## 🛠 Technologies Used  
- **Python** (Pandas, NumPy, Matplotlib)  
- **Jupyter Notebook**  
- **Folium** (untuk visualisasi peta)  
- **PIL (Pillow)** (untuk manipulasi gambar)     
