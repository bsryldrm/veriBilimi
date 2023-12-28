## veriBilimi
Keşifsel Veri Analiz (Exploratory Data Analysis)

Bu terim, veri setinin anlaşılması ve içerdiği özelliklerin keşfedilmesi için yapılan analiz işlemlerini ifade eder. Keşifsel Veri analiz, veri setindeki desenleri, ilişkileri ve önemli özellikleri belirleyerek daha derinlemesine analizler için temel oluşturur. Bu aşama, veri bilimi ve istatistiksel analiz projelerinde genellikle başlangıç noktası olarak kullanılır.
Keşifsel Veri Analizi (EDA sırasında yapılan bazı yaygın işlemler:
1.	Veri Setinin Genel Bakışı:
•	Veri setinin ilk birkaç satırına ve sütununa bakarak genel bir fikir edinme. head(), tail(), info() gibi fonksiyonlar kullanılabilir.
2.	Temel İstatistiklerin İncelenmesi:
•	Veri setinin temel istatistik özelliklerini (ortalama, medyan, standart sapma, min, max vb.) inceleyerek merkezi eğilim ve yayılım hakkında bilgi edinme. describe() fonksiyonu sıklıkla kullanılır.
3.	Eksik Verilerin İncelenmesi:
•	Eksik verilerin nerede olduğunu belirleme ve bu eksikliklerin veri setini nasıl etkilediğini değerlendirme. isnull(), sum() gibi fonksiyonlar kullanılabilir.
4.	Değişkenler Arası İlişkilerin Analizi:
•	Değişkenler arasındaki ilişkileri anlamak için korelasyon matrisi, scatter plotlar, pair plotlar gibi görselleştirmeler yapma.
5.	Kategorik Değişken Analizi:
•	Kategorik değişkenlerin dağılımını inceleme ve bunların sınıf dengesini değerlendirme. Frekans tabloları, bar grafikleri, pasta grafikleri kullanılabilir.
6.	Outlier (Aykırı Değer) Analizi:
•	Aykırı değerleri tespit etme ve bu değerlerin gerçekçi olup olmadığını değerlendirme. Box plot, histogram gibi görselleştirmeler kullanılabilir.
7.	Dağılım Analizi:
•	Değişkenlerin dağılımını inceleme. Histogramlar, yoğunluk grafikleri, QQ plotlar gibi görsel araçlar kullanma.
8.	İnteraktif Görselleştirme:
•	Veri setini daha ayrıntılı bir şekilde incelemek için interaktif görselleştirmeler kullanma. Bu, daha fazla detayı ve odaklanmayı sağlar.
9.	Hipotez Testleri:
•	Önemli olduğunu düşündüğünüz değişkenler arasında istatistiksel olarak anlamlı farklar olup olmadığını belirlemek için hipotez testleri yapma.
10.	İleri Analiz İçin Hazırlık:
•	Veri setindeki önemli desenleri ve keşifleri belirleyerek ileri analizler için temel oluşturma.
EDA süreci, veri setinin hikayesini anlamak ve modelleme aşamasına geçmeden önce temel bilgileri elde etmek için kritik bir aşamadır. 

Özellik Mühendisliği (Feature Engineering)

veri bilimi ve makine öğrenimi projelerinde kullanılan bir süreçtir. Bu süreçte, mevcut özellikleri kullanarak yeni özellikler oluşturulur veya mevcut özelliklerde değişiklikler yapılır. Özellik mühendisliği, modelin öğrenme yeteneğini artırabilir, eğitim süreçlerini iyileştirebilir ve genellikle daha iyi sonuçlar elde etmeye yardımcı olabilir.
İşte özellik mühendisliğinde sıkça yapılan bazı işlemler:
1.	Birebir Dönüşümler:
•	Mevcut özellikleri diğer özelliklerle çarpma, bölme veya üs alma gibi matematiksel işlemlere tabi tutma.
2.	Logaritmik ve İstatistiksel Dönüşümler:
•	Logaritmik dönüşümler, özelliklerin dağılımlarını düzeltmek veya model performansını artırmak için kullanılır. Ayrıca, özellikler üzerinde istatistiksel hesaplamalar yapma.
3.	Kategori Dönüşümleri:
•	Kategorik değişkenleri sayısallaştırma (One-Hot Encoding gibi) veya belirli bir sıra içindeki kategori düzeylerini sayısal değerlere dönüştürme.
4.	Eksik Veri İşleme:
•	Eksik verileri doldurma veya eksik verilere dair bilgiler içeren yeni özellikler oluşturma.
5.	Interaksiyon ve Polinomlar:
•	Değişkenler arasındaki etkileşimleri ifade etmek için özellikleri çarparak veya bölerek yeni özellikler oluşturma. Ayrıca, polinom terimleri ekleyerek non-linear ilişkileri modelleme.
6.	Normalizasyon ve Standartlaştırma:
•	Özellikleri belirli bir aralığa veya standart normal dağılıma getirme.
7.	Zaman Serisi Özellikleri:
•	Zaman serisi verileri için özel özellikler oluşturma, örneğin, zamanın mevsimsellik, trend veya döngüselliği hakkında bilgi içeren özellikler.
8.	Domain Bilgisi Kullanma:
•	Alan bilgisini kullanarak, problemle ilgili özel bilgileri içeren özellikler oluşturma.
9.	Aggregasyon ve Gruplama:
•	Veriyi gruplayarak ve belirli bir özelliğe göre özetleme yaparak (ortalama, toplam, maksimum, minimum vb.) yeni özellikler oluşturma.
Özellik mühendisliği, veri setini daha anlamlı ve öğrenilebilir kılmak, modelin daha iyi genelleme yapabilmesini sağlamak amacıyla gerçekleştirilir. Başarılı bir özellik mühendisliği, veri setinin içerdiği desenleri daha iyi ortaya çıkarabilir ve modelin performansını artırabilir.

