# 📊 Enflasyon Tahmin Modeli (2010–2023)

Bu projede, Türkiye'de 2010–2023 yılları arasında döviz kuru, politika faizi ve işsizlik oranına göre yıllık TÜFE (enflasyon) tahmini yapılmıştır.

## 🔧 Kullanılan Araçlar
- Python (pandas, matplotlib, seaborn)
- scikit-learn (LinearRegression)
- Jupyter Notebook

## 📊 Veriler
Veriler aşağıdaki kaynaklardan alınmıştır:
- Türkiye İstatistik Kurumu (TÜİK)
- Türkiye Cumhuriyet Merkez Bankası (TCMB)

### Kullanılan Değişkenler:
- TÜFE (%) [bağımlı değişken]
- USD/TRY kuru
- TCMB politika faizi
- İşsizlik oranı

## 🤖 Modelleme ve Yöntem
- Model türü: **Çoklu Doğrusal Regresyon**
- Amaç: Ekonomik göstergelere bakarak TÜFE'nin yıllar içindeki değişimini tahmin etmek

### 📈 Model Performansı
- **R² Skoru:** 0.895 → Model, TÜFE’deki değişimin %89.5’ini açıklayabiliyor.
- **MAE:** 4.67 → Ortalama hata 4.67 puan.

## 📉 Görsel Sonuç
Gerçek ve tahmin edilen TÜFE değerleri karşılaştırıldığında model, özellikle 2010–2019 arası oldukça başarılı tahminler üretmiştir.

_Grafik görselleri için Jupyter dosyasına göz atabilirsiniz._

## 🧑‍💻 Katkıda Bulunan
**Esma Sultan Koyuncu**  
- Dokuz Eylül Üniversitesi, Ekonometri 
- LinkedIn: www.linkedin.com/in/esma-sultan-koyuncu-077975266

---

