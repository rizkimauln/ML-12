# Implementasi K-Means Clustering

Repository ini berisi implementasi algoritma **K-Means Clustering** menggunakan Python dan Jupyter Notebook. Proyek ini dikerjakan sebagai bagian dari penyelesaian Modul 11 (Machine Learning) yang mencakup praktik terbimbing dan latihan mandiri dengan dataset eksternal.

## Isi Repository

Di dalam repository ini, terdapat tiga buah Jupyter Notebook utama:

1. **`Modul_11_KMeans_GoTrack.ipynb`**
   Merupakan implementasi K-Means clustering sesuai dengan panduan Modul 11. Notebook ini menggunakan dataset **GPS Trajectories** (`go_track_tracks.csv`) yang berasal dari aplikasi Android Go!Track. Tujuannya adalah mengelompokkan data berdasarkan jarak (*distance*) dan kecepatan (*speed*).

2. **`Latihan_KMeans_MallCustomers.ipynb`**
   Merupakan latihan mandiri yang menerapkan konsep segmentasi pelanggan (Customer Segmentation). Menggunakan dataset dari Kaggle, yaitu **Mall Customer Segmentation Data**. Pada notebook ini, pelanggan dikelompokkan menjadi 5 cluster natural berdasarkan pendapatan (*Annual Income*) dan skor pengeluaran (*Spending Score*).

3. **`Modul_KMeans_MallCustomers.ipynb`**
   Merupakan adaptasi langsung dari format langkah demi langkah yang ada di `Modul_11_KMeans_GoTrack.ipynb`, namun diterapkan pada dataset `Mall_Customers.csv`. Notebook ini dibuat untuk menunjukkan bagaimana format kode dari modul dapat langsung diimplementasikan pada dataset baru dengan sangat sedikit modifikasi.

## Prasyarat (Requirements)

Untuk dapat menjalankan file-file `.ipynb` di atas, pastikan environment Python Anda memiliki library berikut:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Semua file *notebook* di atas menggunakan dataset lokal yang sudah disertakan di dalam folder ini (`go_track_tracks.csv` dan `Mall_Customers.csv`).

---
**Credits:** rizki.mauln
