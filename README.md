# 🍄 Mantar Sınıflandırma Projesi: Gözetimli ve Gözetimsiz Öğrenme Karşılaştırması

Bu proje, Akbank Makine Öğrenmesi Bootcamp kapsamında gerçekleştirilmiştir. "Classification Mushroom Data 2020" veri seti üzerinde
hem **Gözetimli Öğrenme** hem de **Gözetimsiz Öğrenme** yöntemleri kullanılarak mantarların zehirli olup olmadığını tahmin etmeyi amaçlamaktadır.

---

##  Proje Amacı

Bu çalışmada hedef, çeşitli fiziksel özellikleri verilen mantarların yenilebilir mi yoksa zehirli mi olduğunu sınıflandırmaktır. 
Gözetimli öğrenme algoritmalarıyla yüksek doğruluklu tahminler yapılmış, ardından aynı veri seti gözetimsiz öğrenme teknikleriyle analiz edilmiştir.
Sonuçlar karşılaştırılmış ve yöntemlerin avantajları tartışılmıştır. Projenin çıktısı, kullanıcıların veri ile destekli kararlar alabilmesini sağlamakla birlikte,
gelecekte görsel tanıma gibi sistemlere de entegre edilebilir.



---

##  Kullanılan Yöntemler

### Gözetimli Öğrenme
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Random Forest Classifier  
- Performans Metrikleri: Accuracy, Precision, Recall, F1-Score, Confusion Matrix, ROC Curve

### Gözetimsiz Öğrenme (Bonus)
- k-Means  
- Gaussian Mixture Model (GMM)  
- DBSCAN  
- Değerlendirme Metrikleri: Silhouette Score, Adjusted Rand Index (ARI), Accuracy (etiket eşleştirme ile)

---

##  Model Karşılaştırma

| Model Türü       | Algoritma           | Doğruluk (Accuracy) | Diğer Metrikler                    |
|------------------|---------------------|----------------------|------------------------------------|
| Gözetimli        | Random Forest       | 0.99                 | Precision, Recall, F1 Score        |
| Gözetimli        | Logistic Regression | 0.98                 | ROC AUC eğrisi ile doğrulandı      |
| Gözetimli        | KNN                 | 0.96                 | K=5 ile optimum başarı             |
| Gözetimsiz       | k-Means             | ~0.82                | Silhouette = 0.54, ARI ≈ 0.62       |
| Gözetimsiz       | GMM                 | ~0.81                | ARI ≈ 0.59                         |
| Gözetimsiz       | DBSCAN              | Düşük                | Gürültü oranı yüksek, ARI < 0.3    |

---
## Kaggle Linki
Kaynak:https://www.kaggle.com/code/aysebilir/mushroom-classification-and-clustering-with-superv



---




