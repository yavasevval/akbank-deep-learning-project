# akbank-deep-learning-project
Akbank Derin Öğrenme Bootcamp Projesi

# Akbank Derin Öğrenme Bootcamp: Dogs vs. Cats Projesi
Bu proje, Akbank Derin Öğrenme Bootcamp kapsamında, Convolutional Neural Network (CNN) mimarisi kullanarak kedi ve köpek görsellerini sınıflandırmayı amaçlamaktadır. Projede temel derin öğrenme kavramları, veri ön işleme, model geliştirme ve performans değerlendirmesi gibi konulara odaklanılmıştır.

# Veri Seti
Projede, Kaggle'da bulunan "Dogs vs. Cats" veri seti kullanılmıştır. Bu veri seti, her biri kedi ve köpek görsellerinden oluşan yaklaşık 25.000 eğitim ve 12.500 test görseli içermektedir.

# Kullanılan Yöntemler
Projenin bu amacına ulaşmak için aşağıdaki yöntemler uygulanmıştır:

### Veri Ön İşleme ve Veri Çoğaltma: 
ImageDataGenerator kullanılarak görseller yeniden boyutlandırılmış, normalleştirilmiş ve modelin daha iyi genelleme yapması için rastgele döndürme, kaydırma ve yakınlaştırma gibi teknikler uygulanmıştır.

### CNN Mimarisi:
Model, evrişim (Convolutional), havuzlama (Pooling), dropout ve yoğun (Dense) katmanlarından oluşan özel bir CNN yapısıdır.

### Hiperparametre Optimizasyonu: 
Modelin performansını artırmak amacıyla farklı öğrenme oranları (1e-4 ve 1e-3) üzerinde denemeler yapılmıştır.

### Model Yorumlama: 
Modelin bir görseli sınıflandırırken hangi bölgelere odaklandığını göstermek için Grad-CAM görselleştirme tekniği kullanılmıştır.

# Elde Edilen Sonuçlar
Yapılan denemeler sonucunda, en iyi performansı gösteren modelin doğrulama doğruluğu (validation accuracy) %84.70 olarak ölçülmüştür. Bu sonuç, modelin daha önce hiç görmediği görselleri başarıyla sınıflandırabildiğini göstermektedir.

# Kaggle Notebook
[[Kaggle Notebook'umun Linki](https://www.kaggle.com/code/yavasevval/dogs-vs-cats-proje-26-09-25)]

