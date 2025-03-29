# README: Clustering dan Klasifikasi

## Deskripsi Proyek
Proyek ini bertujuan untuk melakukan analisis clustering dan klasifikasi pada dataset yang memiliki lebih dari 2500 baris. Clustering dilakukan dengan mempertimbangkan fitur numerik dan kategorikal yang telah diolah menggunakan teknik One-Hot Encoding. Selain itu, dua algoritma klasifikasi diterapkan untuk membandingkan performa model.

## Detail Dataset
- **Sumber Dataset**: [Beverage Sales Dataset](https://www.kaggle.com/datasets/sebastianwillmann/beverage-sales)
- Jumlah sampel: **300000 baris**
- Fitur yang digunakan:
  - **Fitur numerik**: Termasuk variabel kuantitatif untuk analisis.
  - **Fitur kategorikal**: Dikodekan menggunakan **One-Hot Encoding** untuk kompatibilitas dengan model machine learning.

## Clustering
- Dilakukan feature selection untuk meningkatkan efektivitas clustering.
- **Silhouette Score** setelah feature selection tetap **di atas 0.70**, menunjukkan kualitas pemisahan cluster yang baik.

## Klasifikasi
- Menggunakan dua algoritma klasifikasi:
  - **Random Forest**
  - **Naive Bayes**
- Evaluasi model:
  - **Akurasi & F1-Score pada testing set > 92%**, menunjukkan performa model yang baik.



## Kesimpulan
Proyek ini berhasil memenuhi kriteria evaluasi dengan hasil yang memuaskan. Clustering dilakukan dengan baik berdasarkan **Silhouette Score**, dan model klasifikasi menunjukkan performa optimal dengan akurasi dan F1-Score yang tinggi.

