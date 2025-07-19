# 💳 Credit Card Delinquency Risk Analyzer

This project analyzes credit card customer behavior to uncover key factors leading to delinquency (default). It helps financial institutions derive actionable insights through data cleaning, exploratory data analysis (EDA), and feature engineering.

---

## 🧠 Project Objective

To identify risk patterns in credit card usage and customer profiles, enabling better credit decision-making and proactive intervention strategies.

---

## ✅ Work Completed

### 🔹 Data Cleaning
- Handled missing and inconsistent values
- Ensured correct data types
- Removed redundancies and corrected outliers

### 🔹 Exploratory Data Analysis (EDA)
- Target variable distribution analysis
- Gender, education, and marital status comparisons
- Age distribution and group analysis
- Correlation heatmaps
- Feature interactions (e.g., payment delays vs default)
- Grouped summaries for pattern discovery

### 🔹 Feature Engineering
- `TOTAL_BILL`: Sum of 6 months’ bill amounts
- `TOTAL_PAID`: Sum of 6 months’ payments
- `PAY_RATIO`: Ratio of payment to bill
- `AVG_DELAY`: Average delay over 6 months
- One-hot encoding for categorical variables

---

## 🛠️ Technologies Used

- Python (pandas, numpy, matplotlib, seaborn)
- Jupyter Notebook
- Excel (for initial exploration)
- Git & GitHub

---

## 🔍 Key Insights

- Delay in payments is strongly linked to default risk.
- Age group 30–45 shows higher likelihood of default.
- Lower `PAY_RATIO` and high `TOTAL_BILL` are key red flags.
- Education and marital status impact default probability.

---

## 🔮 Future Scope

- Apply machine learning to predict default probability
- Develop an interactive web-based risk analysis tool
- Add monthly trends and cohort-based segmentations


