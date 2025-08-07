# Churn-Behavior-Analytics
📉 Telecom churn analysis with Python &amp; visual insights. Identified key contract, payment &amp; tenure patterns affecting retention.
# 📈 Customer Churn Analysis | Teco Telecom Data

This project explores customer churn behavior for a fictional telecom company using real-world data. The goal: uncover insights that explain *why* users leave and *what* the company can do about it.

---

## 📃 Dataset Overview

- **Size:** 7,043 rows × 21 columns
- **Source:** Teco Telecom dataset (CSV)
- **Target Variable:** `Churn`
- **Key Columns:** Contract type, Payment Method, Internet Services, SeniorCitizen, Tenure, MonthlyCharges, etc.

### Data Cleaning:
- `TotalCharges` was found to contain empty strings — replaced with "0" and cast to float.
- No nulls or duplicates after cleaning.
- Binary encoded `SeniorCitizen` to Yes/No for readability.

---

## 📊 Tools & Technologies
- **Language:** Python
- **Libraries:** Pandas, NumPy, Seaborn, Matplotlib
- **Techniques:** Exploratory Data Analysis, Correlation Insights, Comparative Visualization, Customer Segmentation

---

## 🛠️ Step-by-Step Analysis

### 1. Churn Overview
- Overall churn rate: **26.5%** of customers have left.
- Pie chart and count plots were used to visualize churn distribution.

### 2. Gender & Churn
- Churn rates were **fairly equal** across gender — not a strong predictive factor.

### 3. Senior Citizen Insight
- **Senior Citizens churned at ~41%**, vs. 26% for non-seniors.
- Suggests age-based engagement strategies are needed.

### 4. Tenure Breakdown
- Customers within their **first year had 50% churn**, dropping to **15% after 3 years**.
- Long-term engagement strongly reduces churn risk.

### 5. Contract Type
- **Month-to-month:** 42% churn
- **1-year contract:** 11%
- **2-year contract:** 3%
- ✨ Long-term contracts ≪ higher retention

### 6. Payment Method
- Customers using **electronic checks** churned at **45%**
- Users paying via **credit cards / bank transfer** had 15–18% churn
- Highlights **trust** and **payment UX** as retention factors

### 7. Services & Subscriptions
- Customers with **OnlineSecurity, TechSupport, DSL** churned less
- Customers **without** optional services showed higher churn
- Having multiple services = greater loyalty

---

## 🎨 Visualizations
- Count plots for contract, payment, internet services
- Stacked bar charts for age and churn
- Pie chart for churn percentage
- Histograms for tenure and charges

All visuals created using `seaborn` and `matplotlib`, with intuitive labels and color-coded grouping.

---

## 📊 Key Business Insights

| Insight | Actionable Strategy |
|--------|---------------------|
| ⬇️ Senior citizens churn more | Tailored support & onboarding |
| ⌛ Short tenure = high churn | Early user engagement campaigns |
| 📝 Month-to-month = risky | Promote contract upgrades |
| 💳 Electronic check users churn | Promote secure digital payments |
| 📉 Lacking services = churn | Bundle value-added services |

---

## 🌟 What I Learned
- How to convert business questions into analytical workflows
- How visualization directly supports decision making
- Importance of EDA and grouping for root cause detection
- How tenure, behavior, and payment modes affect churn

---

## 📄 Business Recommendations
- Offer **discounts** for yearly contracts
- Provide **early loyalty incentives** during first 6 months
- Replace **electronic check** with auto-debit and card incentives
- Launch **senior care onboarding** with human support

---

## 📁 Project Files
```
├── Customer Churn.csv
├── churn_analysis.ipynb
├── visuals/
│   ├── tenure_histogram.png
│   └── payment_method_churn.png
└── README.md
```

---

## 👋 Let's Connect
- 📧 harsh201130@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/harsh-sharma-354379294/)
