# 📊 Data Science & Machine Learning Explorations

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Status](https://img.shields.io/badge/Status-Active-success.svg)]()

Selamat datang di repositori kolaboratif **Muhammad Arsyad Setiawan** dan **Candra Andika Putra**. 

Repositori ini difungsikan sebagai ruang kerja utama untuk tugas, workshop, dan eksperimen terkait *Data Science* dan *Machine Learning*. Fokus utama dari pembelajaran saat ini mencakup Eksplorasi Data (EDA), prapemrosesan data, hingga implementasi model *machine learning* menggunakan dataset dunia nyata.

---

## 🎯 Objektif Proyek

1. **Week 1:** Menentukan dataset dan nilai bisnisnya.
2. **Week 2:** Melakukan *Exploratory Data Analysis* (EDA) untuk menemukan pola dan *insight* tersembunyi.
3. **Week 3:** Melakukan *preprocessing*, *feature engineering*, dan *model training* untuk memprediksi tingkat *burnout*.
4. **Week 4:** Memperbaiki model dan mengoptimalkasi performa model untuk melakukan *final pitching*.

---

## 📁 Struktur Repositori

Struktur folder telah dirapikan agar lebih modular, di mana seluruh skrip analisis dikelompokkan ke dalam `notebook/` dan aset data dipindahkan ke `data/`.

```text
📦 10-MuhammadArsyadSetiawan-CandraAndikaPutra
 ┣ 📂 Week_1
 ┃ ┗ 📜 ai_worker_burnout_attrition_2026.csv
 ┣ 📂 notebook
 ┃ ┣ 📂 Week_2
 ┃ ┃ ┗ 📜 DS-Kel10-Week2.ipynb
 ┃ ┃ ┗ 📜 FindDataset.ipynb
 ┃ ┣ 📂 Week_3
 ┃ ┃ ┣ 📂 DS-AI-Week3-BestModels
 ┃ ┃ ┗ 📂 DS-AI-Week3-Notebook
 ┃ ┣ 📂 Week_4
 ┃ ┃ ┣ 📂 DS-AI-Week4-BestModels
 ┃ ┃ ┗ 📂 DS-AI-Week4-Notebook
 ┃ ┗ 📂 WorkShop1
 ┃ ┃ ┗ 📜 10_MuhammadArsyadSetiawan.ipynb
 ┃ ┃ ┗ 📜 BankCampaignClassification_CandraAndikaPutra.ipynb
 ┣ 📜 .gitignore
 ┣ 📜 requirements.txt
 ┗ 📜 README.md

## 🗄️ Tentang Dataset

Repositori ini menggunakan dataset **`ai_worker_burnout_attrition_2026.csv`**. 
Dataset ini berisi metrik dan fitur yang relevan untuk menganalisis dan memprediksi tingkat kelelahan (*burnout*) serta kemungkinan pengunduran diri (*attrition*) pada profesional di bidang *Artificial Intelligence*.

**Tugas yang umum dilakukan pada dataset ini:**
- Pembersihan data (penanganan *missing values* & *outliers*).
- Visualisasi distribusi fitur.
- Pembuatan model klasifikasi atau regresi untuk memprediksi tingkat *burnout*.

---

## 🛠️ Teknologi & Library

Proyek-proyek di dalam repositori ini dibangun menggunakan ekosistem Data Science Python standar:
- **Bahasa Pemrograman:** Python 3.x
- **Environment:** Jupyter Notebook / JupyterLab
- **Data Manipulation:** `pandas`, `numpy`
- **Data Visualization:** `matplotlib`, `seaborn`
- **Machine Learning & Optimization:** `scikit-learn`, `xgboost`, `catboost`, `lightgbm`, `optuna`, `shap`, `imbalanced-learn`

---

## 🚀 Cara Menjalankan Repositori Secara Lokal

Untuk mencoba *notebook* yang ada di dalam repositori ini di perangkat lokal kamu, ikuti langkah-langkah berikut:

### 1. Clone Repositori
Buka terminal dan jalankan perintah:
```bash
git clone https://github.com/noctican/10-MuhammadArsyadSetiawan-CandraAndikaPutra.git

cd 10-MuhammadArsyadSetiawan-CandraAndikaPutra
```

### 2. Siapkan Virtual Environment
Sangat direkomendasikan menggunakan *virtual environment* agar dependensi sistem tidak terganggu.

```bash
# Membuat virtual environment bernama 'env'
python -m venv env

# Mengaktifkan environment (Untuk pengguna Linux / MacOS)
source env/bin/activate

# Mengaktifkan environment (Untuk pengguna Windows / Command Prompt)
env\Scripts\activate
```

### 3. Instalasi Dependensi
Pastikan kamu menginstal *library* yang dipakai dengan menjalankan perintah:

```bash
pip install -r requirements.txt
```

### 4. Jalankan Jupyter Notebook
Masuk ke dalam direktori *notebook* dan jalankan Jupyter:
```bash
cd notebook
jupyter notebook
```
*Browser* akan otomatis terbuka. Kamu tinggal menavigasikan ke folder `Week_2`, `Week_3`, atau `WorkShop1` untuk membuka file `.ipynb`.

---

## 👥 Kontributor

Repositori ini dikelola dan dikembangkan oleh:
* **[Muhammad Arsyad Setiawan](https://github.com/arsyad429)**
* **[Candra Andika Putra](https://github.com/noctican)**
---
*Dibuat dengan ❤️ dan rasa penasaran yang tinggi terhadap Data Science  ^_^.*
