# README: Clustering dan Klasifikasi

## Deskripsi Proyek
Proyek ini bertujuan untuk melakukan analisis clustering dan klasifikasi pada dataset yang memiliki lebih dari 2500 baris. Clustering dilakukan dengan mempertimbangkan fitur numerik dan kategorikal yang telah diolah menggunakan teknik One-Hot Encoding. Selain itu, dua algoritma klasifikasi diterapkan untuk membandingkan performa model.

## Detail Dataset
- **Sumber Dataset**: [Beverage Sales Dataset](https://www.kaggle.com/datasets/sebastianwillmann/beverage-sales)
- Jumlah sampel: **8682 baris**
- Fitur yang digunakan:
  - **Fitur numerik**: Termasuk variabel kuantitatif untuk analisis.
  - **Fitur kategorikal**: Dikodekan menggunakan **One-Hot Encoding** untuk kompatibilitas dengan model machine learning.
- **Path Dataset:**
  - **VS Code**: `df = pd.read_csv('synthetic_beverage_sales_data.csv')  # Gantilah dengan jalur file yang benar`
  - **Google Colab**: `data = pd.read_csv('/content/synthetic_beverage_sales_data.csv')`

## Clustering
- Dilakukan feature selection untuk meningkatkan efektivitas clustering.
- **Silhouette Score** setelah feature selection tetap **di atas 0.70**, menunjukkan kualitas pemisahan cluster yang baik.

## Klasifikasi
- Menggunakan dua algoritma klasifikasi:
  - **Random Forest**
  - **Naive Bayes**
- Evaluasi model:
  - **Akurasi & F1-Score pada testing set > 92%**, menunjukkan performa model yang baik.

## Implementasi
- **VS Code** digunakan untuk pengolahan data dengan nama file:
  - `[Klasifikasi]_Submission_Akhir_BMLP_Krismono_Sadi_(Updated).ipynb`
  - `[Clustering]_Submission_Akhir_BMLP_Krismono_Sadi_(Updated).ipynb`
- **Google Colab** digunakan untuk pengolahan data dengan nama file:
  - `VS CODE [Klasifikasi]_Submission_Akhir_BMLP_Krismono_Sadi_(Updated).ipynb`
  - `VS CODE [Clustering]_Submission_Akhir_BMLP_Krismono_Sadi_(Updated).ipynb`

## Kesimpulan
Proyek ini berhasil memenuhi kriteria evaluasi dengan hasil yang memuaskan. Clustering dilakukan dengan baik berdasarkan **Silhouette Score**, dan model klasifikasi menunjukkan performa optimal dengan akurasi dan F1-Score yang tinggi.

