# heart-disease-prediction-naive-bayes
Implementasi model klasifikasi penyakit jantung menggunakan algoritma Naive Bayes. Dibuat sebagai Tugas UAS mata kuliah Data Mining, Program Studi Teknologi Informasi.
# Prediksi Penyakit Jantung Menggunakan Algoritma Naive Bayes  
_Project UAS Mata Kuliah Data Mining_

## Deskripsi Proyek  
Repository ini berisi implementasi model Machine Learning untuk melakukan **prediksi penyakit jantung (Heart Disease Prediction)** menggunakan **algoritma Naive Bayes**.  
Proyek ini merupakan bagian dari **Tugas Ujian Akhir Semester (UAS)** pada mata kuliah **Data Mining** Program Studi Teknologi Informasi.

Dataset yang digunakan adalah **Heart Disease UCI Dataset** dari Kaggle(https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data), yang terdiri dari 14 atribut klinis seperti usia, tekanan darah, kolesterol, detak jantung maksimum, dan lain-lain. Tujuan dari proyek ini adalah membuat model klasifikasi yang dapat memprediksi apakah seorang pasien berpotensi mengalami penyakit jantung berdasarkan fitur-fitur tersebut.

## Tujuan Proyek
- Melakukan eksplorasi dan pembersihan data.
- Menerapkan algoritma Naive Bayes untuk klasifikasi penyakit jantung.
- Menghasilkan metrik evaluasi seperti:
  - Accuracy  
  - Precision  
  - Recall  
  - F1-Score  
  - Confusion Matrix  

## Dataset
Dataset: **Heart Disease UCI (Kaggle)**  
Link: https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data

Dataset ini merupakan dataset multivariat dengan 14 fitur utama dan satu label target (`target`) yang menunjukkan ada/tidaknya penyakit jantung.

## Algoritma yang Digunakan
Model klasifikasi menggunakan:

### **Naive Bayes (GaussianNB)**
Dipilih karena:
- Sederhana dan cepat.
- Cocok untuk dataset dengan fitur numerik.
- Performa stabil untuk data medis.

## Hasil Evaluasi
Beberapa hasil model:

- **Accuracy:** 0.85  
- **Precision:** 0.91  
- **Recall:** 0.75  
- **F1-Score:** 0.82  
- Confusion Matrix dan visualisasi lainnya tersedia di folder `/images`.

## Anggota Kelompok
1. **[Muhammad Rifal – 2205903040109]**
2. **[Hendra farizal – 2205903040116]**

## Catatan
Proyek ini dibuat sebagai bagian dari **Ujian Akhir Semester (UAS)** mata kuliah **Data Mining**, Program Studi Teknologi Informasi.
