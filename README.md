
---

# **Customer Segmentation Using Clustering**  

## **Pendahuluan**  
Proyek ini bertujuan untuk **mengelompokkan pelanggan kartu kredit berdasarkan pola transaksi mereka** menggunakan **K-Means Clustering**. Dengan segmentasi yang lebih akurat, Bank ABC dapat **menyusun strategi pemasaran yang lebih efektif, meningkatkan loyalitas pelanggan, dan mengoptimalkan penawaran produk**.  

## **Tujuan Proyek**  
- **Mengidentifikasi pola penggunaan kartu kredit pelanggan**  
- **Membantu perancangan strategi pemasaran yang lebih tepat sasaran**  
- **Meningkatkan kepuasan dan loyalitas pelanggan melalui penawaran yang lebih personal**  

## **Tahapan Proyek**  
1. **Pengumpulan Data** → Mengambil data transaksi  dari **Google BigQuery**  
2. **Preprocessing Data** → Cleaning data, handling missing values, normalisasi (scaling), dan reduksi dimensi dengan PCA  
3. **Feature Engineering** → Pemilihan variabel utama berdasarkan pola transaksi pelanggan  
4. **Modeling** → Menerapkan **K-Means Clustering** untuk mengelompokkan pelanggan  
5. **Evaluasi Model** → Menentukan jumlah klaster optimal menggunakan **Elbow Method & Silhouette Score**  
6. **Visualisasi Hasil** → Menampilkan hasil clustering dengan **Matplotlib & Seaborn**  

## **Teknologi yang Digunakan**  
- **Database**: Google BigQuery  
- **Pemrograman & Machine Learning**: SQL, Python, Scikit-learn, Pandas, NumPy  
- **Visualisasi Data**: Matplotlib, Seaborn  
- **Notebook**: Google Colab / Jupyter Notebook  

## **Hasil Segmentasi Pelanggan**  
Dari hasil segmentasi, pelanggan terbagi menjadi **5 klaster** dengan karakteristik yang berbeda:  

1. **Klaster 0** → Pelanggan aktif dengan saldo tinggi, batas kredit besar, dan sering menggunakan cash advance  
2. **Klaster 1** → Pelanggan konservatif dengan transaksi rendah, saldo kecil, dan batas kredit rendah  
3. **Klaster 2** → Pelanggan dengan penggunaan sedang, saldo dan batas kredit bervariasi, serta jarang menggunakan cash advance  
4. **Klaster 3** → Pelanggan dengan saldo tinggi, pembayaran besar, dan batas kredit tinggi tetapi penggunaan cash advance minim  
5. **Klaster 4** → Pelanggan dengan saldo rendah, pembayaran kecil, dan jarang menggunakan kartu kredit  

## **Rekomendasi Bisnis**  
Dari hasil segmentasi pelanggan ini, **Bank ABC** dapat mengembangkan strategi pemasaran yang lebih tepat sasaran:  

- **Klaster 0** → Tawarkan **produk premium & layanan eksklusif** untuk meningkatkan loyalitas pelanggan berdaya beli tinggi  
- **Klaster 1** → Edukasi pelanggan tentang **manfaat penggunaan kartu kredit** dan tawarkan peningkatan batas kredit  
- **Klaster 2** → Berikan **program cashback atau rewards** untuk meningkatkan penggunaan kartu kredit  
- **Klaster 3** → Kembangkan **penawaran khusus dan layanan eksklusif** bagi pelanggan dengan potensi finansial tinggi  
- **Klaster 4** → Berikan promosi untuk mendorong penggunaan kartu kredit lebih aktif  

## **Saran Analisis Selanjutnya**  
- **Melakukan eksplorasi data tambahan (EDA)** → Menganalisis pola belanja berdasarkan kategori transaksi dan waktu penggunaan kartu kredit  
- **Mengidentifikasi kelompok pelanggan yang kurang mendapat perhatian** → Memastikan semua segmen mendapatkan penawaran produk yang sesuai  
- **Menganalisis waktu transaksi tertinggi** → Mengoptimalkan promosi dan marketing campaign pada jam transaksi yang paling aktif  
- **Memahami preferensi pelanggan** → Mengembangkan produk yang lebih sesuai dengan kebutuhan pelanggan  

## **Impact Bisnis**  
- **Optimasi strategi pemasaran** → Menargetkan pelanggan dengan promosi yang lebih relevan berdasarkan segmen mereka  
- **Peningkatan loyalitas pelanggan** → Memberikan penawaran yang lebih personal untuk meningkatkan retensi pelanggan  
- **Optimasi penggunaan kartu kredit** → Mendorong pelanggan untuk lebih aktif menggunakan kartu kredit dan meningkatkan transaksi per pelanggan  

## **Cara Menjalankan Proyek**  
1. Clone repository ini  
2. Instal dependensi dengan `pip install -r requirements.txt`  
3. Hubungkan dengan **Google BigQuery** untuk mengambil data  
4. Jalankan skrip analisis dan model clustering di **Jupyter Notebook**  

## **Kontak**  
Jika ada pertanyaan atau saran, silakan hubungi:  
**Email**: yinkasinulingga@gmail.com  

---

