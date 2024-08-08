# Enerji Üretimi ve Yenilenebilir Enerji Analizi

Bu proje, enerji üretimi ve yenilenebilir enerji kaynaklarının analizi üzerine odaklanmaktadır. Proje, veri keşfi, görselleştirme ve çeşitli makine öğrenme modellerinin uygulanmasını kapsamaktadır.

## İçindekiler

1. [Veriye İlk Bakış]
2. [Veri Görselleştirmesi]
3. [Model Kurma]
4. [Proje Yapısı]
5. [Kullanım]
6. [Katkıda Bulunanlar]
7. [Lisans]

## Veriye İlk Bakış

Veri setinin ilk aşamasında şu adımlar gerçekleştirilir:

- **Verinin İlk Beş Verisine Bakış:** Veri setinin temel özelliklerini anlamak için ilk beş veri gözden geçirilir.
- **Verinin Son Beş Verisine Bakış:** Son beş veri ile veri setinin sonundaki değerlerin durumu kontrol edilir.
- **Veri Seti Hakkında ve İndeksler Hakkında Bilgi:** Veri setinin yapısal özellikleri ve indeks bilgileri incelenir.
- **Yapısal Olarak Veri İstatistiksel İnceleme:** Veri setinin temel istatistikleri analiz edilir.
- **Veri Setindeki İndeksler Hakkında Bilgi:** İndekslerin anlamı ve işlevi hakkında bilgi sağlanır.
- **Veri Setindeki Boş Veriler Var mı Bakmak:** Eksik veri olup olmadığı kontrol edilir.
- **Veri Setindeki Yapısal Şekline Bakalım:** Veri setinin yapısal özellikleri incelenir.

## Veri Görselleştirmesi

Veri görselleştirme adımları aşağıdaki gibidir:

- **Ülkelerin Enerji Üretimi Açısından İnceleme:** Enerji üretim kapasiteleri ve miktarları görselleştirilir.
- **Enerji Üretim Türleri ve Buna Bağlı Üretim Miktarı:** Farklı enerji türlerinin üretim miktarları incelenir.
- **Ülkelerin Enerji Üretim Miktarı ve Üretim Şekli Açısından İnceleme:** Enerji üretim yöntemleri ülkelere göre karşılaştırılır.
- **Ülkelerin Enerji Üretim Miktarı ve Kamu-Özel Ortaklığı Üretim Açısından İnceleme:** Kamu ve özel sektörün enerji üretimindeki rolü değerlendirilir.
- **Ülkelerin Enerji Üretim Miktarı ve Bölgesel Anlaşmalı Üretim Açısından İnceleme:** Bölgesel anlaşmaların etkileri analiz edilir.
- **Kurulu Kapasiteye Bakalım:** Toplam kurulu kapasite incelenir.
- **Üretim Kapasitesinin Ülkeler Açısından İnceleme:** Ülkeler arası üretim kapasiteleri karşılaştırılır.
- **Fransa Özelinde Rusya-Ukrayna Savaşı Sonrası Fransa'nın Üretim Kapasitesini Artırma Politikaları:** Fransa'nın savaş sonrası enerji politikaları analiz edilir.
- **Üretim Kapasitesi ve Yıl Odaklı İnceleme:** Yıllara göre üretim kapasitesindeki değişiklikler incelenir.
- **Yıllara ve Üretim Miktarına Göre İnceleme:** Enerji üretim türleri yıllık bazda analiz edilir.
- **Enerji Tüketimine Yıllara Göre Bakalım:** Yıllık enerji tüketim değişiklikleri gözden geçirilir.
- **Yıllara Göre Yenilenebilir Enerji Oranı:** Yenilenebilir enerji oranındaki yıllık değişiklikler analiz edilir.
- **Yıllara Göre Yenilenebilir Enerji Oranını Ülkelere Odaklı İnceleme:** Ülkelere göre yenilenebilir enerji oranları karşılaştırılır.
- **Yenilenebilir Enerji Kaynakları Açısından Ülkeleri 2023 Yılı İçin İnceleme:** 2023 yılı için yenilenebilir enerji kaynakları analiz edilir.
- **Yenilenebilir Enerji Kaynaklarının Oranı ve Yapılma Proje Anlaşmaları:** Projelerin etkileri değerlendirilir.
- **Kişi Başına Düşen Milli Gelir ve Enerji Üretimi Dağılımı:** Ekonomik durum ile enerji üretimi arasındaki ilişki incelenir.

## Model Kurma

Farklı makine öğrenme modelleri kullanılarak enerji üretimi tahminleri yapılır:

- **Doğrusal Regresyon:** Enerji üretimi ve diğer faktörler arasındaki ilişkiler modellemesi.
- **Lojistik Regresyon:** Kategorik tahminler için kullanılır.
- **Destek Vektör Makinesi (SVM):** Karmaşık veri ilişkileri için yüksek doğruluk sağlar.
- **Karar Ağaçları:** Verileri ağaç yapısında analiz eder.
- **Yapay Sinir Ağı:** Daha karmaşık ilişkileri modellemek için derin öğrenme yöntemleri kullanılır.

## Proje Yapısı

Proje, veri analizi, görselleştirme ve modelleme aşamalarını içeren Python dosyaları ve Jupyter notebook'lar içerir. Her aşama için detaylı açıklamalar ve kodlar mevcuttur.

## Kullanım

Projeyi çalıştırmak için aşağıdaki adımları izleyin:

1. Gerekli kütüphaneleri yükleyin: `pip install -r requirements.txt`
2. Veriyi yükleyin ve ön işleme adımlarını uygulayın.
3. Model kurma ve değerlendirme adımlarını takip edin.
4. Görselleştirme ve sonuç analizi yapın.

## Katkıda Bulunanlar

Bu projede katkıda bulunanlar:

- [İbrahim Püsküllü] - Proje lideri ve geliştirici

## Lisans

Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır.
