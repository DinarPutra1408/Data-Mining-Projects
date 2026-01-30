# 🎭 Sentiment Analysis: Political Figures 2024

Folder ini berisi proyek **Natural Language Processing (NLP)** untuk menganalisis opini publik di media sosial terhadap tokoh politik menggunakan algoritma machine learning.

## 🗳️ Project: Sentiment Analysis of 2024 Presidential Candidates
Proyek ini mengklasifikasikan sentimen masyarakat (Positif, Netral, Negatif) terkait bakal calon presiden 2024 berdasarkan data teks dari YouTube.

### 📋 Key Workflow
1. **Data Crawling**: Pengambilan data komentar menggunakan YouTube Data API.
2. **Text Preprocessing**:
   - *Cleansing*: Menghapus simbol, angka, dan link.
   - *Case Folding*: Menyeragamkan huruf kecil.
   - *Tokenizing & Stemming*: Memecah kalimat menjadi kata dasar.
   - *Filtering*: Menghapus *stopwords* (kata yang tidak bermakna).
3. **Labelling**: Pemberian label sentimen menggunakan library `TextBlob` atau manual.
4. **Model Implementation**: Menggunakan algoritma **Multinomial Naïve Bayes**.
5. **Evaluation**: Pengujian akurasi menggunakan *Confusion Matrix*.

### 📊 Project Highlights
* **Subject**: Anies Baswedan, Ganjar Pranowo, & Prabowo Subianto.
* **Algorithm**: Naïve Bayes Classifier.
* **Result**: Visualisasi perbandingan sentimen antar tokoh dalam bentuk Bar Chart dan WordCloud.

### 🚀 Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-blue?style=flat)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white)
![YouTube API](https://img.shields.io/badge/YouTube_API-FF0000?style=flat&logo=youtube&logoColor=white)

---
[⬅️ Kembali ke Menu Utama](../README.md)