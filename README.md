# Script Analisis Sentimen Komentar YouTube terhadap Fitur Pendaftaran Pelayanan Mobile JKN dengan SVM
Repository ini berisi implementasi analisis sentimen komentar YouTube terhadap fitur pendaftaran pelayanan pada aplikasi Mobile JKN menggunakan metode **Support Vector Machine (SVM)**.
Repository ini menyediakan script utama, kamus normalisasi, daftar stopword Bahasa Indonesia, contoh format dataset, serta panduan pemilihan komentar dan proses anotasi sentimen. Apabila ingin menggunakan data sendiri, proses pengambilan komentar agar tetap sesuai dengan topik penelitian disarankan mengikuti **Panduan Pemilihan Komentar dan Anotasi.pdf** yang telah disediakan pada repository ini.

---

## Isi Repository

| File | Deskripsi |
|------|-----------|
| `Analisis_Sentimen_Komentar_Pengguna_Platform_YouTube_...ipynb` | Notebook utama yang berisi seluruh proses analisis sentimen, mulai dari membaca data, preprocessing, ekstraksi fitur TF-IDF, pelatihan model SVM, hingga evaluasi model. |
| `kamus_normalisasi.csv` | Kamus normalisasi kata tidak baku menjadi kata baku yang digunakan pada tahap preprocessing teks. |
| `stopwords-id.txt` | Daftar stopword Bahasa Indonesia yang digunakan untuk menghapus kata-kata umum yang tidak memiliki makna sentimen. |
| `Contoh format kolom label dan content untuk ....` | Contoh format dataset (`commentsdata_svm.csv`) yang dapat digunakan sebagai acuan apabila ingin menjalankan script menggunakan data sendiri. |
| `Panduan Pemilihan Komentar dan Anotasi.pdf` | Panduan dalam memilih komentar YouTube yang relevan dengan topik penelitian serta pedoman pelabelan (annotasi) sentimen positif dan negatif. |
