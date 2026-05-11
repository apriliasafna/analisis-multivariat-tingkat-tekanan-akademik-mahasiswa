# **Analisis Multivariat Tekanan Akademik Mahasiswa**

## **Deskripsi**
Proyek ini menganalisis faktor-faktor yang memengaruhi tekanan akademik mahasiswa menggunakan pendekatan analisis multivariat, yang mencakup Linear Discriminant Analysis (LDA), Random Forest, dan Regresi Ordinal (Proportional Odds Model).

## **Dataset**
Dataset yang digunakan adalah Student Depression Dataset yang terdiri dari variabel demografi, akademik, gaya hidup, dan kondisi finansial mahasiswa. (https://www.kaggle.com/datasets/hopesb/student-depression-dataset) 

## **Tujuan**
Mengidentifikasi faktor utama yang memengaruhi tekanan akademik mahasiswa
Membandingkan performa model klasifikasi (LDA vs Random Forest)
Menganalisis hubungan variabel menggunakan regresi ordinal
Memberikan interpretasi berbasis data terhadap tekanan akademik

## **Metode**
Data preprocessing (missing value & outlier handling)
Uji asumsi multivariat
Uji Kelayakan
Linear Discriminant Analysis (LDA)
Random Forest Classification
Ordinal Logistic Regression
Evaluasi model (accuracy, confusion matrix, error rate)

## **Hasil Analisis**
Random Forest memiliki performa klasifikasi lebih baik dibanding LDA
Kedua model klasifikasi masih menunjukkan error cukup tinggi karena kemiripan antar kelas
Regresi Ordinal memberikan interpretasi paling jelas terhadap hubungan variabel

## **Insight Utama**
Financial Stress merupakan faktor paling dominan terhadap tekanan akademik
Study Satisfaction dan Sleep Quality juga berpengaruh signifikan
CGPA cenderung berperan sebagai faktor pelindung terhadap tekanan akademik

## **Tools**
R Programming
Libraries: MASS, caret, randomForest, VGAM, ggplot2, dll

## **Author**
Aprilia Safna Anggraeni (24031554003)
Khairun Nisa’ (24031554043)
Naufal Muzaki (24031554061)
