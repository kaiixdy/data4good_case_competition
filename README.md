# 🤖 Data4Good: AI-Powered Support System for Military Families  
*Microsoft Azure | NLP | Supervised Learning | AI Ethics*  
🏆 **Top 1 in California** out of 243 teams and 1,031 students 🎉

---

## 📝 Overview

This project was developed for the **Data4Good Case Competition** hosted by Purdue University and Microsoft. Our team engineered a supervised ML system to automate the classification of 5,000+ survivor survey responses into care stages — enabling better resource allocation and more personalized support for military families.

🔍 **Problem Statement:**  
How can we use machine learning and natural language processing to classify military survivor responses into stages of care and support?

Our solution leverages structured and unstructured features from the survey to build an accurate, explainable classification system using open-source tools and Microsoft Azure infrastructure.

We placed **first in California**, competing against 240+ graduate teams across the U.S.

👉 [View the official competition site](https://business.purdue.edu/events/data4good/)

---

## 🔧 What We Did

- Built an **ensemble machine learning pipeline** using:
  - `XGBoost`, `LightGBM`, `Random Forest`, and **StackingClassifier**
  - **Text feature extraction** via `TF-IDF` and `TextBlob` sentiment analysis
  - **Polynomial interaction terms** for numeric features  
- Performed:
  - Feature engineering, missing value imputation, and label encoding
  - Model evaluation using **F1 score** and `StratifiedKFold` cross-validation  
- Deployed final predictions for evaluation on Kaggle-style test set

---

## 🧠 Tools & Skills

- **Python** (Pandas, NumPy, Scikit-learn, XGBoost, LightGBM)
- **Text Analytics** (TfidfVectorizer, TextBlob)
- **Model Stacking** (RandomForest, XGBoost, LGBM → Logistic Regression meta-learner)
- **Evaluation:** F1 Score, Cross-Validation, Label Encoding, StandardScaler

---

## 🎓 Certifications & Trainings

By participating in the competition, I completed:

- ✅ **AI-900: Microsoft Azure AI Fundamentals** Certification  
- ✅ **INFORMS Job Task Analysis (JTA) Training** – Blueprint for the CAP Exam  
- ✅ **AI Ethics Training** with PrimeAI  
- ✅ **Prediction Guard Q&A Sessions** and live expert trainings  

---

## 📁 Files

- `examples.csv` → Training dataset with labeled survey responses  
- `test.csv` → Test dataset for prediction  
- `submission.csv` → Final prediction output for leaderboard  
- `notebook.ipynb` → Full code pipeline (feature engineering + model training + predictions)

---
