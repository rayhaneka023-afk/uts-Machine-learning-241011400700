# UTS Machine Learning

Implementasi algoritma **Linear Regression** dan **Logistic Regression** secara manual menggunakan NumPy, Pandas, dan Matplotlib.

## Identitas Mahasiswa

- **Nama:** Rayhan Eka Putra
- **NIM:** 241011400700
- **Kelas:** Sesuaikan dengan kelas masing-masing

## Library yang Digunakan

- **NumPy:** Perhitungan numerik, implementasi model, pembagian data, dan perhitungan metrik.
- **Pandas:** Membaca dan mengolah dataset CSV.
- **Matplotlib:** Membuat grafik dan visualisasi hasil.
  Scikit-learn tidak digunakan untuk model dan metrik utama. Library tersebut hanya digunakan pada bagian bonus untuk membandingkan hasil implementasi manual.

## A. Linear Regression

Linear Regression digunakan untuk memprediksi nilai numerik berdasarkan hubungan antara variabel input dan target.

Implementasi meliputi:

- Pembagian data training dan testing menggunakan NumPy.
- Model Linear Regression menggunakan metode Normal Equation.
- Model Linear Regression menggunakan Gradient Descent.
- Evaluasi menggunakan MAE, MSE, RMSE, dan R².
- Visualisasi hasil serta contoh prediksi.

## B. Logistic Regression

Logistic Regression digunakan untuk mengklasifikasikan email menjadi spam dan bukan spam.

Implementasi meliputi:

- Pembagian data training dan testing.
- Pelatihan model menggunakan Gradient Descent.
- Penggunaan fungsi sigmoid untuk menghitung probabilitas.
- Evaluasi menggunakan accuracy, precision, recall, F1-score, dan confusion matrix.
- Visualisasi dan pengujian prediksi email.

## Implementasi Manual

Model dan metrik utama dibuat menggunakan NumPy, meliputi:

- `train_test_split`
- `LinearRegression`
- `LinearRegressionGD`
- `LogisticRegression`
- `regression_metrics`
- `confusion_matrix`
- `accuracy_score`
- `classification_metrics`

## Ringkasan Hasil

Notebook menampilkan hasil evaluasi model regresi dan klasifikasi, visualisasi, serta contoh prediksi. Nilai metrik digunakan untuk mengevaluasi performa model pada data pengujian.
Hasil numerik dapat dilihat pada output notebook setelah semua sel berhasil dijalankan.
