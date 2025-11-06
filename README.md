# Pertemuan-05-Lab

Menggunakan dua algoritma machine learning yang umum digunakan dalam klasifikasi data, yaitu Random Forest dan Support Vector Machine (SVM).
Tujuan dari praktikum ini adalah untuk memahami konsep dasar, proses training, evaluasi model, serta membandingkan performa kedua algoritma pada dataset yang sama.

📘 Tujuan Pembelajaran
- Memahami konsep dasar Random Forest dan Support Vector Machine.
- Menerapkan kedua algoritma menggunakan library scikit-learn.
- Melakukan evaluasi model menggunakan metrik seperti akurasi, confusion matrix, dan classification report.
- Membandingkan hasil performa antara Random Forest dan SVM.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📂 Struktur Notebook
- Import Library
  Menggunakan pustaka: pandas, numpy, matplotlib, seaborn, sklearn.
- Persiapan Data
  Memuat dataset dan melakukan eksplorasi data awal.
  Melakukan preprocessing dan pembagian dataset menjadi training dan testing set.
- Model 1 — Random Forest Classifier
  Inisialisasi dan pelatihan model menggunakan RandomForestClassifier.
  Evaluasi performa model dengan akurasi dan confusion matrix.
- Model 2 — Support Vector Machine (SVM)
  Pelatihan model dengan SVC menggunakan kernel linear dan/atau RBF.
  Evaluasi model dan perbandingan hasil.
- Visualisasi Hasil
  Menampilkan grafik performa dan perbandingan akurasi antar model.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
⚙️ Teknologi yang Digunakan
- Python 3.x
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📊 Hasil & Analisis
- Model Random Forest umumnya menunjukkan performa yang lebih stabil dan akurat, terutama pada data yang kompleks dan non-linear.
- SVM memiliki keunggulan dalam pemisahan data yang jelas, tetapi sensitif terhadap skala data dan parameter kernel.
- Evaluasi dilakukan dengan menggunakan metrik:
  Accuracy Score
  Confusion Matrix
  Classification Report (Precision, Recall, F1-score)
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📈 Kesimpulan
Kedua algoritma memiliki kelebihan masing-masing:
- Random Forest: lebih tangguh terhadap overfitting dan mudah digunakan tanpa banyak tuning.
- SVM: memberikan hasil sangat baik pada dataset dengan batas pemisah yang jelas.
Dengan memahami keduanya, kita dapat memilih model yang paling sesuai tergantung pada jenis dan karakteristik dataset yang digunakan.
