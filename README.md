# Analisis Pola Penyewaan Sepeda Berdasarkan Waktu dan Kondisi Cuaca

## 👥 Anggota Kelompok

| Nama | NRP |
|---|---|
| Ester Yelisabeta | 5027261005 |
| Muhammad Naufal Azmi | 5027261059 |
| Muhammad Ikhsanul Amal | 50272611173 |

## 📌 Topik

**Smart City – Bike Sharing**

Analisis ini membahas pola penyewaan sepeda berdasarkan waktu dan kondisi cuaca menggunakan pendekatan Exploratory Data Analysis (EDA).

## 📊 Sumber Dataset

Dataset yang digunakan adalah **Permintaan Penyewaan Sepeda per Jam & Cuaca (Bike Sharing Demand: Hourly Rentals & Weather)** dari Kaggle.

- **Sumber:** Kaggle
- **Link:** https://www.kaggle.com/datasets/muhammadishahrukh/bike-sharing-demand-hourly-rentals-and-weather
- **Lisensi:** CC BY-NC-SA 4.0

Dataset berisi data penyewaan sepeda per jam beserta informasi waktu dan kondisi cuaca.

## 🔎 3 Temuan Utama

1. **Pola penyewaan berdasarkan waktu**  
   Jumlah penyewaan sepeda berbeda pada setiap jam dan terdapat jam tertentu dengan jumlah penyewaan yang lebih tinggi dibandingkan jam lainnya.

2. **Penyewaan berdasarkan kondisi cuaca**  
   Jumlah penyewaan sepeda berbeda berdasarkan kondisi cuaca yang terjadi.

3. **Karakteristik jumlah penyewaan**  
   Berdasarkan statistik deskriptif, rata-rata `total_rentals` adalah **189,46 sepeda per jam**, sedangkan mediannya **142 sepeda per jam**. Perbedaan tersebut menunjukkan bahwa distribusi penyewaan cenderung miring ke kanan.

1. Setelah install Miniconda, buat environment `statprob` dengan Python 3.11 dan aktifkan environment:
   ```bash
   conda create -n statprob python=3.11 -y
   conda activate statprob
2. Masuk ke folder project 1 `cd Documents\project1-eda-kelompok-01`
