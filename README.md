# HOUSE_PREDICTION_SOLUTION

Ev Fiyat Tahmin Projesi
Bu proje, Ames, Iowa'daki konutların fiyatlarını tahmin etmeyi amaçlayan bir makine öğrenimi çalışmasıdır. Veriler, Kaggle üzerinde sağlanan bir veri setinden alınmıştır.

Kullanım
Veri Setinin Yüklenmesi: train.csv ve test.csv dosyalarını veri klasörüne yerleştirin.

Model Eğitimi

Özellik Mühendisliği
Proje boyunca aşağıdaki özellik mühendisliği adımları uygulanmıştır:

NEW_1st*GrLiv: 1. kat alanı ile yaşam alanının çarpımı

NEW_Garage*GrLiv: Garaj alanı ile yaşam alanının çarpımı

TotalQual: Çeşitli kalite ve kondisyon özelliklerinin toplamı

NEW_TotalFlrSF: 1. kat ve 2. kat alanlarının toplamı

NEW_TotalBsmtFin: Bitmiş bodrum alanlarının toplamı

NEW_PorchArea: Tüm veranda alanlarının toplamı

ve daha fazlası...

Modeller
Projede kullanılan modeller:

Doğrusal Regresyon

K-Nearest Neighbors (KNN)

Karar Ağaçları (CART)

Random Forest

Gradient Boosting (GBM)

XGBoost

LightGBM

Performans
Modellerin performansı RMSE (Root Mean Squared Error) metriği ile değerlendirildi. En iyi sonuçlar GBM modeli ile elde edildi.

