# Credit-Risk-Supervised-ML

## Latar Belakang Masalah
Proyek ini bertujuan untuk memprediksi status kelayakan kredit (loan status) berdasarkan data aplikasi kredit dari perusahaan multifinance. Prediksi ini penting untuk meminimalisir risiko gagal bayar dan meningkatkan efektivitas proses analisis kredit. Model klasifikasi dibangun menggunakan algoritma supervised machine learning seperti Logistic Regression dan Random Forest. Proyek ini mencakup tahapan data understanding, data preprocessing, EDA, pemodelan, serta evaluasi performa model.
Dataset: Credit Risk Dataset (data internal untuk kebutuhan proyek virtual internship ID/X Partners dan Rakamin Academy).

## Versi Pustaka yang Digunakan
Pandas versi: 2.2.2
Numpy versi: 2.0.2
Matplotlib versi: 3.10.0
Seaborn versi: 0.13.2
Scikit-learn versi: 1.6.1

## Insight
1. Logistic Regression:

Akurasi model mencapai 0.79, dengan kelebihan pada interpretabilitas dan efisiensi. Cocok untuk baseline model dan analisis faktor risiko, namun sedikit kurang dalam menangkap kompleksitas data non-linear.
2. Random Forest:

Memberikan performa terbaik dengan akurasi 0.86. Model ini sangat kuat dalam menangkap interaksi kompleks antar fitur dan memiliki nilai recall tinggi pada kelas ‘Bad’ yang penting dalam deteksi risiko kredit.
3. Fitur Penting (Feature Importance):
    - number_of_loans
    - annual_income
    - credit_score
    - loan_amount
    - term
   
   Fitur-fitur ini sangat berkontribusi dalam membedakan antara nasabah berisiko tinggi dan rendah.
4. Koefisien LR:

Pada model Logistic Regression, number_of_loans, loan_amount, dan credit_score memiliki bobot koefisien tertinggi, menunjukkan pengaruh langsung terhadap probabilitas gagal bayar.

## Kesimpulan
Model Random Forest direkomendasikan karena memberikan performa terbaik dalam mendeteksi risiko kredit dengan akurasi dan recall yang tinggi. Logistic Regression tetap relevan karena hasilnya cukup baik dan memberikan interpretasi fitur yang jelas, cocok untuk analisis dan regulasi. Kedua model menunjukkan bahwa fitur finansial seperti jumlah pinjaman dan skor kredit sangat menentukan dalam klasifikasi risiko. Proyek ini menunjukkan bagaimana pendekatan supervised learning dapat digunakan secara efektif untuk pengambilan keputusan dalam bidang keuangan.

#ML #Python #CreditRisk #SupervisedLearning #DataScience

Silakan hubungi saya jika ingin berdiskusi: ghazaputra99@gmail.com
