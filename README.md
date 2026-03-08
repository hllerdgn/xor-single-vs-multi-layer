# XOR Problemi: Tek Katmanlı ve Çok Katmanlı Perceptron

Bu proje, XOR problemi üzerinden tek katmanlı ve çok katmanlı perceptronların performansını karşılaştırmak amacıyla hazırlanmıştır. Proje Python ve `scikit-learn` kütüphaneleri kullanılarak Google Colab veya yerel Python ortamında çalıştırılabilir.

## 🚀 Amaç

- Tek katmanlı perceptronun XOR problemini çözemediğini göstermek.
- Çok katmanlı perceptronun XOR problemini başarıyla sınıflandırabildiğini göstermek.
- Karar sınırlarının görselleştirilmesi ile lineer ve non-lineer sınıflandırma arasındaki farkı anlamak.

## 🛠 Kullanılan Teknolojiler

- Python 3.x
- `numpy`
- `matplotlib`
- `scikit-learn`

## 📂 Proje Dosya Yapısı

```
XOR-Perceptron/
│
├── xor_single_vs_multi.ipynb   # Colab notebook dosyası
├── README.md                   # Proje açıklama dosyası
```

## 🔹 Kullanım

1. Colab üzerinde `xor_single_vs_multi.ipynb` dosyasını açın.
2. Hücreleri sırayla çalıştırın:
   - Tek katmanlı perceptron tahminleri ve doğruluk
   - Tek katmanlı perceptron karar sınırı ve hatalı noktalar
   - Çok katmanlı perceptron tahminleri ve doğruluk
   - Çok katmanlı perceptron karar sınırı
3. Çıktılar ve grafikler notebook üzerinde görüntülenecektir.

## 📊 Sonuçlar

| Model                   | Doğruluk | Açıklama                                                 |
| ----------------------- | -------- | -------------------------------------------------------- |
| Tek Katmanlı Perceptron | 50%      | Lineer karar sınırı XOR'ü çözemedi                       |
| Çok Katmanlı Perceptron | 100%     | Non-lineer karar sınırıyla tüm noktaları doğru sınıfladı |

## 📝 Açıklama

- XOR problemi, tek katmanlı perceptronların lineer yetersizliğini göstermek için klasik bir örnektir.
- Çok katmanlı perceptronlar, gizli katmanlar ve sigmoid aktivasyon fonksiyonu sayesinde non-lineer sınıflandırma yapabilir.
- Bu proje, lineer ve non-lineer modellerin performans farkını görselleştirerek öğrenmeyi pekiştirir.

## 🔗 Referanslar

- [Scikit-learn Perceptron](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Perceptron.html)
- [Scikit-learn MLPClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPClassifier.html)
- Yapay Sinir Ağları ve XOR problemi literatürü
