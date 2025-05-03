# Folder Ujian Tengah Semester - Model Machine Learning

Repositori ini berisi tiga notebook utama yang mendemonstrasikan penerapan berbagai algoritma machine learning untuk tiga jenis tugas utama: regresi, klasifikasi, dan clustering. Setiap file memuat implementasi dengan beragam pendekatan model.

## 1. Model Regresi
Notebook `MachineLearning_UTS_Regresion.ipynb` mengeksplorasi teknik regresi untuk memprediksi variabel kontinu menggunakan model-model berikut:
- Linear Regression
- Polynomial Regression (menggunakan PolynomialFeatures dan LinearRegression)
- Decision Tree Regressor
- K-Nearest Neighbors (KNN) Regressor
- Bagging Regressor
- Boosting Regressor (termasuk AdaBoost dan Gradient Boosting)
- Support Vector Regressor (SVR)

### Tinjauan Perbandingan Model Regresi

| Model                   | Kelebihan                                      | Keterbatasan                                              |
|------------------------|------------------------------------------------|-----------------------------------------------------------|
| Linear Regression       | Mudah dipahami dan diinterpretasikan           | Tidak efektif untuk hubungan non-linear                   |
| Polynomial Regression   | Menangkap hubungan non-linear antar fitur      | Risiko overfitting pada derajat tinggi                    |
| Decision Tree Regressor | Mampu memodelkan data kompleks dan bercabang   | Rentan overfitting jika tidak dilakukan pruning           |
| KNN Regressor           | Sederhana dan intuitif                         | Kurang efisien pada dataset besar, peka terhadap outlier  |
| Bagging Regressor       | Lebih stabil, kurangi varians                  | Butuh sumber daya lebih banyak dan sulit dijelaskan       |
| Boosting Regressor      | Akurasi tinggi dengan pengurangan bias         | Sensitif terhadap data noise dan overfitting              |
| SVR                     | Andal untuk data berdimensi tinggi             | Parameter tuning kompleks, performa lambat pada dataset besar |

## 2. Model Klasifikasi
Notebook `MachineLearning_UTS_Classification.ipynb` berisi implementasi model klasifikasi untuk memprediksi kelas dari data kategorikal, di antaranya:
- Logistic Regression
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)
- Bagging dan Boosting Classifier
- Support Vector Machine (SVM)

### Tinjauan Perbandingan Model Klasifikasi

| Model                    | Kelebihan                                     | Keterbatasan                                              |
|--------------------------|-----------------------------------------------|-----------------------------------------------------------|
| Logistic Regression      | Memberikan probabilitas prediksi              | Terbatas pada hubungan linear antara fitur dan label      |
| Decision Tree Classifier | Mudah divisualisasikan, dukung fitur kategori | Rentan overfitting jika tidak diatur kedalamannya         |
| KNN Classifier           | Non-parametrik dan simpel                     | Lambat saat memproses data besar, sensitif terhadap noise |
| Bagging Classifier       | Stabil dan kurangi overfitting                | Kompleksitas model meningkat                              |
| Boosting Classifier      | Performa sangat baik dalam banyak kasus       | Dapat overfit dan memerlukan parameter tuning             |
| SVM                      | Cocok untuk data berdimensi tinggi            | Kurang efisien pada skala besar dan perlu tuning cermat   |

## 3. Model Clustering
Notebook `MachineLearning_UTS_Clustering.ipynb` digunakan untuk eksplorasi teknik clustering, yaitu pengelompokan data tanpa label menggunakan algoritma:
- KMeans
- Agglomerative Clustering
- DBSCAN
- Gaussian Mixture Model (GMM)
- Spectral Clustering

### Tinjauan Perbandingan Model Clustering

| Model                    | Kelebihan                                     | Keterbatasan                                                    |
|--------------------------|-----------------------------------------------|-----------------------------------------------------------------|
| KMeans                   | Cepat, efisien pada data berskala besar       | Asumsi bentuk cluster bulat, tidak tahan outlier                |
| Agglomerative Clustering | Tidak memerlukan jumlah cluster di awal       | Proses lambat dan sulit menentukan cut-off                      |
| DBSCAN                   | Deteksi cluster bentuk bebas dan outlier      | Sensitif terhadap nilai epsilon dan minimum sampel              |
| Gaussian Mixture Model   | Cocok untuk data yang memiliki overlap cluster | Bergantung pada inisialisasi dan bisa berhenti di solusi lokal  |
| Spectral Clustering      | Tangani bentuk cluster kompleks atau non-konveks | Konsumsi memori tinggi, butuh jumlah cluster sejak awal        |

## Contoh Aplikasi Model

- **Linear Regression**: Estimasi harga rumah berdasarkan luas dan lokasi.
- **Polynomial Regression**: Prediksi tren populasi dengan pola pertumbuhan kompleks.
- **Decision Tree Regressor**: Perkiraan pendapatan berdasarkan faktor demografis.
- **KNN Regressor**: Rekomendasi rating produk berdasar preferensi pengguna lain.
- **Bagging Regressor**: Prediksi hasil pertanian berdasarkan cuaca dan tanah.
- **Boosting Regressor**: Penilaian risiko kredit dengan riwayat finansial.
- **SVR**: Perkiraan harga saham dari indikator teknikal.

- **Logistic Regression**: Prediksi diagnosis penyakit dari gejala.
- **Decision Tree Classifier**: Penilaian kelayakan pinjaman pelanggan.
- **KNN Classifier**: Identifikasi jenis bunga berdasarkan fitur fisik.
- **Bagging Classifier**: Prediksi pelanggan yang kemungkinan berhenti berlangganan.
- **Boosting Classifier**: Deteksi transaksi mencurigakan atau penipuan.
- **SVM**: Klasifikasi dokumen atau email menjadi spam dan bukan spam.

- **KMeans**: Segmentasi pelanggan untuk strategi pemasaran.
- **Agglomerative Clustering**: Klasifikasi taksonomi spesies berdasarkan data genetik.
- **DBSCAN**: Deteksi aktivitas abnormal dalam sistem jaringan.
- **Gaussian Mixture Model**: Pengenalan area pada gambar berdasarkan warna.
- **Spectral Clustering**: Temukan komunitas dalam data jaringan sosial.

