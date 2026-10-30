# Konut Kira Tahmini ve Fırsat Skorlama Sistemi

Bu proje, Python Programlama dersi kapsamında geliştirilmektedir. 

## Proje Amacı
Kiralık konut ilanlarındaki fiyatların piyasa ortalamasına göre ne kadar uygun olduğunu belirlemek amacıyla makine öğrenmesi tabanlı bir tahmin ve skorlama sistemi oluşturulacaktır. 

Sistemde konutların metrekare, oda sayısı, bina yaşı, bulunduğu kat ve konum gibi temel verileri kullanılarak olması gereken tahmini kira değeri hesaplanacak, ardından ilandaki mevcut fiyat ile karşılaştırılarak kullanıcıya ilan hakkında bir uygunluk puanı (ucuz, normal, pahalı) sunulacaktır.

## Planlanan Aşamalar
- Konut verilerinin toplanması ve eksik/hatalı verilerin temizlenmesi (Veri Ön İşleme)
- Kira fiyatlarını etkileyen faktörlerin incelenmesi ve grafikleştirilmesi
- Regresyon modelleri ile kira tahmin modelinin eğitilmesi ve test edilmesi
- Tahmin edilen değer ile ilan fiyatını kıyaslayan skorlama yapısının kurulması
- Kullanıcıların ev özelliklerini girip sonuç alabileceği basit bir arayüz hazırlanması

## Kullanılacak Kütüphaneler
- Pandas & NumPy (Veri analizi ve ön işleme)
- Scikit-learn (Makine öğrenmesi modeli)
- Matplotlib / Seaborn (Veri görselleştirme)
- Streamlit (Kullanıcı arayüzü)
