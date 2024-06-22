# KNN ile CIFAR-10 Sınıflandırma

Bu proje, CIFAR-10 veri setini kullanarak K-Nearest Neighbors (KNN) algoritması ile görüntü sınıflandırması yapmayı amaçlamaktadır.

## Proje Amacı
Bu projenin amacı, CIFAR-10 veri setindeki görüntüleri KNN algoritması kullanarak sınıflandırmak ve performans değerlendirmesi yapmaktır. KNN algoritmasının basit ve güçlü bir sınıflandırma algoritması olarak nasıl performans gösterdiğini incelemek için bu projeyi gerçekleştirdik.

## Kullanılan Veri Seti
- **Veri Seti Adı**: CIFAR-10
- **Özellikler**: 60,000 adet 32x32 boyutunda renkli görüntü, 10 sınıf.
- **Kaynak**: [CIFAR-10 Dataset](https://www.cs.toronto.edu/~kriz/cifar.html)

## Veri Ön İşleme
- Verilerin train ve test setlerine ayrılması.
- Görüntü verilerinin normalize edilmesi.

## Kullanılan Algoritma
- **Algoritma**: K-Nearest Neighbors (KNN)
- **Parametreler**: K (komşu sayısı), mesafe metriği (örneğin, Euclidean)

## Model Eğitimi ve Değerlendirme
- Eğitim ve test verileri kullanılarak model eğitimi.
- Performans değerlendirme metrikleri: Accuracy, Precision, Recall, F1-Score.

## Sonuçlar
Model sonuçları çeşitli değerlendirme metrikleri kullanılarak analiz edilmiştir:
- **Accuracy**: %xx.xx
- **Precision**: %xx.xx
- **Recall**: %xx.xx
- **F1-Score**: %xx.xx

## Kurulum ve Çalıştırma
1. Projeyi klonlayın:
   ```bash
   git clone <repo-url>
   cd <repo-directory>


