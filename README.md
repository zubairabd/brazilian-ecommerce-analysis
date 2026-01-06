# 🇧🇷 Brazilian E-Commerce Data Analysis & Customer Segmentation
> Proyek analisis data end-to-end untuk mengidentifikasi perilaku belanja pelanggan dan mengoptimalkan strategi marketing menggunakan metode RFM.

## Ringkasan Proyek
Proyek ini menganalisis dataset e-commerce Brasil (Olist) yang mencakup 100 ribu pesanan dari tahun 2016 hingga 2018. Tujuan utamanya adalah melakukan segmentasi pelanggan untuk memberikan rekomendasi bisnis yang didorong oleh data.

## Tech Stack
- **Language:** Python 3.10
- **Libraries:** Pandas (Data Wrangling), Plotly & Folium (Visualization), Kagglehub (Data Ingestion).
- **Tool:** Google Colab.

## Alur Kerja Proyek
1. **Data Ingestion:** Menarik data secara real-time dari Kaggle API.
2. **Data Cleaning:** Menangani nilai hilang, menghapus duplikat, dan konversi tipe data datetime.
3. **Geospatial Analysis:** Memetakan distribusi pendapatan dan pelanggan di seluruh negara bagian Brasil.
4. **RFM Analysis:** Menghitung skor *Recency, Frequency,* dan *Monetary* untuk setiap pelanggan unik.
5. **Customer Segmentation:** Mengelompokkan pelanggan menjadi 4 kategori: *Champions, Regular, New Customers,* dan *At Risk*.

## Temuan Utama (Key Insights)
- **Distribusi Geografis:** Wilayah Tenggara Brasil (Sao Paulo & Rio de Janeiro) menyumbang lebih dari 40% total transaksi.
- **Segmentasi Pelanggan:** - **Regular (Mayoritas):** ~49rb pelanggan. Peluang besar untuk program loyalitas.
    - **At Risk:** ~24rb pelanggan yang sudah lama tidak belanja. Membutuhkan strategi *win-back*.
    - **Champions:** ~1.9rb pelanggan bernilai tinggi yang harus dipertahankan.

## Cara Menjalankan
1. Buka notebook [Link Google Colab ].
2. Pastikan kamu memiliki koneksi internet untuk menarik data via `kagglehub`.
3. Jalankan sel secara berurutan.

## Visualisasi

![Customer Segmentation](images/treemap_segmentasi.png)
![Revenue Map](images/peta_brazil.png)
