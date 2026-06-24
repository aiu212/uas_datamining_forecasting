# UAS Data Mining — Forecasting Jumlah Penyewaan Sepeda

Project akhir mata kuliah **Konsep Data Warehouse & Mining**, dengan kategori studi kasus **Forecasting (Peramalan)**, menggunakan **Bike Sharing Dataset**.

## 👤 Identitas

- **Nama:** Siti Wahyu Nur Asiah Jamil (1224160098)
- **Kelas:** SI 24 P SIM 2
- **Mata Kuliah:** Konsep Data Warehouse & Mining
- **Dosen:** Agus Rifaldi, S.Kom

## 📋 Deskripsi Studi Kasus

Bike Sharing merupakan layanan penyewaan sepeda yang banyak digunakan sebagai alternatif transportasi maupun sarana rekreasi. Jumlah penyewaan sepeda bersifat dinamis dan dipengaruhi oleh berbagai faktor seperti waktu (jam, hari, bulan), musim, kondisi cuaca, suhu, kelembapan, dan kecepatan angin.

Project ini menerapkan kategori studi kasus **Forecasting (Peramalan)** untuk memprediksi jumlah penyewaan sepeda berdasarkan faktor-faktor tersebut, menggunakan algoritma Machine Learning **Random Forest Regressor**.

## 📊 Dataset

- **Nama Dataset:** Bike Sharing Dataset
- **Sumber:** [kaggle.com/datasets/lakshmi25npathi/bike-sharing-dataset](https://www.kaggle.com/datasets/lakshmi25npathi/bike-sharing-dataset)
- **File:** `hour.csv`
- **Jumlah Data:** 17.379 baris, 17 atribut

## 🔄 Tahapan CRISP-DM

1. **Business Understanding** — Latar belakang masalah, tujuan, dan manfaat project
2. **Data Understanding** — Deskripsi dataset, struktur data, statistik deskriptif, eksplorasi data awal
3. **Data Preparation** — Data cleaning, pemeriksaan missing value, seleksi fitur, pembagian data training/testing
4. **Modeling** — Linear Regression dan Random Forest Regressor
5. **Evaluation** — Pengukuran performa model dengan MAE, RMSE, dan R² Score
6. **Deployment** — Publikasi hasil dalam bentuk website portofolio

## 📈 Hasil Evaluasi

| Model | MAE | RMSE | R² Score | Performa |
|---|---|---|---|---|
| Linear Regression | 104.80 | 139.21 | 0.3880 | 38.80% |
| **Random Forest Regressor** | **24.73** | **41.85** | **0.9447** | **94.47%** ✅ |

Model **Random Forest Regressor** dipilih sebagai model terbaik karena berhasil mencapai performa **94,47%**, jauh di atas kriteria sukses minimal **80%**.

## 🗂️ Isi Repository

```
├── UAS_KDWM_AYU.ipynb     # Source code lengkap (Jupyter Notebook)
├── hour.csv                # Dataset Bike Sharing
└── README.md               # File ini
```

## 🔗 Link Terkait

- **Website Portofolio (Google Sites):** https://sites.google.com/view/uas-datamining-sitiwahyunaj
- **Video Presentasi (YouTube):** https://youtu.be/Cv1SiFCTkfA?si=Rgmng-2z8UNETbLb
