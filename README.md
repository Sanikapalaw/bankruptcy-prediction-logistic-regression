# 🏦 Bankruptcy Prediction Using Logistic Regression

### 📊 A Comprehensive Evaluation of Accuracy, Precision, Recall, F1 Score, and ROC Curve on the American Bankruptcy Dataset

---

## 📌 Project Overview

This capstone project aims to **predict corporate bankruptcy** using a **Logistic Regression model** applied to the **American Bankruptcy Dataset**. It focuses not only on building a predictive model, but also on critically analyzing its performance using key evaluation metrics like **Accuracy**, **Precision**, **Recall**, **F1 Score**, and the **ROC Curve**.

---

## 🧠 Problem Statement

Corporate bankruptcy can severely impact investors, creditors, and employees. Predicting bankruptcy based on financial indicators can enable businesses and stakeholders to take preventive action. This project seeks to classify companies as **bankrupt** or **non-bankrupt** based on financial features.

---

## 📁 Dataset

- **Source**: American Bankruptcy Dataset (cleaned version)
- **Target Variable**: `status_label` (0 = Non-Bankrupt, 1 = Bankrupt)
- **Key Features**: `total_assets`, `total_liabilities`, `current_ratio`, `cash_flow`, `net_income`, `gross_margin`, etc.

---

## 🛠️ Tools & Technologies

- **Language**: Python
- **Libraries**: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Scikit-learn`
- **Platform**: Google Colab

---

## 🔬 Exploratory Data Analysis (EDA)

The dataset was analyzed through:
- 🔹 Histograms to explore distributions
- 🔹 Boxplots to detect outliers
- 🔹 Countplots to observe class imbalance
- 🔹 KDE plots for feature-class comparison
- 🔹 Pairplots for pairwise feature relationships
- 🔹 Heatmap to examine feature correlations

---

## 🧪 Model Building

We applied **Logistic Regression** as the baseline classification model. The data was split into training and testing sets (70/30 split) and the model was trained using Scikit-learn’s `LogisticRegression`.

---

## 📈 Evaluation Metrics

The model was evaluated using:
- ✅ **Confusion Matrix**
- ✅ **Accuracy**
- ✅ **Precision**
- ✅ **Recall**
- ✅ **F1 Score**
- ✅ **ROC Curve & AUC Score**

---

## 📉 Key Results

| Metric      | Value     |
|-------------|-----------|
| Accuracy    | ~10.93%   |
| Precision   | 40%       |
| Recall      | ~0.62%    |
| F1 Score    | ~0.012    |
| AUC (ROC)   | Low       |

The model shows **strong bias toward non-bankrupt companies**, with extremely low recall — indicating it's missing most actual bankruptcies.

---

## 📌 Business Insights

- 🔍 **High class imbalance** led to underperformance in identifying bankruptcies.
- ⚠️ **Low recall** is dangerous in financial risk prediction; missing a risky firm can have huge consequences.
- 💡 Better results may be achieved using:
  - **SMOTE / Undersampling**
  - **Feature scaling**
  - **Advanced models like Random Forest / XGBoost**
  - **Cross-validation & hyperparameter tuning**

---

## ✅ Conclusion

Logistic Regression, though interpretable, **did not perform well** on this dataset due to **class imbalance** and **model limitations**. This highlights the importance of using the **right evaluation metrics** (not just accuracy) and **addressing data imbalance** in sensitive domains like bankruptcy prediction.

---

## 📚 Future Work

- Apply **ensemble methods** (Random Forest, XGBoost)
- Use **SMOTE** to balance classes
- Add **cross-validation** and **hyperparameter tuning**
- Explore **feature engineering** and **domain-specific indicators**

---

## 🤝 Connect With Me

If you work in data analytics, financial modeling, or machine learning — let’s connect and share insights!  
🔗 [LinkedIn](https://www.linkedin.com/in/sanika-palaw-7583a3289)

---

## 🔖 Tags

`#MachineLearning` `#LogisticRegression` `#CapstoneProject` `#BankruptcyPrediction` `#DataScience` `#BusinessAnalytics`
