# Proyek Penelitian: Pengembangan Model Peringkasan Teks Abstraktif Berbasis BiLSTM dan Mekanisme Attention

## Overview
Penelitian ini bertujuan mengembangkan model peringkasan teks abstraktif berbasis BiLSTM dengan mekanisme attention, difokuskan pada cerita Mahabharata dalam bahasa Jawa. Penelitian ini mengeksplorasi bagaimana model peringkasan abstraktif dapat diadaptasi untuk bahasa Jawa dengan mempertimbangkan aspek linguistik dan budaya dalam cerita Mahabharata. Sebagai inovasi, penelitian ini menggunakan pendekatan hybrid berbasis BiLSTM dan attention untuk menyesuaikan karakteristik cerita Mahabharata.

Hasil dari penelitian ini diharapkan dapat memberikan kontribusi terhadap teknologi peringkasan otomatis, khususnya untuk bahasa Jawa, serta menghasilkan solusi yang relevan secara akademik dan praktis.

## Metadata
- **Model**: BiLSTM + Mekanisme Attention
- **Fokus Dataset**: Cerita Mahabharata dalam bahasa Jawa
- **Metode Evaluasi**: ROUGE (Recall-Oriented Understudy for Gisting Evaluation)
- **Bahasa**: Jawa
- **Sumber Data**: Website [sastra.org](https://sastra.org)
- **Output Dataset Format**: CSV

## Tools
- **Platform**: Google Colab
- **Framework Pemrograman**: Python
- **Library Utama**:
  - TensorFlow/Keras: Untuk pengembangan model BiLSTM
  - NLTK/Spacy: Untuk preprocessing teks
  - BeautifulSoup: Untuk web scraping dataset
  - Pandas: Untuk pengelolaan dataset
  - ROUGE-metric library: Untuk evaluasi kinerja model
- **API**: ChatGPT (sebagai referensi tambahan untuk ringkasan, maksimal 10% dari teks asli)

## Cara Penginstalan
1. **Buka Google Colab**:
   - Pastikan Anda memiliki akun Google untuk mengakses Google Colab.

2. **Clone Repository**:
   - Gunakan perintah berikut di salah satu cell Google Colab:
     ```python
     !git clone <repository-url>
     %cd <repository-directory>
     ```

