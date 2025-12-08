Judul Project:
Product Sales Performance Analysis

Deskripsi:
Proyek ini merupakan analisis menyeluruh terhadap Product Sales Dataset. Dataset ini berisi 200.000 catatan penjualan sintetis yang mensimulasikan transaksi produk di berbagai wilayah di Amerika Serikat.
Tujuan utama proyek ini adalah membangun pipeline analitik end-to-end yang lengkap, dimulai dari perancangan data warehouse PostgreSQL, transformasi ETL, hingga pembuatan dashboard interaktif di Power BI untuk mengeksplorasi insight bisnis.

Tools:
PostgreSQL, PowerBI

Insight:
1. Revenue dipimpin oleh category Electronics (40%+ atau 57M). Produk high-value seperti laptops, smartphones, wearables menyumbang hampir setengah dari revenue.
2. Kontributor Revenue terbesar adalah di region East (45M). Strategi marketing & inventory perlu fokus ke East & West.
3. Top product secara revenue adalah Tempur-Pedic Mattress & Instant Pot. High-priced items memberikan revenue tinggi, bisa dimanfaatkan dengan strategi upselling.
4. Profit margin 22.15% relatif stabil. Bisnis cukup sehat, namun bisa ditingkatkan melalui fokus pada high-margin categories (bedding, mattresses)
5. California adalah state dengan revenue terbesar. Perlu ekspansi market ke states minor.
6. Sebagian kategori pakaian memiliki revenue kecil (Kids Wear, Bags, Wearable Accessories). Kategori-kategori kecil bisa ditinjau untuk: Stop-loss, Rebranding, Bundling promotion

Dataset:
https://www.kaggle.com/datasets/yashyennewar/product-sales-dataset-2023-2024

Project ini membangun Star Schema yang terdiri dari:
fact_orders
dim_dates
dim_customers
dim_products

Proses ETL dilakukan melalui SQL di PostgreSQL dengan berbagai langkah:
- Standardisasi format tanggal
- Cleaning dan Validasi data
- Key mapping antara fact & dimension

Selanjutnya PowerBI import data tersebut untuk dibuat dashboard dengan struktur:
- Summary Overview
- Customer and Product Insight
