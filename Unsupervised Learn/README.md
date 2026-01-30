# 🔍 Unsupervised Learning: Clustering Project

Folder ini berisi implementasi teknik pembelajaran mesin tanpa pengawasan untuk menemukan pola tersembunyi dalam data.

## 🛍️ Project: Customer Segmentation Analysis (K-Means)
Proyek ini bertujuan untuk mengelompokkan pelanggan berdasarkan kemiripan karakteristik untuk membantu strategi pemasaran (marketing strategy).

### 📊 Dataset Overview
Analisis dilakukan pada dataset pelanggan yang mencakup fitur utama:
* **Gender**: Jenis kelamin pelanggan.
* **Age**: Usia pelanggan.
* **Annual Income**: Pendapatan tahunan.
* **Spending Score**: Skor pengeluaran yang ditentukan berdasarkan perilaku konsumen.

### ⚙️ Workflow & Methodology
1. **Exploratory Data Analysis (EDA)**: Menganalisis korelasi antar fitur (seperti hubungan Age vs Spending Score).
2. **Feature Engineering**: Melakukan *Label Encoding* pada data kategorikal (Gender) agar bisa diproses algoritma.
3. **Elbow Method**: Menentukan jumlah klaster ($k$) yang paling optimal.
4. **K-Means Clustering**: Mengelompokkan data ke dalam beberapa klaster berdasarkan jarak *Euclidean*.
5. **Visualization**: Menampilkan hasil segmentasi dalam bentuk *scatter plot*.

### 🚀 Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=flat&logo=Matplotlib&logoColor=black)

---
[⬅️ Kembali ke Menu Utama](../README.md)