# Proyek Klasifikasi Gambar

- Course: **Belajar Fundamental Deep Learning**

Dataset  Animal kaggle (https://www.kaggle.com/datasets/shiv28/animal-5-mammal).


# 📘 Panduan Singkat Menjalankan Notebook.ipynb  
## Proyek Klasifikasi Gambar (MobileNetV2)

## 🔹 Deskripsi
Notebook ini berisi proyek klasifikasi gambar menggunakan **Transfer Learning (MobileNetV2)** pada dataset *Animal-5-Mammal*.  
Model dilatih, dievaluasi, lalu dikonversi ke format deployment (SavedModel, TFLite, TFJS).

---

## 🛠 1. Persiapan Environment

Install library yang dibutuhkan:

```bash
pip install tensorflow tensorflowjs kagglehub gdown matplotlib numpy pandas pillow scikit-learn



## Catatan
- Semua preprocessing dan augmentasi hanya diterapkan pada train set untuk menghindari kebocoran informasi ke validation/test set.
- File `requirements.txt` sudah disediakan untuk menginstal library yang diperlukan.


dataset/
 ├── cat/
 ├── dog/
 ├── elephant/
 ├── horse/
 └── lion/
# Proyek-Klasifikasi-Gambar
