# LLMModels
LLMlerin Temsilleri Üzerinde Ensemble

Bu çalışmada, Dil Modeli (LLM) temsillerinin geliştirilmesi amacıyla ensemble yöntemleri olan Bagging, AdaBoost, Random Forest, Rotation Forest ve SVM gibi algoritmaların karşılaştırmalı analizi yapılmaktadır. Ayrıca, bu yöntemlerin hiperparametre optimizasyonu süreci detaylı bir şekilde incelenmektedir. Türkçe metin veri kümesi üzerinde gerçekleştirilen deneylerde, farklı ensemble yöntemlerinin performansları karşılaştırılarak en etkili yöntem belirlenmeye çalışılmaktadır.

Çalışma aynı zamanda büyük ve küçük BERT modellerinin kullanımının LLM temsilleri üzerindeki etkilerini ele almaktadır. Bu bağlamda, büyük BERT modellerinin performansıyla küçük BERT modellerinin performansı arasındaki farklılıklar ve avantajlar detaylı bir şekilde incelenmektedir. Türkçe metin veri kümesi üzerinde yapılan deneylerle, her iki BERT modelinin de LLM temsillerini geliştirmedeki katkıları ve sınırlamaları ortaya konmaktadır.

Sonuç olarak, bu çalışma LLM temsillerini optimize etmek amacıyla ensemble yöntemlerinin seçimi, hiperparametre optimizasyonu ve farklı BERT modellerinin kullanımı konularında kapsamlı bir analiz sunarak, dil işleme alanındaki araştırmacılara değerli bir kaynak sağlamaktadır. 

# Potential Customer Yield Calculation with Rule Based Classification (Kural Tabanlı Sınıflandırma ile Potansiyel Müşteri Getirisi Hesaplama)
<p align="center">
  <img src="https://github.com/celalakcelikk/rule-based-customer-segmentation/blob/main/media/Servant-Leadership.png" alt="rule-based"/>
<p>
  
## İş Problemi
Bir oyun şirketi müşterilerinin bazı özelliklerini kullanarak seviye tabanlı (level based) yeni müşteri tanımları (persona) oluşturmak ve bu yeni müşteri tanımlarına göre segmentler oluşturup bu segmentlere göre yeni gelebilecek müşterilerin şirkete ortalama ne kadar kazandırabileceğini tahmin etmek istemektedir.

## Veri Seti Hikayesi
* Persona.csv veri seti uluslararası bir oyun şirketinin sattığı ürünlerin fiyatlarını ve bu ürünleri satın alan kullanıcıların bazı demografik bilgilerini barındırmaktadır.
* Veri seti her satış işleminde oluşan kayıtlardan meydana gelmektedir. Bunun anlamı tablo tekilleştirilmemiştir.
* Diğer bir ifade ile belirli demografik özelliklere sahip bir kullanıcı birden fazla alışveriş yapmış olabilir.

## Veri Seti Değişkenleri
* **PRICE:** Müşterinin harcama tutarı 
* **SOURCE:** Müşterinin bağlandığı cihaz türü 
* **SEX:** Müşterinin cinsiyeti
* **COUNTRY:** Müşterinin ülkesi 
* **AGE:** Müşterinin yaşı
