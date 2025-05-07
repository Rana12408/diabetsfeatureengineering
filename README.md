# 🩺 Diyabet Tahmin Projesi (Diabetes Prediction)

Bu proje, `diabetes.csv` veri setini kullanarak bireylerin diyabet hastası olup olmadığını tahmin etmeyi amaçlamaktadır. Veri analizi, keşifsel veri analizi (EDA), görselleştirme ve makine öğrenmesi modelleri ile tahminleme süreçleri yürütülmüştür.

## 📁 Veri Seti

Veri seti, çeşitli sağlık ölçütlerine göre bireylerin diyabet hastalığına sahip olup olmadığını belirtmektedir. İçerdiği başlıca sütunlar şunlardır:

- `Pregnancies`: Gebelik sayısı
- `Glucose`: Glikoz seviyesi
- `BloodPressure`: Kan basıncı
- `SkinThickness`: Cilt kalınlığı
- `Insulin`: İnsülin seviyesi
- `BMI`: Vücut kitle indeksi
- `DiabetesPedigreeFunction`: Genetik diyabet fonksiyonu
- `Age`: Yaş
- `Outcome`: **(Hedef Değişken)** 1 = Diyabet, 0 = Sağlıklı

## 🎯 Proje Amacı

Verilen sağlık verileri ışığında, bireylerin diyabet hastalığına sahip olup olmadığını (Outcome) tahmin etmek.

## 🔍 Uygulanan Adımlar

1. **Veri Yükleme ve İnceleme**
   - Boş değer kontrolü
   - Temel istatistiksel analizler

2. **Değişken Türlerinin Belirlenmesi**
   - Kategorik, nümerik ve karmaşık değişken ayrımı

3. **Kategorik ve Nümerik Değişkenlerin Analizi**
   - Değer dağılımı ve oranları
   - Hedef değişkenle ortalama karşılaştırmaları

4. **Veri Görselleştirme**
   - Histogramlar
   - Korelasyon matrisi (heatmap)

5. **Modelleme**
   - Verinin eğitim ve test olarak ayrılması
   - `Random Forest`, `Logistic Regression` vb. algoritmalarla sınıflandırma modeli oluşturulması

## 🛠️ Kullanılan Kütüphaneler

- `pandas`, `numpy`
- `seaborn`, `matplotlib`
- `scikit-learn`

