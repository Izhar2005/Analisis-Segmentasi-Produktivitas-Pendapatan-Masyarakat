# Analisis-Segmentasi-Produktivitas-Pendapatan-Masyarakat
Halo! Ini proyek kecil yang gue bikin buat latihan machine learning unsupervised. Gue ambil data survei sederhana tentang produktivitas dan pendapatan masyarakat (kayak umur, pendidikan, jam kerja, dll.), terus gue segmentasiin pake K-Means clustering biar keliatan pola-pola kelompoknya. Abis itu, gue validasiin pake Random Forest buat liat seberapa akurat klasterannya. Hasilnya lumayan, akurasi sampe 96% di data test!
Proyek ini dibuat pake Jupyter Notebook, cocok buat yang lagi belajar ML dasar. Datasetnya dari file Excel, dan gue fokus ke preprocessing, clustering, visualisasi, sama evaluasi model.

Kalo lu punya data sendiri, tinggal ganti file Excelnya.
Hasil Singkat

Klustering: 4 grup, visualisasi nunjukin pemisahan yang oke berdasarkan pengalaman kerja dan jam kerja.
Klasifikasi: Akurasi 96.67%, precision/recall bagus di semua kluster.
Insight: Kelompok dengan pengalaman tinggi & jam kerja stabil cenderung di kluster premium (mungkin pendapatan lebih tinggi)
