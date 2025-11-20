1. Uçuş İptal Tahmin Sistemi

Bu proje, uçak bileti rezervasyonlarının iptal edilip edilmeyeceğini tahmin etmek amacıyla geliştirilmiş uçtan uca bir makine öğrenmesi çözümüdür. Havayolu şirketlerinin gelir tahmini, koltuk optimizasyonu ve müşteri memnuniyeti stratejilerine katkı sağlamayı hedefler.

***

1.1 Proje Kapsamı

Bu proje, [Zero2End Machine Learning Bootcamp](https://github.com/Developer-MultiGroup) kapsamında gerçekleştirilmiştir. Gerçek uçuş verileri kullanılarak iptal tahmini yapılmış, modelin her adımı dokümante edilmiştir.

***

1.2 Problem Tanımı

Havayolu şirketleri, rezervasyonların iptal edilip edilmeyeceğini önceden tahmin ederek overbooking stratejileri ve gelir planlaması yapabilir. Bu projede, geçmiş uçuş verilerine dayanarak bir rezervasyonun iptal edilme olasılığı tahmin edilmektedir.

***

1.3 Kullanılan Veri Seti

- **Kaynak:** [Kaggle – Flight Delay and Cancellation Dataset (2018–2022)](https://www.kaggle.com/datasets/robikscube/flight-delay-dataset-20182022)
- **Format:** Tabular (.csv)
- **Boyut:** 4M+ satır, 20+ özellik
- **Sentetik değil**, gerçek FAA verilerine dayalıdır.

---

1.4 Kullanılan Teknolojiler

- Python, Pandas, Scikit-learn, XGBoost, SHAP
- Streamlit (arayüz)
- joblib (model kaydı)
- Git, VSCode, Jupyter Notebook

***

1.5 Proje Yapısı

flight-cancellation-prediction/ 
├── data/ # Veri dosyaları 
├── notebooks/ # EDA, baseline, feature eng, model opt, evaluation, pipeline 
├── src/ # config.py, pipeline.py, inference.py, app.py 
├── models/ # Eğitilmiş model dosyası 
├── docs/ # Markdown dokümantasyonları 
├── README.md 
└── requirements.txt

***

1.6 Ekran Görüntüsü

<img width="1024" height="1024" alt="a screenshot-style m" src="https://github.com/user-attachments/assets/9bf9e5e4-4528-47f1-afe3-f00fd5ab9e41" />


***

1.7 Local Kurulum

```bash
git clone https://github.com/eceserka/flight-cancellation-prediction.git
cd flight-cancellation-prediction
pip install -r requirements.txt
streamlit run src/app.py

Öne Çıkan Belgeler
•	docs/eda_findings.md: Veri analizi bulguları
•	docs/baseline_docs.md: İlk model ve skorlar
•	docs/feature_eng_docs.md: Türetilen değişkenler
•	docs/model_opt_docs.md: Hiperparametre optimizasyonu
•	docs/evaluation_docs.md: SHAP ve iş uyumu
•	docs/final_pipeline_docs.md: Final pipeline açıklaması
```


1.8 Belgeler
- docs/eda_findings.md
- docs/baseline_docs.md
- docs/feature_eng_docs.md
- docs/model_opt_docs.md
- docs/evaluation_docs.md
- docs/final_pipeline_docs.md


*** İletişim ***
Ece ŞERKA
[LinkedIn Profilim](https://www.linkedin.com/in/eceserka)



