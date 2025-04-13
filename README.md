# 💳 Credit Score Classification

A machine learning project that predicts an individual's credit score based on financial and demographic data. The project explores key features influencing creditworthiness using statistical analysis, advanced visualizations, and a Random Forest Classifier model.

## 📊 Project Overview

This project walks through:
- Exploratory data analysis using Plotly
- Feature engineering to improve model performance
- Model training using Random Forest and comparisons with other models
- Feature importance visualization using SHAP
- Interactive prediction using user input

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas & NumPy (data manipulation)
- Scikit-learn (modeling)
- Plotly (visualizations)
- SHAP (model interpretability)
- Matplotlib & Seaborn
- Jupyter Notebook / Google Colab

---

## 📂 Dataset

The dataset includes information such as:
- Annual Income
- Monthly Inhand Salary
- Number of Bank Accounts & Credit Cards
- Interest Rate
- Delayed Payments, Credit History
- Investment & Loan Data
- Credit Score labels: `Poor`, `Standard`, `Good`

**Source**: Provided as `train.csv` in the repo

---

## 🧠 Feature Engineering Highlights

Created new features to enhance model performance:
- `Debt_to_Income_Ratio`
- `Loan_to_Credit_Card_Ratio`
- `Monthly_Savings`

These features help the model better understand the individual's financial health.

---

## 📈 Model Training

The default classifier is `RandomForestClassifier` from scikit-learn, achieving strong performance on the test set.

---

## 🎯 Predict Your Credit Score

The project includes an interactive section where you can input:
- Income, salary, debt, loans, etc.
- The model will predict your credit score category.

---

## 🖼️ Sample Visualizations

- Box plots for credit score distribution across various features
- Feature importance heatmap

---

## 🚀 How to Run

1. Clone the repo:
```bash
git clone https://github.com/yourusername/credit-score-classification.git
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the notebook or Python script:
```bash
python credit_score_classification.py
```

---

## 💡 Future Work

- Streamlit-based Web App for UI
- Model deployment via Flask/Docker
- Incorporate additional data sources (e.g. location, employment length)

---
