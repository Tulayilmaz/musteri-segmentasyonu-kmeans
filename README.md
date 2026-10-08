> ⚠️ **Not:** GitHub'ın Jupyter Notebook dosyalarını görüntülerken yaşadığı teknik sorunlar nedeniyle, kodları ve analiz çıktılarını (tablolar/skorlar) tam formatıyla görmek için lütfen aşağıdaki linke tıklayın:
> 
> 👉 **[Proje Notebook'unu Görüntüle (Nbviewer)](https://nbviewer.org/github/Tulayilmaz/musteri-segmentasyonu-kmeans
/blob/main/analiz.ipynb)**
# 🛍️ Customer Segmentation & Persona Analysis with K-Means Clustering

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange.svg)
![Plotly](https://img.shields.io/badge/Plotly-3D%20Visualization-red.svg)

Bu proje, bir alışveriş merkezinin müşteri verilerini kullanarak **Gözetimsiz Öğrenme (Unsupervised Learning)** teknikleriyle müşteri segmentasyonu gerçekleştirmek ve pazarlama ekipleri için veriye dayalı stratejiler üretmek amacıyla geliştirilmiştir.

## 📌 Öne Çıkan Özellikler

- **Keşifçi Veri Analizi (EDA):** Gelir, yaş ve harcama skorlarının dağılımlarının incelenmesi.
- **Dirsek Yöntemi (Elbow Method):** Optimum küme sayısının matematiksel olarak kanıtlanması ($K=5$).
- **Model Performansı (Silhouette Score):** Kümeleme kalitesinin doğruluk skoru ile ölçülmesi.
- **3D İnteraktif Görselleştirme:** Age, Income ve Spending Score değişkenlerinin Plotly ile 3 boyutlu analizi.
- **İş Zekası & Persona Analizi:** Segmentlerin iş kararlarına dönüştürülmesi ve pazarlama aksiyon planı.

---

## 📊 Müşteri Personaları ve Pazarlama Stratejileri

| Segment                    | Yaş Ort. | Gelir Ort. | Harcama Skoru | Stratejik Pazarlama Aksiyonu                                           |
| :------------------------- | :------: | :--------: | :-----------: | :--------------------------------------------------------------------- |
| **VIP / Altın Müşteriler** |   32.7   |   Yüksek   |    Yüksek     | Müşteri tutma (Retention), özel temsilci ve VIP ayrıcalıklar.          |
| **Uyuyan Devler (Fırsat)** |   41.1   |   Yüksek   |     Düşük     | Agresif kişiselleştirilmiş indirimler ve uyandırma kampanyaları.       |
| **Standart / Sadık**       |   42.7   |    Orta    |     Orta      | Çapraz satış (Cross-sell), "3 Al 2 Öde" paket kampanyaları.            |
| **Dikkatsiz Harcayanlar**  |   25.2   |   Düşük    |    Yüksek     | FOMO (Fırsatı kaçırma korkusu) pazarlaması, sosyal medya kampanyaları. |
| **Tasarruflu**             |   45.2   |   Düşük    |     Düşük     | Sezon sonu dev indirimler ve stok eritme odaklı iletişim.              |

---

## 🛠️ Kullanılan Teknolojiler

- **Dil:** Python
- **Veri İşleme:** Pandas, NumPy
- **Makine Öğrenmesi:** Scikit-Learn (`KMeans`, `silhouette_score`)
- **Görselleştirme:** Matplotlib, Seaborn, Plotly Express

---

## 🚀 Projeyi Yerelde Çalıştırma

1. Bu depoyu klonlayın:
   ```bash
   git clone [https://github.com/Tulayilmaz/musteri-segmentasyonu-kmeans.git](https://github.com/Tulayilmaz/musteri-segmentasyonu-kmeans.git)
   ```
