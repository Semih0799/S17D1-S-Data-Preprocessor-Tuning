📊 Cancer Prediction using Machine Learning Pipeline

Bu projede, tümör veri seti kullanılarak kötü huylu (malignant) tümörlerin tespit edilmesi amaçlanmıştır. Amaç, özellikle malignant sınıfını mümkün olduğunca yüksek doğrulukla yakalayabilen bir makine öğrenmesi pipeline’ı geliştirmektir.

Veri ön işleme adımları kapsamında eksik veriler KNNImputer ile tamamlanmış, ardından tüm özellikler MinMaxScaler ile ölçeklendirilmiştir. Kurulan pipeline içerisinde Logistic Regression modeli kullanılmış ve GridSearchCV ile hiperparametre optimizasyonu gerçekleştirilmiştir.

Model performansı recall metriği üzerinden değerlendirilmiş ve malignant tümörleri tespit etmede yaklaşık %92 başarı elde edilmiştir.

Kullanılan Teknolojiler:
Python
Pandas
Scikit-learn

Sonuç:
Recall: 0.92
