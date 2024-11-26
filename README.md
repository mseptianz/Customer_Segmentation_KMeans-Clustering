# Segmentasi Pelanggan 📊 - ![KMeans Clustering](https://img.shields.io/badge/KMeans%20Clustering-FF9C00?style=for-the-badge&logo=google&logoColor=white)

Repositori ini berisi proyek segmentasi pelanggan menggunakan algoritma K-Means Clustering. Proyek ini bertujuan untuk mengelompokkan pelanggan berdasarkan perilaku dan karakteristik mereka, sehingga memungkinkan perusahaan untuk merumuskan strategi pemasaran yang lebih efektif. Repositori ini mencakup file Jupyter Notebook yang menjelaskan proses secara menyeluruh, mulai dari eksplorasi data hingga penerapan model clustering.

## Daftar Isi 🗒️
1. [Project Overview](#project-overview-)
2. [Latar Belakang Masalah](#latar-belakang-masalah)
3. [Problem Statement](#problem-statement-)
4. [Metode yang Digunakan](#metode-yang-digunakan-)
5. [Analisa Karakter per Cluster](#analisa-karakter-per-cluster-)
6. [Rekomendasi](#rekomendasi-)
7. [File yang Tersedia](#file-yang-tersedia-)
8. [Cara Menggunakan Project Ini](#cara-menggunakan-project-ini-)
9. [Dependencies](#dependencies-)
10. [Libraries](#libraries-)
11. [Author](#author-)

## Project Overview 📝

Dalam proyek ini, saya menggunakan algoritma K-Means Clustering untuk mengelompokkan pelanggan berdasarkan data historis mereka. Beberapa langkah utama yang dicakup dalam proyek ini adalah:

1. **Import Libraries dan Eksplorasi Data**:
    - Memuat dataset dan melakukan eksplorasi awal untuk memahami struktur dan karakteristik data.

2. **Preprocessing Data**:
    - Melakukan pembersihan dan persiapan data, termasuk penanganan missing values dan normalisasi data.

3. **Pengembangan Model**:
    - Membangun dan melatih model K-Means Clustering untuk mengelompokkan pelanggan.

4. **Evaluasi Model**:
    - Menggunakan metrik evaluasi untuk menilai kinerja model.

5. **Visualisasi Hasil**:
    - Menggambarkan hasil segmentasi dengan visualisasi yang mudah dipahami.

6. **Analisa Karakteristik per Cluster**:
    - Melakukan analisa karakteristik setiap cluster.

7. **Rekomendasi Bisnis per Cluster**:
    - Memberikan rekomendasi bisnis sesuai dengan karakteristik masing-masing cluster

## Latar Belakang Masalah

Perusahaan Bank ABC ingin meningkatkan efektivitas strategi marketing dengan menyegmentasi nasabah berdasarkan pola penggunaan kartu kredit selama 6 bulan terakhir. Dengan Customer Segmentation, tim marketing dapat lebih tepat menargetkan nasabah sesuai preferensi mereka, meningkatkan loyalitas, dan profitabilitas. Untuk itu, customer segmentation perlu dilakukan untuk membentuk kelompok nasabah yang karakteristik penggunaan kartu kreditnya mirip dan memberikan rekomendasi bisnis yang sesuai untuk setiap segmen.

## Problem Statement √

**Specific**: Mengelompokkan nasabah berdasarkan pola penggunaan kartu kredit.

**Measurable**: Minimal 3 cluster customer terbentuk.

**Achievable**: Menggunakan model clustering KMeans untuk segmentasi.

**Relevant**: Menggunakan model KMeans sangat relevan untuk mendapatkan minimal 3 cluster dan memberikan rekomendasi bisnis ke setiap cluster secara tepat sesuai karakteristik setiap cluster yang terbentuk.

**Time-bound**: Pembentukan segmentasi customer dilaksanakan dalam 1 minggu.

**Problem Statement:** Membuat Customer Segmentation berdasarkan data penggunaan kartu kredit selama 6 bulan terakhir dengan menggunakan metode machine learning unsupervised **`clustering`** . Tujuan dari analisis ini adalah untuk mengelompokkan nasabah ke dalam segmen-segmen berbeda berdasarkan perilaku penggunaan kartu kredit mereka, sehingga tim pemasaran dapat merancang strategi yang lebih tepat sasaran untuk setiap kelompok yang akan membantu meningkatkan retensi nasabah dan memaksimalkan penggunaan kartu kredit.

## Metode yang Digunakan 🛠️

- Statistik Deskriptif
- Machine Learning
- K-Means Clustering
- Visualisasi Data

## Analisa Karakter per Cluster 🧠

**Cluster 0:**
- Nama: "Pengguna Proaktif"
- Alasan: Pelanggan di cluster ini menunjukkan pemanfaatan kredit yang optimal dan aktif dalam melakukan transaksi, serta memiliki saldo dan limit kredit yang tinggi.
-Rekomendasi : Fokus pada upaya penagihan dan pengelolaan risiko kredit. Tawarkan program cicilan atau restrukturisasi utang untuk membantu pelanggan melunasi tagihan.

**Cluster 1:**
- Nama: "Pengguna Konservatif"
- Alasan: Pelanggan di cluster ini memiliki saldo dan limit kredit yang lebih rendah, dengan perilaku yang cenderung hati-hati dalam menggunakan kredit.
- Rekomendasi : 
Fokus pada upaya penagihan dan pengelolaan risiko kredit. Tawarkan program cicilan atau restrukturisasi utang untuk membantu pelanggan melunasi tagihan.

**Cluster 2:**
- Nama: "Pengguna Pasif"
- Alasan: Pelanggan di cluster ini memiliki saldo dan limit kredit yang terendah, serta aktivitas yang rendah dalam penggunaan kredit, menunjukkan kemungkinan mereka adalah pengguna baru atau kurang aktif.
- Rekomendasi : Tawarkan promo atau diskon khusus, serta kembangkan produk atau layanan yang sesuai dengan anggaran mereka.

## Rekomendasi 📌

Fokus utamanya adalah meningkatkan transaksi dan mempertahankan transaksi dari nasabah yang masuk kedalam cluster 1 dan cluster 2, tetapi tidak juga melupakan cluster 0. Cluster 1 dan cluster 2 menjadi fokus utama karena nasabah yang sering menggunakan kartu kredit ada pada cluster ini.

**Cluster 0: "Pengguna Proaktif"**

Karakteristik: Pelanggan aktif dengan saldo dan limit kredit tinggi, serta sering melakukan transaksi dalam jumlah besar.
Rekomendasi:
- Berikan penawaran eksklusif seperti diskon premium atau promo cashback untuk transaksi besar.
- Tawarkan program loyalitas seperti poin reward yang dapat ditukar dengan hadiah atau layanan premium.
- Sediakan informasi tentang investasi atau pengelolaan keuangan untuk meningkatkan kepercayaan mereka pada layanan bank.
- Tingkatkan engagement dengan layanan premium, seperti personal assistant atau akses eksklusif ke acara tertentu.

**Cluster 1: "Pengguna Konservatif"**
Karakteristik: Pelanggan dengan saldo dan limit kredit menengah hingga rendah, yang berhati-hati dalam menggunakan kartu kredit.
Rekomendasi:
- Tawarkan program cicilan ringan dengan bunga rendah untuk pembelian tertentu.
- Buat kampanye edukasi finansial untuk meningkatkan rasa percaya pelanggan terhadap penggunaan kredit.
- Berikan insentif untuk transaksi kecil, seperti bonus poin reward atau cashback untuk pembelian harian.
- Promosikan program diskon untuk kebutuhan rumah tangga atau transaksi rutin, sehingga mereka lebih nyaman menggunakan kartu kredit.

**Cluster 2: "Pengguna Pasif"**
Karakteristik: Pelanggan dengan saldo, limit kredit, dan aktivitas yang rendah, kemungkinan pengguna baru atau tidak aktif.
Rekomendasi:
- Tawarkan welcome bonus atau promo khusus untuk transaksi pertama dengan kartu kredit.
- Kirimkan notifikasi berkala tentang promo atau diskon yang sesuai dengan kebiasaan atau minat pelanggan.
- Buat paket bundling produk kartu kredit dengan manfaat tambahan seperti asuransi, voucher belanja, atau cashback.
- Tawarkan layanan reminder atau auto-debit untuk tagihan kecil guna meningkatkan kebiasaan penggunaan kartu kredit.
  
**Fokus Utama: Meningkatkan Aktivitas Cluster 1 & Cluster 2**

Jalankan kampanye pemasaran berbasis kebutuhan untuk cluster 1 dan cluster 2 agar mereka lebih percaya menggunakan kartu kredit untuk transaksi harian.
Gunakan data analitik untuk merekomendasikan promo yang relevan, sehingga pelanggan merasa lebih terbantu dalam memenuhi kebutuhan mereka.

**Jangan Lupakan Cluster 0:**   
Pelanggan di cluster ini merupakan pengguna loyal yang dapat menghasilkan pendapatan besar. Fokus pada mempertahankan hubungan baik dengan layanan prioritas dan penawaran eksklusif.

## File yang Tersedia 📂

- `customer_segmentation.ipynb`: Jupyter Notebook yang berisi langkah-langkah analisis data, pengembangan model K-Means, evaluasi model, dan wawasan yang diperoleh dari analisis.
- `customer_data.csv`: Dataset yang digunakan dalam analisis. Diambil dari google bigquery menggunakan syntax SQL melalui google collab.
- `data_inference.ipynb`: Jupyter Notebook yang berisi prediksi unseen data menggunakan model yang sudah dibuat sebelumnya
- `kmeans.pkl, list_num_col.txt, pca.pkl, scaler.pkl`: Hasil penyimpanan model dan preprocessing
  
## Cara Menggunakan Project Ini 💻

1. Clone repositori ini ke dalam lokal Anda:
    ```bash
    git clone https://github.com/mseptianz/Customer_Segmentation_KMeans-Clustering.git
    ```

2. Jalankan Jupyter Notebook untuk mengikuti alur analisis data:
    ```bash
    jupyter notebook customer_segmentation.ipynb
    ```

## Dependencies ⚙️

- ![Jupyter Notebook](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)
- ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) 3.12.14

## Libraries 📚
- Pandas
- NumPy
- Scikit-learn
- Plotly
- Matplotlib
- Seaborn
- JSON
- Pickle

## Author ✍️
**Muhammad Septian Zamzani**

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammad-septian-zamzani-a9a8b5230/)
