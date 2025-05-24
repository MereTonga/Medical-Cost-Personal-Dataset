# 📊 Sağlık Sigortası Maliyet Tahmini – Lineer Regresyon Projesi

Bu proje, bireylerin demografik ve sağlıkla ilgili özelliklerine göre sağlık sigortası maliyetlerini (`charges`) tahmin etmeye yönelik bir **veri bilimi çalışmasıdır**. Proje boyunca veri keşfi, görselleştirme, istatistiksel testler ve çoklu lineer regresyon modeli uygulanmıştır.

---

## 🎯 Proje Amacı

Amaç, bireylerin özelliklerine göre sağlık sigortası ücretlerini tahmin eden bir regresyon modeli geliştirmektir. Bu kapsamda:

- Veriler analiz edilmiş,
- Gerekli ön işlemler yapılmış,
- Regresyon modeli kurulmuş,
- Model performansı istatistiksel olarak değerlendirilmiştir.

---

## 📁 Kullanılan Veri Seti

Veri seti `[insurance.csv](https://www.kaggle.com/datasets/mirichoi0218/insurance)` adlı bir dosyadan alınmıştır ve şu bilgileri içerir:

- `age`: Yaş
- `sex`: Cinsiyet
- `bmi`: Vücut Kitle İndeksi
- `children`: Çocuk sayısı
- `smoker`: Sigara içme durumu
- `region`: Yaşanılan bölge
- `charges`: Sağlık sigortası maliyeti (bağımlı değişken)

Toplam 1338 gözlem içermektedir ve eksik veri bulunmamaktadır.

---

## ⚙️ Kullanılan Kütüphaneler

- `pandas`, `numpy`: Veri işlemleri
- `matplotlib`, `seaborn`: Görselleştirme
- `scikit-learn`: Veri ön işleme ve regresyon modelleme
- `scipy`, `statsmodels`: İstatistiksel testler ve ANOVA

---

## 📊 Yapılan Analizler

- Sayısal ve kategorik değişken analizi
- Histogramlar, scatter plot ve korelasyon ısı haritası
- Güven aralıkları (%95) ve t-testi, chi-square testi
- Çoklu lineer regresyon modeli
- Model başarı ölçütleri: MAE, MSE, RMSE, R²
- ANOVA tablosu ile değişken önem analizi

---

## 📌 Sonuçlar

- Sigara kullanımı (`smoker`) sigorta maliyetlerini en çok etkileyen değişkendir.
- Modelin R² skoru ≈ 0.78 olup, `charges` değişkenindeki değişimin %78’ini açıklamaktadır.
- Sigorta primlerini etkileyen temel faktörler: yaş, BMI ve sigara kullanımıdır.

---
