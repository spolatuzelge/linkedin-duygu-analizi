# 💬 LinkedIn Yorumları Üzerinden Duygu Analizi

Bu proje, LinkedIn kullanıcı yorumlarını analiz ederek TextBlob kütüphanesi yardımıyla duygu (sentiment) etiketleri üretmektedir. Veriler; pozitif, negatif ve nötr sınıflarına ayrılmış, sonuçlar grafikler ve WordCloud görselleri ile desteklenmiştir.

## 🎯 Amaç

- Yorumların uzunluk ve puan dağılımlarını analiz etmek
- TextBlob kullanarak duygu analizi yapmak
- Yorum metinlerinden kelime bulutu (WordCloud) oluşturmak

## 📁 Proje Yapısı

```
linkedin_duygu_analizi/
├── linkedin_duygu_analiz.ipynb       # Açıklamalı Jupyter Notebook
├── requirements.txt                  # Gerekli kütüphane listesi
└── data/
    └── data.csv                      # LinkedIn yorum verisi
```

## 🛠️ Kullanılan Kütüphaneler

- `pandas`, `matplotlib`, `seaborn`
- `textblob` → duygu analizi için
- `wordcloud` → metin görselleştirmesi

## ▶️ Çalıştırmak İçin

Aşağıdaki komutla kütüphaneleri yükleyebilirsiniz:
```
pip install -r requirements.txt
```

Ardından `linkedin_duygu_analiz.ipynb` dosyasını Jupyter'da çalıştırarak analize başlayabilirsiniz.
