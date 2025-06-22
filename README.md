# 🏦 Credit Risk Modeling Using Machine Learning

This project aims to build a machine learning model that can predict the likelihood of loan default based on borrower attributes and loan characteristics. The goal is to help financial institutions assess credit risk and make informed lending decisions.

---

## 📌 Problem Statement

Credit risk is one of the major risks faced by banks and lending institutions. By predicting whether a borrower is likely to default on a loan, lenders can manage their risk more effectively. This project uses machine learning techniques to classify loan applications as high or low risk.

---

## 📊 Dataset

**Source**: [Lending Club Loan Data](https://www.kaggle.com/datasets/wordsforthewise/lending-club)

- Total records: ~2.5 million loans
- Features: Borrower demographics, credit history, loan terms
- Target: `loan_status` (binary: defaulted vs fully paid)

---

## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- scikit-learn
- XGBoost
- SHAP (Explainability)
- Streamlit (for UI)
- Matplotlib, Seaborn
- imbalanced-learn

---

## 🧪 Project Workflow

1. **Data Preprocessing**
   - Cleaning missing values
   - Feature encoding & scaling
   - Handling class imbalance

2. **Exploratory Data Analysis**
   - Correlation analysis
   - Default rate by feature groupings

3. **Model Training**
   - Logistic Regression (baseline)
   - XGBoost (best performance)
   - Evaluation using AUC-ROC, F1-score, precision/recall

4. **Model Interpretation**
   - SHAP values for global & local explainability

5. **Deployment**
   - Streamlit app to input loan features and get a risk score (optional)

---

## 🧠 Results

| Metric         | Value (sample only) |
|----------------|---------------------|
| AUC-ROC        | 0.89                |
| Precision      | 0.72                |
| Recall         | 0.84                |
| F1-Score       | 0.77                |

---

## 📈 Key Visuals

*(Add visuals here later — save your graphs as PNGs in an `/images` folder and link them)*

