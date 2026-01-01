# Kelompok-10_Data-Warehouse-Business-Intelligence_Olist-E-Commerce
Proyek Data Warehouse & Business Intelligence:
OLIST Marketplace
📌 Ringkasan Proyek

Proyek ini merupakan implementasi solusi Data Warehouse dan Business Intelligence (BI) pada OLIST Marketplace dengan fokus utama pada perspektif finansial. Tujuan utama dari proyek ini adalah untuk menganalisis kinerja penjualan, kontribusi pendapatan, serta perilaku pelanggan guna mendukung proses pengambilan keputusan strategis berbasis data.

Dengan memanfaatkan pendekatan Data Warehouse dan visualisasi BI, proyek ini menyajikan informasi keuangan secara terintegrasi, ringkas, dan mudah dipahami oleh manajemen.

🎯 Tujuan Utama Proyek

1. Merancang Data Warehouse menggunakan pendekatan Star Schema.

2. Melakukan proses ETL (Extract, Transform, Load) dari data operasional ke data analitik.

3. Menghasilkan indikator kinerja utama (KPI) berbasis finansial.

4. Mengembangkan dashboard interaktif sebagai alat pemantauan performa bisnis OLIST Marketplace.

📊 1. Desain Data Warehouse

Database operasional OLIST ditransformasikan menjadi Star Schema 
untuk mendukung kebutuhan analisis dan pelaporan (OLAP).

🔹 Tabel Fakta

Fact_Sales

Measure utama:

Quantity

Revenue

🔹 Tabel Dimensi

Dim_Customer
Informasi pelanggan seperti CustomerID dan lokasi.

Dim_Time
Informasi waktu transaksi (tanggal, bulan, tahun).

Dim_Product
Informasi produk seperti kategori dan atribut fisik.

Dim_Seller
Informasi penjual berdasarkan lokasi dan identitas.

Struktur ini memungkinkan analisis penjualan dari berbagai perspektif secara fleksibel dan efisien.

🧠 2. Analisis Data & Insight Finansial

Analisis difokuskan pada pendapatan dan perilaku pelanggan berdasarkan data hasil integrasi pada Data Warehouse.

A. Analisis Pendapatan (Revenue Analysis)

- Menghitung Total Revenue sebagai indikator utama performa bisnis.

- Mengidentifikasi kontribusi penjualan berdasarkan pelanggan dan produk.

B. Analisis Perilaku Pelanggan

- Mengukur Average Revenue per Customer (ARPC) untuk mengetahui nilai ekonomi rata-rata setiap pelanggan.

- Analisis ini membantu dalam memahami distribusi nilai pelanggan pada marketplace.

📈 3. Visualisasi Dashboard Business Intelligence

Dashboard BI dirancang sebagai Executive Dashboard yang menampilkan KPI utama OLIST Marketplace secara visual dan interaktif.

KPI yang Ditampilkan:

Total Revenue
Menunjukkan total pendapatan keseluruhan marketplace.

Average Revenue per Customer (ARPC)
Menggambarkan rata-rata kontribusi pendapatan tiap pelanggan.

Top Revenue Contributor
Menampilkan pelanggan atau entitas dengan kontribusi revenue tertinggi.

Distribusi Revenue
Menunjukkan sebaran pendapatan berdasarkan dimensi terkait.

Tren Penjualan
Memberikan gambaran pola penjualan untuk mendukung evaluasi performa bisnis.

Dashboard ini dirancang untuk membantu manajemen dalam:

- Memantau kinerja finansial

- Mengevaluasi strategi penjualan

- Mendukung pengambilan keputusan berbasis data
