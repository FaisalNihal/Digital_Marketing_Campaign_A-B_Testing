

# 📊 A/B Testing on SEO/Digital Marketing Campaign Data

## 📝 Project Overview

This project aims to analyze the performance of two SEO/Digital Marketing campaigns (Group A and Group B) using **A/B Testing** techniques in Python. The goal is to determine if there is a **statistically significant difference** between the campaigns across key performance metrics such as:

* **Purchase**
* **Impression**
* **Earning**
* **Click**

Additionally, through **feature engineering**, two new metrics were created for deeper insights:

* **Conversion Rate** = Purchase / Click
* **Earning per Purchase** = Earning / Purchase

The project follows the statistical methodology of A/B Testing, including:

* Normality testing (Shapiro-Wilk Test)
* Homogeneity testing (Levene’s Test)
* Statistical hypothesis testing (Independent Samples t-Test or Mann-Whitney U Test, based on data characteristics)

---

## 🗂️ Dataset

The dataset consists of the following variables observed over a month for two marketing campaigns:

| Variable   | Description                          |
| ---------- | ------------------------------------ |
| Purchase   | Number of purchases                  |
| Impression | Number of times the ad was displayed |
| Earning    | Total revenue generated              |
| Click      | Number of clicks                     |

---

## 🚀 A/B Testing Workflow

### 1️⃣ Testing the Normality Assumption

* **Shapiro-Wilk Test**: Check if the data for each metric follows a normal distribution.
* **Box Plot Analysis**: Visual inspection for outliers.

### 2️⃣ Testing the Homogeneity of Variance

* **Levene’s Test**: Check if variances are equal between groups (only for normally distributed data).

### 3️⃣ Hypothesis Testing

* **Independent Samples t-Test** (if normality holds)
* **Mann-Whitney U Test** (if normality does not hold)

---

## 🧮 Feature Engineering

Two additional features were created to enrich the analysis:

1. **Conversion Rate (Purchase / Click)**: Indicates how well clicks convert to purchases.
2. **Earning per Purchase (Earning / Purchase)**: Indicates the average revenue per purchase.

---

## 📊 Results & Findings

### 🔎 Key Insights:


### **Final Results of A/B Testing:**

* **Impression:**
  **Group B** performs better (higher impressions).

* **Click:**
  **Group A** performs better (higher clicks).

* **Purchase:**
  No significant difference between Group A and Group B.

* **Earning:**
  **Group B** performs better (higher earnings).

* **Conversion Rate:**
  **Group B** performs better (higher conversion rate).

---

### **Overall Conclusion:**

* **Group B is better for overall performance** (higher impressions, earnings, and conversion rate).
* **Group A** is better if the focus is on **clicks**.
* **Purchases** are similar in both groups.





## 🛠️ Technologies & Libraries

* **Python**
* **Pandas**: Data manipulation
* **SciPy & Statsmodels**: Statistical tests
* **Seaborn & Matplotlib**: Data visualization

---
