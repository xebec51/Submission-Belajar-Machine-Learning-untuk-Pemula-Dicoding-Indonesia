# Submission Proyek Machine Learning untuk Pemula

**Repository ini berisi submission proyek akhir kelas Machine Learning untuk Pemula di Dicoding Indonesia.**

---

## 📚 **Deskripsi Proyek**

Proyek ini bertujuan untuk mengaplikasikan konsep supervised learning dan unsupervised learning dalam membangun model machine learning. Berikut adalah langkah-langkah yang dilakukan dalam proyek ini:

### **1. Clustering (Unsupervised Learning)**
- **Algoritma:** Gaussian Mixture Model (GMM)
- **Evaluasi:** Silhouette Score sebesar 0.661
- **Hasil:** Dataset tanpa label berhasil dikelompokkan ke dalam 4 cluster berdasarkan pola seperti distribusi biaya, metode pembayaran, dan jenis pelanggan.
- **Interpretasi:** Cluster dianalisis menggunakan data asli untuk memberikan wawasan tentang karakteristik utama masing-masing cluster.

### **2. Klasifikasi (Supervised Learning)**
- **Algoritma:**
  - Logistic Regression
  - Random Forest
- **Evaluasi:**
  - Akurasi dan F1-Score mencapai 100% pada training dan testing set.
  - Confusion matrix menunjukkan model berhasil memprediksi seluruh data dengan benar tanpa kesalahan.
- **Hasil:** Model berhasil memprediksi cluster berdasarkan fitur yang tersedia.

---

## 📁 **Struktur Repository**

- **Clustering_Submission_Akhir_BMLP_Muh. Rinaldi Ruslan.ipynb**: Notebook Python untuk proses clustering.
  - **Fitur Utama:**
    - Preprocessing data tanpa mengubah data asli.
    - Clustering menggunakan Gaussian Mixture Model.
    - Evaluasi menggunakan Silhouette Score.
    - Visualisasi pola dalam data dengan grafik.
    - Interpretasi mendalam untuk setiap cluster.
- **Klasifikasi_Submission_Akhir_BMLP_Muh. Rinaldi Ruslan.ipynb**: Notebook Python untuk proses klasifikasi.
  - **Fitur Utama:**
    - Pembagian data menjadi training dan testing set.
    - Pelatihan model Logistic Regression dan Random Forest.
    - Evaluasi dengan metrik akurasi, F1-Score, dan confusion matrix.
    - Visualisasi hasil prediksi.
- **Hasil_Clustering_Final.csv**: Dataset hasil clustering yang digunakan sebagai input untuk klasifikasi.
- **Hasil_Klasifikasi_Final.csv**: Dataset hasil prediksi klasifikasi, memuat label prediksi untuk data uji.
- **Retail_Transactions_Dataset.csv**: Dataset awal tanpa label.

---

## 📂 **Referensi Dataset**

- **Dataset Awal**:
  - [Retail Transactions Dataset](https://www.kaggle.com/datasets/prasad22/retail-transactions-dataset)

---

## 📊 **Evaluasi Model**

### **Clustering**
- **Algoritma:** Gaussian Mixture Model (GMM)
- **Jumlah Cluster:** 4
- **Silhouette Score:** 0.661

### **Klasifikasi**
- **Model:**
  - Logistic Regression
  - Random Forest
- **Akurasi dan F1-Score:**
  - Logistic Regression: 100% pada training dan testing set.
  - Random Forest: 100% pada training dan testing set.
- **Confusion Matrix:**
  - Logistic Regression dan Random Forest berhasil memprediksi semua data dengan benar tanpa kesalahan.

---

## ✨ **Kontributor**
- **Muh. Rinaldi Ruslan**
  - Email: rinaldi.ruslan51@gmail.com
  - LinkedIn: [Rinaldi Ruslan](https://www.linkedin.com/in/rinaldiruslan/)
  - Instagram: [@rinaldiruslan](https://www.instagram.com/rinaldiruslan/)
  - Dicoding ID: rinaldi51

---

## 🛠️ **Catatan**
Jika file besar seperti `Hasil_Clustering_Final.csv` dan `Retail_Transactions_Dataset.csv` tidak terunduh secara otomatis, pastikan Anda telah menginstal Git LFS:
```bash
git lfs install
git lfs pull
