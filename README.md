# Analisis-Sentimen-Komentar-Review-untuk-Marketing-Mix-7P

## Deskripsi Proyek
Proyek ini bertujuan untuk melakukan analisis sentimen pada komentar YouTube terkait video review Samsung A56. Dengan menggunakan teknik text mining, proyek ini mengekstrak, membersihkan, dan menganalisis ribuan komentar untuk mengetahui persepsi publik terhadap produk tersebut.

## Alur Proyek
1. **Scraping Data**: Mengambil komentar dari video YouTube menggunakan YouTube Data API.
2. **Preprocessing**: Membersihkan data, menghilangkan stopwords, normalisasi, dan stemming menggunakan library Sastrawi dan NLTK.
3. **Analisis Sentimen**: Menggunakan pendekatan berbasis leksikon dan machine learning untuk mengklasifikasikan sentimen komentar (positif, negatif, netral).
4. **Visualisasi**: Menampilkan hasil analisis dalam bentuk grafik dan wordcloud.

## File Penting
- `Project_Text_Mining.ipynb`: Notebook utama berisi seluruh pipeline analisis.
- `youtube_comments1.csv`: Hasil scraping komentar YouTube.
- `hasil_analisis_sentimen.csv`: Hasil akhir analisis sentimen.
- `distribusi_sentimen.png`: Visualisasi distribusi sentimen.

## Teknologi & Library
- Python (pandas, numpy, nltk, textblob, gensim, matplotlib, wordcloud, transformers, sastrawi)
- YouTube Data API

## Cara Menjalankan
1. Pastikan semua library pada notebook sudah terinstall.
2. Jalankan notebook `Project_Text_Mining.ipynb` secara berurutan.
3. Ganti API Key YouTube pada bagian scraping jika diperlukan.

## Catatan
- Proyek ini menggunakan data publik dari YouTube untuk tujuan pembelajaran.
- Hasil analisis dapat digunakan untuk memahami persepsi konsumen terhadap produk Samsung A56.
