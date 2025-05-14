# 📊 Eğitim, Maaş ve İşsizlik İlişkisi - Türkiye Veri Analizi

## Proje Özeti
Bu projede Türkiye’ye ait kamu verileri kullanılarak **eğitim düzeyi**, **ortalama brüt maaş** ve **işsizlik oranı** arasındaki ilişki analiz edilmiştir. Veri görselleştirmeleri, korelasyon analizleri ve basit regresyon modelleri ile bu değişkenler arasındaki etkiler değerlendirilmiştir.

## Kullanılan Veriler
- **TÜİK Kazanç Yapısı Araştırması 2018**
- **TÜİK İl Bazında İşgücü Göstergeleri (2022)**

## Uygulanan Analizler
- Eğitim düzeyine göre maaş değişimi (zaman serisi)
- Eğitim seviyesi ↔ Maaş ilişkisi (regresyon)
- Eğitim seviyesi ↔ İşsizlik ilişkisi (regresyon + korelasyon)
- İl düzeyinde işsizlik oranları (bar chart)
- İşsizlik ↔ Ortalama maaş ilişkisi

## Öne Çıkan Bulgular
- Eğitim düzeyi arttıkça maaş da artıyor (**r = 0.96**)
- Eğitim seviyesi yükseldikçe işsizlik oranı düşüyor (**r = -0.98**)
- Türkiye’deki bazı bölgelerde hem düşük eğitim hem de yüksek işsizlik birlikte görülmekte

## Kullanılan Araçlar
- Python, Pandas, Matplotlib, Seaborn, Scikit-learn
- Google Colab

---

📎 `proje_kodu.ipynb` dosyasında tüm analizler ve grafikler adım adım yer almaktadır.
