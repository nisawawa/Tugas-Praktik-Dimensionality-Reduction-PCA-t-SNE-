Nama Kelompok:
Aufa Azahria Purba (24523026)
Najwa Khairun Nisa (24523263)

1. Deskripsi Kasus,
Masalah yang Dihadapi: Dataset Iris memiliki 4 fitur dimensi (sepal_length, sepal_width, petal_length, petal_width). Manusia tidak dapat memvisualisasikan data dalam ruang 4 dimensi secara langsung.
Mengapa Reduksi Dimensi Dibutuhkan: Untuk memetakan data berdimensi tinggi ke dalam ruang 2D agar pola persebaran spesies bunga Iris dapat dilihat dan dianalisis secara visual.
Target Reduksi: Data direduksi menjadi 2 dimensi (2D).

2. Dataset yang Digunakan,
Nama Dataset: Iris Dataset.
Karakteristik: Terdiri dari 150 sampel dengan 4 fitur numerik dan 1 target label (3 kelas: Setosa, Versicolor, Virginica)

3. Ringkasan Metode
PCA (Principal Component Analysis): Metode linear yang mereduksi dimensi dengan memaksimalkan varians data pada sumbu baru (Principal Components).
t-SNE (t-Distributed Stochastic Neighbor Embedding): Metode non-linear yang sangat efektif untuk memvisualisasikan struktur lokal dan menjaga jarak antar titik data yang serupa dalam dimensi rendah.

4. Analisis Hasil (Naratif),
Berdasarkan visualisasi yang dihasilkan dalam Notebook:
Hasil PCA: PCA berhasil memisahkan spesies Setosa dengan sangat jelas dari kelompok lainnya. Namun, terdapat sedikit tumpang tindih (overlap) antara spesies Versicolor dan Virginica karena keterbatasan PCA sebagai metode linear dalam menangkap struktur data yang lebih kompleks.
Hasil t-SNE: t-SNE menunjukkan pembentukan cluster yang lebih solid dan terpisah secara nyata. Jarak antar kelompok terlihat lebih tegas dibandingkan hasil PCA, yang menunjukkan bahwa hubungan non-linear antar fitur pada bunga Iris berhasil dipetakan dengan baik.
Perbandingan: PCA lebih baik dalam mempertahankan struktur global data dan varians, sementara t-SNE lebih unggul dalam menunjukkan pengelompokan (clustering) yang jelas untuk keperluan visualisasi.
Kesimpulan: Untuk kasus visualisasi eksplorasi cluster pada dataset ini, t-SNE lebih sesuai karena memberikan pemisahan antar kelas yang lebih diskrit dan mudah diinterpretasikan secara visual.
