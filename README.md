# 🛒 Customer Shopping Behavior Analysis

*A Data Analytics Project Using Python, SQL (BigQuery), and Tableau*

## 📌 Overview

This project analyzes **customer shopping behavior** using a dataset of
**3,900 transactions**. The objective is to understand spending
patterns, customer segments, product preferences, and subscription
behavior. These insights help businesses improve their marketing
strategies, optimize product offerings, and strengthen customer
retention.

## 📊 Dataset Summary

**Total Rows:** 3,900\
**Total Columns:** 18

### **Key Feature Categories**

-   **Customer Demographics:** Age, Gender, Location, Subscription
    Status\
-   **Purchase Details:** Item Purchased, Category, Purchase Amount,
    Season, Size, Color\
-   **Shopping Behavior:** Discount Applied, Promo Code Used, Previous
    Purchases, Purchase Frequency\
-   **Review & Delivery:** Review Rating, Shipping Type\
-   **Missing Values:** 37 missing in `review_rating`

## 🐍 Exploratory Data Analysis (Python)

### ✔️ Data Loading & Cleaning

-   Imported dataset using **pandas**
-   Checked structure with `.info()` and `.describe()`
-   Imputed missing review ratings using **median rating per product
    category**
-   Standardized column names to **snake_case**

### ✔️ Feature Engineering

-   Created `age_group` using binned age values\
-   Extracted `purchase_frequency_days`\
-   Removed redundant `promo_code_used` after consistency checks

## 🧠 SQL Analysis (BigQuery)

Business questions answered with SQL: 1. Revenue by Gender\
2. High-Spending Discount Users\
3. Top 5 Products by Average Rating\
4. Standard vs Express Shipping: Spending Comparison\
5. Subscribers vs Non-Subscribers Revenue Analysis\
6. Products Most Dependent on Discounts\
7. Customer Segmentation: New, Returning, Loyal\
8. Top 3 Products Within Each Category\
9. Repeat Buyers and Subscription Likelihood\
10. Revenue Contribution by Age Group

## 📈 Tableau Dashboard

An interactive Tableau dashboard was built to visualize:\
- Revenue breakdowns\
- Gender- and age-based patterns\
- Product ratings\
- Shipping preferences\
- Customer segmentation\
- High-value customers

## 💡 Business Recommendations

-   Strengthen subscription strategy\
-   Improve loyalty programs\
-   Review discount policies\
-   Optimize product positioning\
-   Target marketing to key demographics

## 🛠 Tools & Technologies

  Category          Tools
  ----------------- ---------------------------------------------
  Programming       Python (pandas, numpy)
  Database          Google BigQuery (SQL)
  Visualization     Tableau
  Version Control   Git & GitHub
           

## 🚀 Future Improvements

-   Predictive modelling\
-   Clustering-based segmentation\
-   NLP-based review analysis\
-   Automating dashboard refresh workflows
