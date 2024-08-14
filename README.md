# FLO RFM Analizi Projesi

Bu proje, FLO müşterilerini RFM (Recency, Frequency, Monetary) analizi ile segmentlere ayırmayı ve bu segmentlere göre pazarlama stratejileri belirlemeyi amaçlamaktadır. Proje, veri temizleme, RFM metriklerinin hesaplanması, müşteri segmentasyonu ve belirli aksiyon önerilerini içerir.

## Proje Adımları

1. **Veriyi Anlama ve Hazırlama**
   - Veriyi bir CSV dosyasından yükleyin.
   - Tarih sütunlarını datetime formatına çevirin.
   - Eksik ve sıfır değerleri kontrol edin ve kaldırın.
   - Toplam sipariş ve toplam değer için yeni değişkenler oluşturun.

2. **RFM Metriklerinin Hesaplanması**
   - Recency, Frequency ve Monetary değerlerini tanımlayın.
   - Her müşteri için bu metrikleri hesaplayın.
   - Hesaplanan metrikleri bir RFM dataframe'ine atayın.

3. **RF Skorunun Hesaplanması**
   - Recency, Frequency ve Monetary değerlerini qcut yardımı ile 1-5 arasında skorlara çevirin.
   - Bu skorları recency_score, frequency_score ve monetary_score olarak kaydedin

