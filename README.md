# 📊 Capstone Project: Prediksi Harga Saham Apple (AAPL)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rasab1ru/capstone-aapl-stock/blob/main/apple_stock_prediction.ipynb)

Proyek ini bertujuan untuk menganalisis tren harga saham Apple Inc. (AAPL) dari tahun 2010 hingga 2020 menggunakan data historis dan bantuan model Linear Regression dari AI.  
Notebook ini dibuat menggunakan Google Colab dan dilengkapi dengan visualisasi tren serta prediksi sederhana selama 5 hari ke depan.

🔗 **Notebook**: [`apple_stock_prediction.ipynb`](apple_stock_prediction.ipynb)  
📁 **Dataset**: [`aapl_stock_data.csv`](aapl_stock_data.csv)

---

## 📂 Dataset
- **Nama File**: `aapl_stock_data.csv`
- **Isi**: Data harga saham harian Apple (open, high, low, close, volume, dan date)
- **Sumber**: Simulasi dari data historis (untuk edukasi)

---

## 🔍 Insight & Temuan
- Harga saham Apple menunjukkan tren naik jangka panjang.
- Moving Average (MA 7 dan MA 30) mendukung tren pertumbuhan yang konsisten.
- Terdapat fluktuasi signifikan di tahun 2013 dan 2016.
- Prediksi harga 5 hari ke depan menggunakan Linear Regression menunjukkan tren stabil naik:

| Hari ke- | Prediksi Harga (USD) |
|---------:|----------------------:|
| 1        | $155.94               |
| 2        | $155.96               |
| 3        | $155.96               |
| 4        | $155.98               |
| 5        | $155.99               |

---

## 🤖 Model AI yang Digunakan
- `LinearRegression` dari library `scikit-learn`
- Model dilatih dengan variabel waktu (`jumlah hari`) untuk memprediksi harga penutupan

---

## ✅ Rekomendasi
Apple cocok untuk strategi investasi jangka menengah hingga panjang karena tren yang stabil.  
Namun, perlu mempertimbangkan faktor eksternal dan rilis produk yang bisa memengaruhi harga dalam jangka pendek.
