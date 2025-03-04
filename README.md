# 📊 E-Commerce Performance Tracker: Best-Selling Products & Seller Efficiency  

🚀 **Dashboard interaktif untuk menganalisis performa e-commerce berdasarkan penjualan produk dan efisiensi seller.**  

## 🔥 Fitur Utama  

### 1️⃣ Analisis Penjualan  
🔹 Menampilkan **kategori produk dengan peningkatan penjualan paling signifikan dalam 6 bulan terakhir**.  
🔹 Menggunakan **jumlah transaksi dan revenue** sebagai indikator pertumbuhan.  
🔹 Data diambil dari **`order_items_dataset.csv`** dan **`products_dataset.csv`**.  
🔹 Visualisasi menggunakan **bar chart dan line chart**.  

### 2️⃣ Efisiensi Seller  
📦 **Mengukur rata-rata waktu pengiriman seller** berdasarkan selisih waktu antara pesanan dibuat hingga diterima pelanggan.  
🔹 Data dari **`orders_dataset.csv`** (kolom `order_purchase_timestamp` & `order_delivered_customer_date`).  
🔹 Menampilkan **seller dengan pengiriman tercepat** dalam bentuk **bar chart**.  

### 3️⃣ RFM Analysis (Recency, Frequency, Monetary)  
🛒 **Segmentasi pelanggan berdasarkan pola pembelian**:  
- **Recency (R)** → Seberapa baru pelanggan terakhir kali berbelanja.  
- **Frequency (F)** → Seberapa sering pelanggan melakukan transaksi.  
- **Monetary (M)** → Total pembelanjaan pelanggan.  
🔹 Data dari **`orders_dataset.csv`** dan **`order_payments_dataset.csv`**.  
🔹 Hasilnya digunakan untuk mengidentifikasi **Best Customers, Lost Customers, dan Potential Loyalists**.  
🔹 Visualisasi dalam **scatter plot atau heatmap**.  

### 4️⃣ Dashboard Interaktif  
🎯 **Metric Cards**:  
- **Total Penjualan** → Jumlah transaksi dalam periode tertentu.  
- **Total Revenue** → Pendapatan total dari penjualan.  
- **Rata-rata Waktu Pengiriman** → Durasi rata-rata pesanan diterima pelanggan.  

📊 **Bar Chart**:  
- **Kategori Produk dengan Peningkatan Penjualan Terbesar**.  
- **Seller dengan Pengiriman Tercepat**.  

📈 **Line Chart**:  
- **Tren Penjualan per Bulan**.  
- **Customer Review Score (Opsional)**.  

🔎 **Filter Berdasarkan Tanggal**:  
- Pengguna dapat memilih rentang tanggal untuk melihat data spesifik.  

### 5️⃣ EDA (Exploratory Data Analysis)  
🔍 **Analisis eksploratif awal** untuk memahami dataset:  
- **Cek Data Missing & Duplicate**.  
- **Distribusi Kategori Produk**.  
- **Distribusi Waktu Pengiriman**.  
- **Visualisasi Awal untuk Insight Data**.  

---

## 🛠️ Teknologi yang Digunakan  
✅ **Python** (Pandas, Matplotlib, Seaborn, Plotly)  
✅ **Streamlit** (Dashboard Interaktif)  
✅ **GitHub** (Version Control)  

---

## 📌 Cara Menjalankan Dashboard  
1. **Clone Repository**  
   ```
   git clone (https://github.com/covryzne/submission-analysis-dashboard-ecommerce-public-dataset.git)
   cd submission-analysis-dashboard-ecommerce-public-dataset
   ```

2. Install Dependencies
   ```
   pip install -r requirements.txt
   ```
   
3. Jalankan Streamlit
   ```
   streamlit run app.py
   ```
## 📷 Preview Dashboard
![Screenshot (199)](https://github.com/user-attachments/assets/7647bc69-ea8a-4b3a-861e-093825a1de0a)
![Screenshot (200)](https://github.com/user-attachments/assets/096ec119-92ea-47f8-bbbd-0fa4066798ba)

## 🤝 Kontribusi
Jika ingin berkontribusi, silakan buat pull request atau buka issue di repo ini. 🚀

## 📢 Kontak
👤 covryzne <br>
📧 Email: `shendyteuku2@gmail.com` <br>
🔗 GitHub: [![GitHub](https://img.shields.io/badge/GitHub-Covryzne-181717?logo=github&logoColor=white)](https://github.com/covryzne)

