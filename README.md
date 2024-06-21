# CIFAR-10 Görüntü Veri Seti Analizi
Bu proje, CIFAR-10 veri seti üzerinde çeşitli makine öğrenmesi ve derin öğrenme teknikleri kullanılarak yapılan bir görüntü sınıflandırma çalışmasını içerir.

## Proje Aşamaları
### 1. Veri Ön İşleme
- 📥 **Veri Setini Yükleme:** CIFAR-10 veri seti yüklendi.
- 🖼️ **Eğitim ve Test Verilerinin Görselleştirilmesi:** Eğitim ve test veri setindeki görüntülerin boyutları yazdırıldı ve görselleştirildi.
- 🔄 **Normalizasyon:** Görüntü verileri normalleştirildi.

### 2. Model Eğitimi ve Değerlendirme
- 🛠️ **Model Oluşturma:** Makine öğrenmesi metodlarından KNN, Decision Tree, SVM, Logistic Regression ve Random Forest algoritmaları kullanılarak modeller oluşturuldu.
- 📊 **Değerlendirme:** Modellerin karmaşıklık matrisleri oluşturuldu ve görselleştirildi.
- 📈 **Metrikler:** Modeller Accuracy, F1 Score, Recall ve Precision metriklerine göre değerlendirildi.

### 3. Derin Öğrenme ile Model Eğitimi
- 🔢 **One-Hot Encoding:** Sınıflar one-hot encoding ile dönüştürüldü.
- 🧠 **CNN Modeli:** Bir Convolutional Neural Network (CNN) modeli oluşturuldu ve katmanlar belirlendi.
- 📜 **Model Özeti ve Derleme:** Modelin özeti çıkarıldı, derlendi ve model eğitildi.

## Model İyileştirme
- 🛡️ **Overfitting’i Önleme:** Modelin doğruluğunu artırmak ve overfitting’i önlemek amacıyla Dropout, Early Stopping, L1 ve L2 Regularization yöntemleri kullanıldı.
- 🔍 **Değerlendirme:** Modelin accuracy ve loss değerleri göz önünde bulundurularak iyileştirmeler yapıldı.

## Sonuçların Raporlanması
- 📊 **Metriklerin Görselleştirilmesi:** Modellerin doğruluk, kayıp değerleri, F1 Score, Recall gibi metrikler görselleştirildi.
- 📝 **Yorumlama:** Elde edilen sonuçlar metriklere bakılarak yorumlandı.

Bu çalışma ile CIFAR-10 veri seti üzerinde çeşitli makine öğrenmesi ve derin öğrenme teknikleri kullanılarak başarılı bir görüntü sınıflandırma modeli geliştirilmiş ve iyileştirilmiştir. 

## Ek Bilgiler ve Kaynaklar
- 📚 **Veri Seti:** [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)
- 🛠️ **Analizde Kullanılan Kütüphaneler:** TensorFlow, Keras, NumPy, Matplotlib, Seaborn, Sklearn

