# Öğrenci Başarı Tahmini - Makine Öğrenmesi Modelleri

Bu dproje, öğrenci başarısı tahmin etmek için çeşitli makine öğrenmesi modelleri kullanmaktadır. Bu projede aşağıdaki modeller bulunmaktadır:

- **SVM (Destek Vektör Makinesi)**
- **Lojistik Regresyon**
- **rpart (Karar Ağaçları)**
- **Random Forest (Rastgele Orman)**
- **XGBoost (Extreme Gradient Boosting)**

Projenin amacı, öğrenci bilgilerini kullanarak öğrencilerin son durumlarını tahmin etmektir (hedef değişkeni: `Dropout`, `Enrolled`, `Graduate`).

## Proje Özeti

Bu projede aşağıdaki adımlar izlenmiştir:

1. **Veri Ön İşleme**:
   - Öğrencilerin demografik ve akademik bilgilerini içeren veri seti okunur.
   - Kategorik değişkenler etiketleme ile sayısal verilere dönüştürülür.
   - Eğitim ve test setlerine ayırma işlemi gerçekleştirilir.
   
2. **Modellerin Eğitilmesi**:
   - **SVM Modeli**: Eğitim verisi kullanılarak doğrusal kernel ile eğitim yapılır.
   - **Lojistik Regresyon Modeli**: Eğitim verisi ile lojistik regresyon uygulanır.
   - **rpart (Karar Ağaçları)**: Karar ağacı sınıflandırma kullanılır.
   - **Random Forest Modeli**: Eğitim verisi ile rastgele orman algoritması kullanılarak eğitim yapılır.
   - **XGBoost Modeli**: XGBoost algoritması kullanılarak çok sınıflı sınıflandırma yapılır.

3. **Model Değerlendirme**:
   - Modellerin performansları doğruluk, karışıklık matrisi, hassasiyet, geri çağırma, F1 skoru gibi metriklerle değerlendirilir.

4. **Model Sonuçlarının Görselleştirilmesi**:
   - Modellerin doğrulukları ve metrikleri görselleştirilir.
