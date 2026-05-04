# 🔍 Deteksi Clickbait Judul Berita Bahasa Indonesia

Proyek ini merupakan tugas praktikum Bab 4 yang mengimplementasikan 
model **Bi-LSTM (Bidirectional Long Short-Term Memory)** dengan arsitektur 
**multi-input neural network** untuk mendeteksi clickbait pada judul 
berita berbahasa Indonesia.

## ⚠️ Catatan Penting
GitHub tidak dapat menampilkan preview file `.ipynb` secara langsung 
karena keterbatasan render untuk file notebook berukuran besar. 
Silakan gunakan link di bawah untuk melihat notebook beserta outputnya.

## 📓 Lihat Notebook
👉 **[Buka di nbviewer](https://nbviewer.org/github/Jiyad21-ui/deteksiklikbait/blob/main/tugas4.ipynb)**

👉 **[Buka di Google Colab (Recommended)](https://colab.research.google.com/drive/1Eil1CQ3lVzJ3VLGTl3Ulg4T85Ei8O7vo?usp=sharing)**

## 📊 Dataset
Dataset yang digunakan adalah **CLICK-ID** — kumpulan judul berita 
dari 12 publisher berita online Indonesia.
- Total data: 8.613 judul berita
- Clickbait: 3.316 judul
- Non-clickbait: 5.297 judul

## 🧠 Arsitektur Model
Model menggunakan 2 input sekaligus:
- **Input 1** → Teks judul berita (diproses oleh LSTM)
- **Input 2** → Fitur numerik (huruf kapital, huruf kecil, 
tanda baca, angka)

## 📈 Hasil
| Metric | Score |
|--------|-------|
| Accuracy | 87.29% |
| Precision (non-clickbait) | 90% |
| Precision (clickbait) | 84% |
| Recall (non-clickbait) | 89% |
| Recall (clickbait) | 85% |

## ⚙️ Teknologi
- Python
- TensorFlow / Keras
- NLTK
- Scikit-learn
- Pandas & NumPy
- Google Colab
