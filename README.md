# Web Tabanlı Veri Toplama ve Fiyat Karşılaştırma Aracı
Bu Python tabanlı analiz aracı, bir çevrimiçi alışveriş platformunda aynı ürünün birden fazla satıcı tarafından sunulduğu durumları tespit eder. Her bir satıcıyı fiyat, puan, kargo bilgisi,gibi kriterler açısından karşılaştırır ve ürün bazında analiz yaparak karşılaştırmalı sonuçlar üretir.

##  Özellikler

- Kullanıcının belirlediği bir siteden veri çekme (web scraping)
- Fiyat, satıcı, ürün adı gibi bilgilerin çıkarılması
- Verilerin CSV formatında kaydedilmesi
- En ucuz ve en pahalı 5 ürünün analiz edilmesi

---

##  Kullanılan Teknolojiler

- Python 3
- pandas
- requests
- BeautifulSoup

---

## Kurulum

1. Gerekli kütüphaneleri yükleyin:

   ```bash
   pip install -r requirements.txt
