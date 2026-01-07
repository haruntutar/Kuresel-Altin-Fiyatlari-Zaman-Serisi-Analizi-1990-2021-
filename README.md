# 📈 Türkiye Altın Fiyatları Analizi ve Tahmini (1990–2025)

Bu proje, Türkiye'deki altın fiyatlarının 1990–2021 dönemindeki davranışlarını analiz eder ve Linear Regression yöntemiyle 2025'e kadar geleceğe yönelik tahminler üretir. Ayrıca farklı ülkelerin altın fiyatları arasındaki korelasyon yapısı incelenmiş ve kümeleme algoritmalarıyla benzerlik grupları oluşturulmuştur.

## 🔍 Proje İçeriği

- Türkiye altın fiyatlarının zaman serisi analizi  
- Linear Regression ile iteratif gelecek tahmini  
- Ülkeler arası korelasyon analizi (Pearson)  
- K-means, Agglomerative, GMM ve DBSCAN ile kümeleme  
- Volatilite ve trend bazlı ülke karşılaştırmaları  
- Görselleştirme: çizgi grafikleri, korelasyon heatmap'leri, kümeleme bar chart'ları

## 🧠 Kullanılan Yöntemler

- **Linear Regression**: Türkiye altın fiyatlarının gelecekteki değerlerini tahmin etmek için kullanıldı.  
- **Pearson Korelasyon**: Ülkeler arası fiyat benzerliğini ölçmek için.  
- **Kümeleme Algoritmaları**:  
  - KMeans  
  - Agglomerative  
  - Gaussian Mixture Model (GMM)  
  - DBSCAN (aykırı ülke tespiti)

## 📊 Öne Çıkan Bulgular

- Gelişmiş ülkeler arasında yüksek korelasyon (r > 0.90)  
- Türkiye’nin gelişmiş ülkelerle korelasyonu orta düzeyde (0.60–0.70)  
- Linear Regression tahmini, 2025’e kadar altın fiyatlarında yükseliş öngörüyor  
- Kümeleme sonuçları, Türkiye’nin yüksek volatiliteye sahip ülkelerle benzerlik gösterdiğini ortaya koyuyor
