# Submission Kelas Belajat Pengembangan Machine Learning - Sentiment Analysis

Proyek Sentiment Analysis dari modul "Belajar Pengembangan Machine Learning (BPML)" pada kelas Dicoding program Coding Camp 2025 powered by DBS Foundation 

Repositori ini berisi implementasi analisis sentimen pada data teks menggunakan model Deep Learning (LSTM, CNN, dan GRU).

## 📌 Gambaran Projek
- **Tujuan**: Membandingkan performa tiga arsitektur neural network (LSTM, CNN, GRU) untuk klasifikasi sentimen.
- **Label Sentimen**: `positive`, `negative`, `neutral`.

## 🛠 Teknologi & Library
- TensorFlow/Keras
- NLTK untuk text preprocessing
- Pandas untuk manipulasi data
- Scikit-learn untuk evaluasi model

## 📂 Struktur Repositori
```
/submissionBPML-analisis-sentimen
├── data/                                      # Folder dataset
├── models/                                    # Model terlatih (LSTM, CNN, GRU)
├── notebook_model_analisis_sentimen.ipynb     # Script notebook pelatihan model
├── notebook_model_analisis_sentimen.py        # Script notebook pelatihan model
├── notebook_scraping_analisis_sentimen.ipynb  # Script notebook scraping
└── requirements.txt                           # Dependensi projek
```

## 🔧 Cara Menjalankan
1. Clone repositori:
   ```bash
   git clone https://github.com/Fatikhaaa/submissionBPML-analisis-sentimen.git
   ```
2. Install dependensi:
   ```bash
   pip install -r requirements.txt
   ```
3. Jalankan notebook eksperimen atau script pelatihan.

## 📊 Hasil Evaluasi
| Model  | Accuracy (Train) | Accuracy (Test) |
|--------|------------------|-----------------|
| LSTM   | 95.06%           | 93.53%          |
| CNN    | 94.95%           | 93.00%          |
| GRU    | 92.46%           | 93.00%          |
