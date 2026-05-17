# 🌾 Agro-Invest: Makine Öğrenmesi Tabanlı Akıllı Tarım Yatırım Paneli

Agro-Invest, modern tarım yatırımlarında riskleri minimize etmek ve kaynak verimliliğini optimize etmek amacıyla geliştirilmiş bir **Karar Destek Sistemi**'dir. Proje, toprak ve iklim parametrelerini analiz ederek kullanıcıya en yüksek uyumluluk ve getiri sağlayacak mahsul önerisini sunar.

---

## 🚀 Proje Özellikleri
- **Veri Temizliği & Ön İşleme:** Aykırı değerlerin IQR (Interquartile Range) yöntemiyle temizlenmesi ve gürültülü verilerin elenmesi.
- **Dengeli Veri Dağıtımı:** `Stratify` parametresi kullanılarak 22 farklı bitki sınıfının Eğitim (%70), Doğrulama (%15) ve Test (%15) setlerine matematiksel olarak eşit dağıtılması.
- **Çoklu Model Algoritmaları:** Random Forest, Support Vector Machine (SVM) ve Naive Bayes modellerinin karşılaştırmalı analizi.
- **XAI (Açıklanabilir Yapay Zeka):** "Kara Kutu" model kararlarının SHAP analizi ile şeffaflaştırılması ve güvenilirlik tescili.
- **Canlı Dağıtım (Deployment):** Streamlit kütüphanesi kullanılarak yatırımcıların kolayca kullanabileceği etkileşimli bir web paneli tasarımı.

---

## 📊 Modelleme Stratejisi ve Veri Mimarisi
- **Eğitim Seti (%70):** 1237 Gözlem
- **Doğrulama Seti (%15):** 265 Gözlem
- **Nihai Test Seti (%15):** 266 Gözlem

### Model Başarı Tablosu
| Algoritma | Set Türü | Accuracy (Doğruluk) | Precision (Hassasiyet) | Recall (Duyarlılık) |
| :--- | :--- | :---: | :---: | :---: |
| **Random Forest** | Eğitim / Test | %100 / %99.39 | 1.00 / 0.99 | 1.00 / 0.99 |
| **Naive Bayes** | Eğitim / Test | %99.41 / %99.39 | 0.99 / 0.99 | 0.99 / 0.99 |
| **SVM** | Eğitim / Test | %98.63 / %97.58 | 0.98 / 0.97 | 0.98 / 0.97 |

---

## 🛠️ Kullanılan Teknolojiler
- **Programlama Dili:** Python
- **Veri Analizi & ML:** Pandas, NumPy, Scikit-Learn, SHAP
- **Görselleştirme:** Matplotlib, Seaborn
- **Arayüz & Dağıtım:** Streamlit, Joblib

---

## 💻 Uygulamayı Yerelde Çalıştırma
Projeyi yerel bilgisayarınızda çalıştırmak için aşağıdaki komutları sırasıyla terminalinizde çalıştırabilirsiniz:

```bash
# Sistem bunu kod bloğu sanıyordu:
git clone ...
pip install ...
streamlit run ...
```
👥 Geliştiriciler

Elif Bilge Güleç - İstanbul Sabahattin Zaim Üniversitesi / Bilgisayar Mühendisliği

Ümmü Habibe Yüce - İstanbul Sabahattin Zaim Üniversitesi / Bilgisayar Mühendisliği


