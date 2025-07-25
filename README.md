# -covid-literature-analysis
# COVID-19 Literatür Analizi (CORD-19)

Bu projede, COVID-19 üzerine yayınlanan akademik makalelerin yer aldığı CORD-19 veri seti kullanılarak basit bir metin madenciliği çalışması yapılmıştır. Amaç, makalelerin özet bölümlerinde (abstract) en sık geçen kelimeleri incelemek ve bu kavramları görselleştirmektir.

## 📁 Kullanılan Veri
- [CORD-19 Research Challenge Dataset](https://www.kaggle.com/datasets/allen-institute-for-ai/CORD-19-research-challenge)
- Kullanılan dosya: `metadata.csv`
- Veri 2023 sürümünden alınmıştır.

## ⚙️ Kullanılan Teknolojiler
- Python
- Pandas
- Matplotlib
- NLTK (Natural Language Toolkit)
- WordCloud

## 🔍 Projede Yapılanlar
- `abstract` sütununda boş olmayan satırlar filtrelendi
- Metin temizleme adımları (küçük harfe çevirme, noktalama temizliği, stopword çıkarımı)
- En sık geçen kelimelerin analiz edilmesi
- WordCloud ve bar chart ile görselleştirme
- Yayınların yıllara göre dağılımının incelenmesi

## 📂 Dosya Yapısı
covid-literature-analysis/
├── metadata.csv
├── covid_analysis.ipynb
├── README.md 

## 👤 Hazırlayan
İkra Uğurlu  
Temmuz 2025  

