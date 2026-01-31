# Credit-Risk-Prediction-ML
Banka kredi riskini tahmin eden, SMOTE ile dengelenmiş makine öğrenmesi projesi.

# Credit Risk Analysis & Prediction (SMOTE Optimized)

Bu proje, bir bankanın kredi portföyündeki riskli müşterileri yüksek doğrulukla tespit etmek amacıyla geliştirilmiş uçtan uca bir makine öğrenmesi pipeline'ıdır.

## Teknik Öne Çıkanlar
* **Veri Dengeleme (SMOTE):** Eğitim setindeki azınlık sınıfı (Riskli Müşteriler) sentetik verilerle dengelenerek modelin yanlılığı giderilmiştir.
* **Performans Optimizasyonu:** Karar eşiği (Threshold) **0.7**'ye çekilerek, banka için en kritik metrik olan **Recall (Riskliyi Yakalama) oranı %81'e** çıkarılmıştır.
* **Deployment:** Kullanıcıların canlı veri girişi yapabileceği bir **Gradio** arayüzü entegre edilmiştir.

## Sonuç Tablosu
| Metrik | Optimize Edilmiş Model (Eşik: 0.7) |
| :--- | :--- |
| **Doğruluk (Accuracy)** | %65 |
| **Riskli Yakalama (Recall)** | **%81** |
| **Güvenilir Belirleme (Precision)** | %87 |

## Teknoloji Yığını
* **Dil:** Python
* **ML:** Scikit-learn (Random Forest), Imbalanced-learn (SMOTE).
* **Arayüz:** Gradio.

## Kullanım
1. Kütüphaneleri yükleyin: `pip install pandas scikit-learn imbalanced-learn gradio`
2. Notebook dosyasını (`.ipynb`) çalıştırın ve arayüz üzerinden tahmin yapmaya başlayın.
