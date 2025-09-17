# Credit-Risk-Supervised-ML

## Latar Belakang Masalah
Proyek ini bertujuan untuk memprediksi status kelayakan kredit (loan status) berdasarkan data aplikasi kredit dari perusahaan multifinance. Prediksi ini penting untuk meminimalisir risiko gagal bayar dan meningkatkan efektivitas proses analisis kredit. Model klasifikasi dibangun menggunakan algoritma supervised machine learning seperti Logistic Regression dan Random Forest. Proyek ini mencakup tahapan data understanding, data preprocessing, EDA, pemodelan, serta evaluasi performa model.
Dataset: Credit Risk Dataset (data internal untuk kebutuhan proyek virtual internship ID/X Partners dan Rakamin Academy).

## Versi Pustaka yang Digunakan
- Pandas versi: 2.2.2
- Numpy versi: 2.0.2
- Matplotlib versi: 3.10.0
- Seaborn versi: 0.13.2
- Scikit-learn versi: 1.6.1

## Insight
1. Logistic Regression:

- Akurasi: 80%, AUC: 0.99
- Kuat dalam recall (96%), sehingga hampir semua nasabah berisiko terdeteksi.
- Cocok sebagai baseline model, namun precision rendah (73%), artinya masih ada salah klasifikasi pada prediksi nasabah berisiko.

2. Random Forest:

- Akurasi: 99%, Precision: 99%, Recall: 98%
- Model paling unggul karena mampu menangkap interaksi kompleks antar fitur.
- Sangat konsisten dan seimbang antara precision dan recall, sehingga cocok untuk deployment.

3. Interpretasi Logistic Regression

- Variabel seperti loan_amount, credit_score, dan number_of_loans punya koefisien terbesar.
- Menunjukkan bahwa semakin tinggi jumlah pinjaman dan jumlah pinjaman aktif, semakin besar peluang gagal bayar.

## Kesimpulan
- Logistic Regression unggul dalam recall (≈96%), efektif menangkap mayoritas nasabah berisiko, meski precision lebih rendah (≈73%).
- Random Forest memiliki performa keseluruhan terbaik: akurasi ≈99%, precision ≈99%, recall ≈98%, sehingga ideal untuk mendeteksi nasabah berisiko gagal bayar.
- Implementasi model ini dapat membantu perusahaan meminimalkan risiko kredit macet dan menjaga kualitas portofolio.

#ML #Python #CreditRisk #SupervisedLearning #DataScience

Silakan hubungi saya jika ingin berdiskusi: ghazaputra99@gmail.com
