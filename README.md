# Submission Proyek Machine Learning untuk Pemula

**Repository ini berisi submission proyek akhir kelas Machine Learning untuk Pemula di Dicoding Indonesia.**

---

## 📚 **Deskripsi Proyek**

Proyek ini bertujuan untuk mengaplikasikan konsep supervised learning dan unsupervised learning dalam membangun model machine learning. Berikut adalah langkah-langkah yang dilakukan dalam proyek ini:

1. **Clustering (Unsupervised Learning):**
   - Dataset tanpa label dikelompokkan menggunakan algoritma Gaussian Mixture Model (GMM).
   - Evaluasi dilakukan menggunakan Silhouette Score.
   - Interpretasi cluster memberikan wawasan tentang pola dalam data, seperti distribusi biaya, metode pembayaran, dan jenis pelanggan.

2. **Klasifikasi (Supervised Learning):**
   - Dataset yang telah diberi label dari hasil clustering digunakan untuk membangun model klasifikasi.
   - Model klasifikasi dilatih menggunakan Logistic Regression dan Random Forest.
   - Evaluasi model mencakup metrik Accuracy, F1-Score, dan Confusion Matrix.

---

## 📁 **Struktur Repository**

- **Clustering_Submission_Akhir_BMLP_Muh. Rinaldi Ruslan.ipynb**: Notebook Python untuk proses clustering.
- **Klasifikasi_Submission_Akhir_BMLP_Muh. Rinaldi Ruslan.ipynb**: Notebook Python untuk proses klasifikasi.
- **Hasil_Clustering_Final.csv**: Dataset hasil proses clustering, digunakan sebagai input untuk klasifikasi.
- **Hasil_Klasifikasi_Final.csv**: Dataset hasil prediksi klasifikasi, memuat label prediksi untuk data uji.
- **Retail_Transactions_Dataset.csv**: Dataset awal tanpa label.

---

## 🔗 **Link Submission**
- Repository GitHub: [Submission Machine Learning Pemula](https://github.com/xebec51/Submission-Belajar-Machine-Learning-untuk-Pemula-Dicoding-Indonesia.git)

---

## ⚙️ **Cara Menggunakan Repository**

1. Clone repository:
   ```bash
   git clone https://github.com/xebec51/Submission-Belajar-Machine-Learning-untuk-Pemula-Dicoding-Indonesia.git
2. Pastikan Anda menginstal dependensi yang diperlukan:
   - Python 3.x
   - Jupyter Notebook
   - Library: pandas, numpy, matplotlib, seaborn, scikit-learn

3. Jalankan notebook:
   - Mulai dengan `Clustering_Submission_Akhir_BMLP_Muh. Rinaldi Ruslan.ipynb` untuk proses clustering.
   - Lanjutkan dengan `Klasifikasi_Submission_Akhir_BMLP_Muh. Rinaldi Ruslan.ipynb` untuk proses klasifikasi.

---

## 📊 **Evaluasi Model**

### **Clustering**
- **Algoritma**: Gaussian Mixture Model (GMM)
- **Jumlah Cluster**: 4
- **Silhouette Score**: 0.661

### **Klasifikasi**
- **Model**:
  - Logistic Regression
  - Random Forest
- **Akurasi dan F1-Score**:
  - Logistic Regression: 100% pada training dan testing set
  - Random Forest: 100% pada training dan testing set
- **Confusion Matrix**:
  - Logistic Regression dan Random Forest berhasil memprediksi semua data dengan benar tanpa kesalahan.

---

## 📂 **Referensi Dataset**

- **Dataset Awal**:
  - [Retail Transactions Dataset](https://www.kaggle.com/datasets/prasad22/retail-transactions-dataset)

---

## ✨ **Kontributor**
- **Muh. Rinaldi Ruslan**
  - Email: rinaldi.ruslan51@gmail.com
  - LinkedIn: [Rinaldi Ruslan](https://www.linkedin.com/in/rinaldiruslan/)
  - Dicoding ID: rinaldi51

---

## 🛠️ **Catatan**
Jika file besar seperti `Hasil_Clustering_Final.csv` dan `Retail_Transactions_Dataset.csv` tidak terunduh secara otomatis, pastikan Anda telah menginstal Git LFS:
```bash
git lfs install
git lfs pull
