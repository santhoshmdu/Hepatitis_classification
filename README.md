# 🏥 Hepatitis Disease Severity Prediction

<div align="center">

![Accuracy](https://img.shields.io/badge/Accuracy-97.8%25-00ff00?style=for-the-badge&labelColor=000000)
![F1-Score](https://img.shields.io/badge/Macro--F1-0.72-00d9ff?style=for-the-badge&labelColor=000000)
![Status](https://img.shields.io/badge/Status-Research_Ready-ffd700?style=for-the-badge&labelColor=000000)

**Machine Learning system for predicting hepatitis severity with 97.8% accuracy**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white&labelColor=000)
![Scikit-learn](https://img.shields.io/badge/Sklearn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white&labelColor=000)
![XGBoost](https://img.shields.io/badge/XGBoost-00A3E0?style=flat-square&labelColor=000)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white&labelColor=000)

</div>

---

## 🎯 Key Highlights

```
┌─────────────────────────────────────────┐
│  🎯 Accuracy:        97.8%              │
│  📊 XGBoost F1:      0.52 → 0.72 (+38%) │
│  🧠 MLP F1:          0.33 → 0.65 (+97%) │
│  ⚖️ Dataset:         Highly Imbalanced  │
│  🏥 Application:     Clinical Ready     │
└─────────────────────────────────────────┘
```

---

## 📋 Overview

Research-grade ML model addressing **severe class imbalance** (~10% critical cases) in hepatitis diagnosis using:

- **RFE** (Recursive Feature Elimination) → Remove noisy predictors
- **ADASYN** → Advanced synthetic oversampling
- **XGBoost + LightGBM** → Ensemble learning for robust predictions

---

## 🔄 Pipeline

```mermaid
%%{init: {'theme':'dark'}}%%
graph LR
    A[📊 Dataset] --> B[🔍 RFE]
    B --> C[⚖️ ADASYN]
    C --> D[🤖 XGBoost]
    D --> E[✅ 97.8%]
    
    style A fill:#1a1a1a,stroke:#00d9ff,color:#fff
    style B fill:#1a1a1a,stroke:#ff00ff,color:#fff
    style C fill:#1a1a1a,stroke:#ffd700,color:#fff
    style D fill:#1a1a1a,stroke:#00ff88,color:#fff
    style E fill:#1a1a1a,stroke:#00ff00,color:#fff
```

---

## 📊 Results

| Model | Before | After | Gain |
|-------|--------|-------|------|
| **XGBoost** | F1: 0.52 | **F1: 0.72** | +38% |
| **MLP** | F1: 0.33 | **F1: 0.65** | +97% |
| **Accuracy** | 89.2% | **97.8%** | +8.6% |

---

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/santhoshmdu/Hepatitis_classification.git
cd Hepatitis_classification

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook hepatitis_classification.ipynb
```

---

## 🛠️ Tech Stack

- **Language:** Python 3.8+
- **ML Libraries:** Scikit-learn, XGBoost, LightGBM
- **Data Processing:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Balancing:** ADASYN, RFE

---


---

## 🎓 Key Techniques

<details>
<summary><b>Why RFE Before Oversampling?</b></summary>

- Removes noisy features first
- Improves model interpretability
- Prevents synthetic samples from amplifying noise

</details>

<details>
<summary><b>Why ADASYN Over SMOTE?</b></summary>

- Focuses on harder-to-learn minority samples
- Better for medical datasets
- Reduces overfitting on synthetic data

</details>

---

## 📈 Clinical Impact

✅ **Early Detection** of life-critical hepatitis cases  
✅ **Reduced False Negatives** for severe conditions  
✅ **Balanced Predictions** across all severity levels  
✅ **Production-Ready** for clinical decision support

---

## 👨‍💻 Author

**Santhosh Thiruvengadam**

[![GitHub](https://img.shields.io/badge/GitHub-santhoshmdu-181717?style=flat-square&logo=github&labelColor=000)](https://github.com/santhoshmdu)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&labelColor=000)](https://linkedin.com/in/santhoshmadurai)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail&labelColor=000)](mailto:sahash1903@gmail.com)

---

## 📄 License

MIT License - Feel free to use for research and education

---

## ⭐ Acknowledgments

- Dataset: UCI Machine Learning Repository
- Research: Imbalanced Learning techniques
- Libraries: Scikit-learn, XGBoost, Imbalanced-learn

---

<div align="center">

**If you find this useful, please ⭐ star the repository!**

<sub>Made with ❤️ for advancing healthcare ML</sub>

</div>
