# cancelledflight
Uçak Bileti İptal Tahmin Sistemi: Gelir Optimizasyonu için Makine Öğrenmesi Yaklaşımı

1. Aşama: Problem Tanımı ve Veri Seçimi

🎯 Problem:
Havayolu şirketleri, rezervasyonların iptal edilip edilmeyeceğini önceden tahmin ederek koltuk planlaması, overbooking stratejileri ve gelir tahminlerini optimize edebilir. Bu projede, geçmiş rezervasyon verilerine dayanarak bir biletin iptal edilip edilmeyeceğini tahmin eden bir model geliştirilecek.

✈️ Veri Seti: Flight Delay and Cancellation Dataset (2018–2022)
•	Kaynak: Kaggle – robikscube/flight-delay-dataset-20182022
•	Veri Türü: Gerçek uçuş verileri (ABD iç hatlar)
•	Boyut: 4GB+ (büyük hacimli, gerçekçi)

•	Özellikler:
•	Uçuş tarihi, kalkış/saat bilgileri
•	Havayolu, kalkış-varış havalimanı
•	Gecikme süresi, iptal durumu, iptal nedeni
•	Uçuş mesafesi, uçuş süresi, taşıyıcı kodu

Bu veri seti, iptal tahmini için çok uygun çünkü:
•	Sentetik değil, gerçek FAA (Federal Aviation Administration) verilerine dayanıyor.
•	Zengin özellik seti içeriyor (20+ sütun).
•	Yüksek hacimli (milyonlarca satır), bu da modelin genelleme gücünü artırır.
•	İptal bilgisi ve nedenleri mevcut, bu da sınıflandırma için ideal.

