# Linear-Regression-on-Credit-Data-in-KNIME
Bu proje, KNIME Analytics Platformu kullanılarak kredi verisi üzerinden bir doğrusal regresyon modeli kurmayı amaçlamaktadır. Amaç, bireylerin demografik ve finansal özelliklerine (yaş, cinsiyet, eğitim, gelir, çalışma süresi, ev sahipliği, kredi tutarı, kredi nedeni, kredi geliri, kredi süresi, kredi skoru, geçmiş kredi durumu vb.) dayanarak krediye ilişkin bir durumu veya skoru tahmin etmektir.

Veri, Excel dosyasından alınmış ve sayısal-kategorik dönüşümler gerçekleştirilmiştir. “One to Many” ile dummy değişkenler oluşturulmuş, ardından veriler normalize edilmiştir. Veri seti %70 eğitim ve %30 test olarak bölünmüş, eğitim verisiyle lineer regresyon modeli eğitilmiş ve test verisi üzerinde tahmin yapılmıştır.

Modelde gelir, yaş, çalışma süresi ve kredi faizi gibi değişkenler anlamlı bulunmuştur. Özellikle gelir değişkeni yüksek istatistiksel önem taşımaktadır. Modelin başarı ölçütü R-Kare: 0,5282 ve Düzeltilmiş R-Kare: 0,5121 olarak hesaplanmıştır.

