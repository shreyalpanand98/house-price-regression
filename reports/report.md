# Customer Shopping Behavior Analysis — Exploratory Data Analysis Report

## 1. Introduction

This project explores customer shopping behavior using exploratory data analysis (EDA) to understand **spending patterns**, **revenue concentration across product categories**, and the **impact of demographic and promotional factors** on purchase amounts. The objective is to derive actionable insights that can inform marketing strategy, pricing decisions, and customer segmentation.

---

## 2. Dataset Overview

The dataset consists of individual customer transactions, where each row represents a purchase and includes information such as:
- Customer demographics (e.g., age, gender)
- Product category
- Purchase amount
- Discount application status

The analysis focuses on understanding how these factors relate to **purchase amount**, a key business metric.

---

## 3. Methodology

The analysis followed a structured EDA workflow:

### Data Cleaning
- Standardized column names for consistency
- Checked for missing values and validated data types
- Ensured numerical variables were suitable for analysis

### Exploratory Analysis
- Compared average purchase amounts across demographic groups
- Analyzed revenue distribution by product category
- Examined the effect of discounts on purchase behavior
- Investigated the relationship between age and spending

### Visualization
- Bar charts for group comparisons
- Box plots to analyze spending distributions
- Scatter plots to assess correlation patterns

---

## 4. Key Analyses & Insights

### 4.1 Spending by Gender

Average purchase amounts were found to be **very similar across genders**, with only marginal differences. This indicates that gender alone has **low explanatory power** for predicting purchase amount.

**Insight:**  
Gender may be more effective as a secondary feature when combined with behavioral variables rather than as a primary segmentation criterion.

---

### 4.2 Revenue by Product Category

Revenue distribution across product categories is **highly skewed**, with a small subset of categories contributing a disproportionately large share of total revenue.

**Insight:**  
This Pareto-like distribution suggests that product category is a **high-impact driver** of revenue and should be prioritized in both analytical modeling and business strategy.

---

### 4.3 Discount Impact on Purchase Amount

Box plot analysis shows that purchase amount distributions for discounted and non-discounted transactions have **similar medians and interquartile ranges**, indicating substantial overlap.

**Insight:**  
While discounts may influence purchase likelihood, they do not significantly increase **per-transaction spending** on average.

---

### 4.4 Age vs Purchase Amount

Scatter plot analysis reveals **no strong correlation** between age and purchase amount. High and low spending values appear across nearly all age groups.

**Insight:**  
Age alone does not meaningfully explain variance in spending behavior and is unlikely to be a strong standalone predictor in downstream modeling tasks.

---

## 5. Business Implications

Based on the analysis:

- **Product category** should be a primary focus for revenue optimization and predictive modeling
- **Behavioral features** are likely more informative than basic demographic attributes
- **Discount strategies** should be targeted and data-driven rather than uniformly applied
- **Customer segmentation** should emphasize purchasing behavior over demographics alone

---

## 6. Limitations

- The analysis is exploratory and does not establish causality
- Customer-level behavioral history is not available
- Advanced modeling and interaction effects were intentionally excluded to maintain interpretability

---

## 7. Conclusion

This project demonstrates a structured approach to exploratory data analysis, combining descriptive statistics, visual analysis, and business reasoning. The findings highlight the importance of moving beyond demographic variables toward **behavior-driven insights**, providing a strong foundation for future predictive modeling and customer analytics.

---

## 8. Tools & Technologies

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Exploratory Data Analysis (EDA)
