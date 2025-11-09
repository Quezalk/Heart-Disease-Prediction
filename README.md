# ❤️ Heart Disease Risk Analysis

Exploring the **Framingham Heart Study dataset** to identify major risk factors influencing 10-year heart disease outcomes.

This repository is part of a larger data science project focused on **predicting cardiovascular risk** using real-world health data.

---

## 📊 Project Overview

Heart disease remains one of the leading causes of mortality worldwide.  
This project applies data science techniques to explore and understand the key contributors to heart disease, including:

- Age, blood pressure, and cholesterol levels  
- Smoking, diabetes, and BMI  
- Gender and lifestyle factors  

The goal is to **gain insights** from the data and progressively build predictive models to estimate heart disease risk.

---

## 🧭 Project Roadmap

| Phase | Notebook | Description | Status |
|--------|-----------|--------------|----------|
| 🧼 **EDA** | `notebooks/01_EDA.ipynb` | Data exploration, cleaning, and insight discovery | ✅ Completed |
| 🧩 **Feature Engineering** | `notebooks/02_Feature_Engineering.ipynb` | Feature selection, transformation, and data preprocessing | 🔄 Upcoming |
| 🤖 **Modeling** | `notebooks/03_Modeling.ipynb` | Predictive modeling using Logistic Regression, Random Forest, and XGBoost | 🔄 Upcoming |
| 📈 **Evaluation** | `notebooks/04_Evaluation.ipynb` | Model comparison, ROC-AUC analysis, and metrics visualization | 🔄 Upcoming |

---

## 🧠 Key EDA Insights
- **Age** and **systolic blood pressure** are the strongest predictors of heart disease risk.  
- **Smoking** and **diabetes** significantly increase the likelihood of developing CHD.  
- **BMI** and **cholesterol** show moderate associations with risk.  
- Median imputation ensured complete and reliable data.  
- Male participants show a slightly higher risk overall.

---

## 🧰 Tech Stack
- Python 🐍  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## 📂 Repository Structure
heart-disease-risk-analysis/
│
├── notebooks/
│ ├── 01_EDA.ipynb
│ ├── 02_Feature_Engineering.ipynb 
│ ├── 03_Modeling.ipynb
│ └── 04_Evaluation.ipynb 
│
├── data/
│ └── framingham.csv 
│
├── images/ 
│
└── README.md

---

## 📈 Dataset
**Framingham Heart Study (Kaggle)**  
[https://www.kaggle.com/datasets/amanajmera1/framingham-heart-study-dataset](https://www.kaggle.com/datasets/amanajmera1/framingham-heart-study-dataset)

- Records: ~4,000  
- Features: 15  
- Target: `TenYearCHD` (1 = heart disease, 0 = no heart disease)

---

## 🙌 Author
👩‍💻 **Ghazal Kamali**  
🔗 [LinkedIn](https://www.linkedin.com/in/ghazal-kamali/)  

If you found this useful, feel free to ⭐ star the repo and share feedback!
