# Prediksi Karyawan Mengundurkan Diri

Proyek ini bertujuan untuk memprediksi kemungkinan seorang karyawan mengundurkan diri berdasarkan beberapa variabel seperti jam kerja dan usia. Model prediktif ini dibangun menggunakan Python dan pustaka machine learning dari `scikit-learn`.

## Informasi Umum

- **Nama**: Marsell Stefen Lontaan  
- **NIM**: 202201022  
- **Kelas**: A  
- **Dataset**: Dummy   
- **Tujuan**: Memprediksi pengunduran diri karyawan  
- **Sumber Data**: Dibuat secara dummy untuk keperluan proyek pembelajaran

## Teknologi yang Digunakan

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Langkah-langkah Analisis

1. **Import Library**  
   Notebook ini memuat berbagai library penting seperti:
   ```python
   import pandas as pd
   import numpy as np
   from sklearn.preprocessing import LabelEncoder, StandardScaler
   from sklearn.model_selection import train_test_split
   from sklearn.naive_bayes import GaussianNB
   from sklearn.metrics import confusion_matrix, accuracy_score
   import matplotlib.pyplot as plt
