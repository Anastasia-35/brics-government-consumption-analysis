# BRICS Government Consumption Analysis

## 📊 Project Overview
This project presents a statistical analysis of **general government final consumption expenditure (% of GDP)** across BRICS countries:
- Brazil
- Russian Federation
- India
- China
- South Africa

The analysis focuses on identifying differences in government spending patterns using descriptive statistics, trend visualizations, and inferential statistical testing.

---

## 📁 Dataset
- Source: World Bank economic indicators (via Kaggle)
- Time period: 1970–2020
- Key indicator:
  - General government final consumption expenditure (% of GDP)

---

## 🧪 Methodology
The following steps were performed:
- Data cleaning and preprocessing
- Filtering BRICS countries
- Panel data transformation
- Descriptive statistical analysis
- Visualization of trends over time
- One-way ANOVA to test mean differences
- Tukey HSD post-hoc test to identify country-level differences

---

## 📈 Key Findings
- Government consumption differs significantly across BRICS countries (ANOVA, p < 0.001)
- India shows the highest average government consumption as a percentage of GDP
- Russia and South Africa are not significantly different from each other
- Clear country-specific spending trends are observed over time

---

## 🛠️ Tools & Libraries
- Python
- pandas
- matplotlib
- seaborn
- scipy
- statsmodels

---

## ▶️ How to Run
Install dependencies:
```bash
pip install -r requirements.txt
