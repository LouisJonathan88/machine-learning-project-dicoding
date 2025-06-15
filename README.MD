# Machine Learning Project - Dicoding 

Repositori ini merupakan submission akhir untuk kelas **Membangun Proyek Machine Learning** dari Dicoding.

Project ini memuat proses end-to-end dari *unsupervised learning* (clustering) hingga *supervised learning* (klasifikasi), dimulai dari data mentah, pemrosesan, hingga pembuatan model klasifikasi berdasarkan hasil clustering.

---

## Alur Proyek

1. **Clustering** (`Clustering.ipynb`)
   - Melakukan preprocessing dataset
   - Menggunakan metode **K-Means Clustering** untuk mengelompokkan data
   - Menentukan jumlah cluster optimal dengan metode **Elbow Method**
   - Menambahkan hasil cluster sebagai fitur baru di dataset

2. **Klasifikasi** (`Klasifikasi.ipynb`)
   - Menggunakan label hasil clustering sebagai target klasifikasi
   - Membangun model klasifikasi menggunakan algoritma seperti:
     - Random Forest
     - XGBoost
   - Evaluasi model menggunakan metrik akurasi, confusion matrix, precision, recall, f1-score

---

## Teknologi & Library
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

## Cara Menjalankan
1. Clone repository:
     ```bash
   git clone https://github.com/LouisJonathan88/machine-learning-project-dicoding.git
   cd machine-learning-project-dicoding
   ```
2. Install dependensi:
- pip install pandas
- pip install numpy
- pip install scikit-learn
- pip install matplotlib
- pip insall seaborn

3. Jalankan program:
```bash
   jupyter notebook
```

