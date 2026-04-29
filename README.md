# Customer Churn Prediction (Machine Learning)

## Overview
This project predicts customer churn using machine learning techniques based on e-commerce behavioral data.

The goal is to identify customers at risk of leaving and provide insights for retention strategies.

---

## Dataset
The dataset includes:
- Customer demographics (Age, Gender, City)
- Purchase behavior (Total Spend, Items Purchased)
- Engagement metrics (Days Since Last Purchase, Rating)
- Membership type and discount usage

---

## Problem Definition
Churn is defined as customers who have not made a purchase for more than 30 days.

---

## Methodology

### 1. Data Preprocessing
- Removed missing values
- Selected key features for modeling

### 2. Feature Engineering
- Created binary churn label
- Selected behavioral features:
  - Total Spend
  - Items Purchased
  - Average Rating
  - Age

### 3. Model Building
- Random Forest Classifier
- Train-test split (80/20)

### 4. Model Evaluation
- Accuracy
- Confusion Matrix
- ROC Curve

---

## Results

- Model achieved high predictive performance
- ROC curve shows strong classification ability
- Identified key drivers of churn behavior

---

## Key Insights
- Customers with lower engagement are more likely to churn
- Spending and purchase frequency are strong indicators of retention
- Early detection of churn risk enables targeted marketing

---

## Business Impact
This model helps:
- Identify at-risk customers early
- Improve retention strategies
- Increase customer lifetime value

---

## Tools & Technologies
- Python (pandas, sklearn)
- Machine Learning (Random Forest)
- Data Visualization (matplotlib, seaborn)

---

## Future Improvements
- Add more behavioral features
- Use advanced models (XGBoost)
- Deploy as a real-time prediction system
