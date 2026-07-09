# Titanic_ML_Project
## Makine Öğrenmesi Uygulamaları: Veri Ön İşleme ve Metrik Analizi
Bu proje, bir veri bilimcinin gerçek dünyadaki verilerle karşılaşınca yaşadığı temel zorlukları ve "doğruluk yanılgısını" (accuracy paradox) anlamak için hazırlanan iki temel alıştırmayı içermektedir.

#### İçerik
### 1. Alıştırma A: Kirli Veriyi Temizle
Amaç: Ham ve eksik verinin makine öğrenmesi modeline girmeye hazır hale getirilmesi.

#### Yapılan İşlemler:

Eksik değerlerin tespiti (isnull().sum()) ve stratejik doldurulması (Imputation).

Kategorik sütunların sayısal verilere dönüştürülmesi (Encoding).

Özelliklerin aynı ölçeğe getirilmesi (StandardScaler).

Lojistik Regresyon ile ilk model eğitimi.

### 2. Alıştırma B: Accuracy'nin Yalanı
#### Amaç: Dengesiz veri setlerinde yüksek accuracy değerinin neden yanıltıcı olabileceğini kanıtlamak.

#### Yapılan İşlemler:

%95'e %5 oranında dengesiz bir veri seti üretimi.

Modelin yüksek başarı göstermesine rağmen azınlık sınıfını yakalayamadığının confusion_matrix ile tespiti.

Precision, Recall ve F1-Score metriklerinin önemi.

### Öğrenilen Temel Ders
Yüksek accuracy bazen bir tuzaktır. Özellikle dengesiz veri setlerinde, modelin sadece çoğunluk sınıfını ezberleyip ezberlemediğini anlamak için hata matrisine (confusion matrix) ve recall gibi daha derinlikli metriklere bakmak şarttır.
