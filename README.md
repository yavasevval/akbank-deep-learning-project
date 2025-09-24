# akbank-deep-learning-project
Akbank Derin Öğrenme Bootcamp Projesi

# Akbank Derin Öğrenme Bootcamp: Dogs vs. Cats Projesi

### Projenin Amacı
Bu proje, Akbank Derin Öğrenme Bootcamp kapsamında, Convolutional Neural Network (CNN) mimarisi kullanarak kedi ve köpek görsellerini sınıflandırmayı amaçlamaktadır.

### Veri Seti
Projede, Kaggle'da bulunan "Dogs vs. Cats" veri seti kullanılmıştır. Bu veri seti, her biri kedi ve köpek görsellerinden oluşan yaklaşık 25.000 eğitim ve 12.500 test görseli içermektedir.

### Kullanılan Yöntemler
* **Veri Ön İşleme ve Çoğaltma:** Görsellerin yeniden boyutlandırılması, normalleştirilmesi ve `ImageDataGenerator` ile veri çoğaltma (Data Augmentation) teknikleri uygulanmıştır.
* **Model Mimarisi:** Model, evrişim (Convolutional), havuzlama (Pooling) ve tam bağlı (Dense) katmanlardan oluşan bir CNN yapısıdır.
* **Hiperparametre Optimizasyonu:** Modelin performansını artırmak için farklı öğrenme oranları (örneğin, 1e-4 ve 1e-3) üzerinde denemeler yapılmıştır.

### Elde Edilen Sonuçlar ve Başarı Skoru
Yapılan denemeler sonucunda, en iyi performansı gösteren modelin **doğrulama doğruluğu (validation accuracy)** **%86.83** olarak ölçülmüştür. Bu sonuç, modelin daha önce görmediği görselleri başarıyla sınıflandırdığını göstermektedir.

### Kaggle Notebook
[[Kaggle Notebook'un Linki]](https://www.kaggle.com/code/yavasevval/dogs-vs-cats-projesi)
