# Sistem Prediksi Kematangan Buah Apel Menggunakan Convolutional Neural Network (CNN)

Proyek ini berfokus pada prediksi tingkat kematangan buah apel menggunakan
Pengolahan Citra Digital dan metode Convolutional Neural Network (CNN).
Sistem ini mengklasifikasikan citra buah apel ke dalam tiga kategori, yaitu:
Belum Matang (Unripe), Matang (Ripe), dan Terlalu Matang (Overripe).
Proyek ini dikembangkan sebagai tugas akhir pada mata kuliah
Pengolahan Citra Digital
## 📌 Tujuan Proyek
- Membangun sistem otomatis untuk memprediksi kematangan buah apel berdasarkan citra
- Menerapkan teknik preprocessing citra
- Mengimplementasikan metode CNN dengan pendekatan transfer learning
- Mengevaluasi kinerja model menggunakan akurasi dan confusion matrix
## 📂 Dataset
Dataset yang digunakan terdiri dari citra buah apel yang dibagi ke dalam tiga kelas:
- Unripe (buah apel belum matang)
- Ripe (buah apel matang)
- Overripe (buah apel terlalu matang)
Setiap kelas disimpan dalam folder terpisah.
Sumber dataset diperoleh dari dataset publik Kaggle:
https://www.kaggle.com/datasets/asadullahprl/fruits-ripeness-classification-dataset/code

> ⚠️ Dataset tidak diunggah langsung ke repository ini karena keterbatasan ukuran

## 🧠 Metodologi
Metodologi yang digunakan dalam proyek ini meliputi:
1. Preprocessing citra (resize dan normalisasi)
2. Image augmentation untuk meningkatkan variasi data
3. Implementasi model CNN menggunakan transfer learning
4. Proses pelatihan dan validasi model
5. Evaluasi model menggunakan confusion matrix dan nilai akurasi

## 🛠 Teknologi yang Digunakan
- Python
- TensorFlow / Keras
- NumPy
- OpenCV
- Matplotlib
- Scikit-learn
## 📊 Evaluasi Model
Kinerja model dievaluasi menggunakan beberapa metrik, antara lain:
- Akurasi
- Confusion Matrix
- Precision dan Recall
Hasil evaluasi menunjukkan bahwa model CNN mampu mengklasifikasikan
tingkat kematangan buah apel dengan performa yang baik.
## 👥 Authors
Fayzar Gymnastiar  
Kelompok 1  
Pengolahan Citra Digital
