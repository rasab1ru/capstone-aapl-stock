# 📈 Capstone Project: Prediksi Harga Saham Apple (AAPL)

Proyek ini bertujuan untuk menganalisis tren harga saham **Apple Inc. (AAPL)** dari tahun **2010 hingga 2020** menggunakan data historis dan bantuan model **Linear Regression** dari AI.  
Notebook ini dibuat menggunakan **Google Colab** dan dilengkapi dengan visualisasi tren serta prediksi 5 hari ke depan.

---

## 📊 Dataset

- **Nama File:** `aapl_stock_data.csv`
- **Isi:** Data harga saham harian Apple (open, high, low, close, volume, dan date)
- **Sumber:** Simulasi dari data historis realistis (untuk edukasi)

---

## 🔍 Insight & Temuan

- Harga saham Apple menunjukkan **tren naik jangka panjang**.
- Moving Average (**MA 7 dan MA 30**) mendukung tren yang konsisten.
- Terdapat **fluktuasi signifikan** di tahun 2013 dan 2016.
- Prediksi harga 5 hari ke depan menggunakan Linear Regression menunjukkan tren stabil naik.

| Hari ke- | Prediksi Harga (USD) |
|---------|-----------------------|
| 1       | $155.94               |
| 2       | $155.96               |
| 3       | $155.96               |
| 4       | $155.98               |
| 5       | $155.99               |

---

## 🧠 Model AI yang Digunakan

- **LinearRegression** dari `scikit-learn`
- Model dilatih dengan variabel waktu (jumlah hari sejak awal) untuk memprediksi harga penutupan

---

## 💡 Rekomendasi

Apple cocok untuk strategi **investasi jangka menengah hingga panjang** karena tren yang stabil.  
Namun, perlu tetap mempertimbangkan faktor eksternal seperti **rilis produk** dan **kondisi pasar global**.

---

## 🛠 Cara Menjalankan

1. Upload file `aapl_stock_data.csv` ke Google Colab
2. Jalankan sel notebook `ca.ipynb` secara berurutan
3. Lihat grafik tren dan hasil prediksi di bagian akhir

---

## 🧾 Lisensi

Project ini digunakan untuk keperluan edukasi. Bebas untuk direplikasi dan dimodifikasi selama mencantumkan sumber.

---

## 🙋‍♂️ Kontributor

- 🧑‍💻 `rasab1ru` – Developer, data analyst, and AI explorer
