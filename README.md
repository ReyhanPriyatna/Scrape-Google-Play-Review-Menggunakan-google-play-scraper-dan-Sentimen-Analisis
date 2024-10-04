# Scrape Google Play Reviews Menggunakan google-play-scraper

Repository ini berisi proyek yang melakukan scraping ulasan pengguna dari aplikasi **Vidio Dot Com** di Google Play Store menggunakan library [`google-play-scraper`](https://github.com/danieliu/google-play-scraper). Ulasan yang diambil diekspor ke file **Excel**, dan analisis sentimen dilakukan untuk memberikan wawasan tentang umpan balik pengguna, tingkat kepuasan, dan sentimen keseluruhan terhadap aplikasi.

## Gambaran Proyek

- **Scraping Ulasan**: Menggunakan library `google-play-scraper`, ulasan dari aplikasi Vidio Dot Com dikumpulkan dan disimpan dalam file Excel.
- **Analisis Sentimen**: Ulasan dianalisis untuk menentukan sentimen (positif, negatif, atau netral) menggunakan teknik pengolahan bahasa alami dengan library Python seperti `NLTK` dan `Sastrawi`.
- **Visualisasi**: Grafik dan diagram dibuat untuk menggambarkan distribusi sentimen dan metrik kunci lainnya terkait ulasan.

## Fitur

- **Pengumpulan ulasan otomatis**: Mengambil ulasan dari Google Play untuk aplikasi Vidio Dot Com.
- **Klasifikasi sentimen**: Mengklasifikasikan ulasan sebagai positif, negatif, atau netral.
- **Ekspor ke Excel**: Menyimpan ulasan yang diambil dalam format Excel untuk akses dan analisis lebih lanjut.
- **Visualisasi Data**: Menggunakan library Python seperti `matplotlib`, `seaborn`, dan `plotly` untuk memvisualisasikan hasil analisis sentimen.

## Prerequisites

Pastikan kamu telah menginstal:

- Python 3.x
- Library Python berikut:

```bash
google_play_scraper==1.2.7
imbalanced_learn==0.10.1
matplotlib==3.7.1
nltk==3.8.1
pandas==2.0.3
plotly==5.15.0
protobuf==3.20.3
Sastrawi==1.0.1
scikit_learn==1.2.2
seaborn==0.13.2
wordcloud==1.9.3
