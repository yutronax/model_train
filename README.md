Boston Housing Price Prediction
Proje Açıklaması
Bu proje, Boston Housing veri setini kullanarak konut fiyatlarını tahmin etmeyi amaçlamaktadır. Çeşitli regresyon modelleri ve hiperparametre optimizasyonu kullanılarak en iyi tahmin modelini belirlemeye odaklanılmıştır.

Kullanılan Teknolojiler ve Kütüphaneler
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn (Sklearn)
Veri Seti
Bu çalışmada, Boston Housing veri seti kullanılmıştır. Veri seti, konut fiyatlarını etkileyen çeşitli özellikleri içermektedir.

Yapılan İşlemler
Veri Yükleme ve Temizleme

Eksik verilerin çıkarılması
Korelasyon analizi ile gereksiz değişkenlerin elenmesi
Veri Ön İşleme

Standardizasyon uygulanması
Eğitim ve test veri kümelerine bölme
Model Eğitimi ve Karşılaştırma

Linear Regression
Random Forest Regressor
Gradient Boosting Regressor
Decision Tree Regressor
K-Nearest Neighbors Regressor
RandomizedSearchCV ile en iyi hiperparametrelerin belirlenmesi
Model Performans Analizi

Mean Squared Error (MSE) hesaplaması
Gerçek ve tahmin edilen değerlerin karşılaştırılması
Sonuçlar
Eğitim ve test aşamalarında en düşük hata oranına sahip model seçilmiş ve grafiklerle desteklenerek performans analizi yapılmıştır.

Nasıl Kullanılır?
Gerekli kütüphaneleri yükleyin:
bash
Kopyala
Düzenle
pip install pandas numpy matplotlib scikit-learn
Projeyi çalıştırın:
Google Colab veya Jupyter Notebook üzerinde .ipynb dosyasını açarak çalıştırabilirsiniz.
