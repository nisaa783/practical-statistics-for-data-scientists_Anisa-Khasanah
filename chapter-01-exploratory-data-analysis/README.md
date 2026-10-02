# Chapter 1: Exploratory Data Analysis

Bab ini membahas dasar-dasar **Exploratory Data Analysis (EDA)** untuk meringkas, menganalisis, dan memvisualisasikan data terstruktur sebelum masuk ke pemodelan Machine Learning.

---

## Ringkasan Teori

1. **Estimasi Lokasi (Location Estimates):** 
   Digunakan untuk mengetahui nilai pusat dari distribusi data.
   * **Mean (Rata-rata):** Penjumlahan seluruh nilai dibagi jumlah data (sensitif terhadap *outlier*).
   * **Median:** Nilai tengah dari data yang telah diurutkan (lebih tahan terhadap *outlier*).
   * **Trimmed Mean:** Rata-rata yang dihitung setelah membuang sejumlah persentase data di bagian ujung (atas dan bawah).
   * **Weighted Mean:** Rata-rata tertimbang, di mana setiap titik data memiliki bobot atau kepentingan yang berbeda.

2. **Estimasi Variabilitas (Variability Estimates):**
   Digunakan untuk mengukur seberapa menyebarnya data dari nilai pusatnya.
   * **Variance & Standard Deviation:** Ukuran penyebaran standar yang sensitif terhadap *outlier*.
   * **Mean Absolute Deviation (MAD):** Rata-rata selisih absolut dari nilai median.
   * **Interquartile Range (IQR):** Selisih antara persentil ke-75 dan persentil ke-25 (tidak terpengaruh *outlier*).

3. **Eksplorasi Data Kategorikal:**
   * **Modus:** Nilai yang paling sering muncul dalam data kategorikal.
   * **Expected Value:** Nilai rata-rata yang diharapkan dari suatu kejadian probabilistik.
   * **Bar Chart & Pie Chart:** Visualisasi frekuensi atau proporsi dari setiap kategori.

4. **Visualisasi Data:**
   * **Box Plot:** Menampilkan ringkasan distribusi data berdasarkan kuartil dan *outlier*.
   * **Histogram:** Menampilkan frekuensi kemunculan data dalam bentuk interval (bin).
   * **Density Plot:** Versi mulus dari histogram yang memperkirakan fungsi kepadatan probabilitas (*probability density*).

---
