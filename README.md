# Customer Churn Prediction & Analysis (using Python,Machine Learning and Power BI)
## 🔍 Overview
This project focuses on analyzing customer behavior data to identify factors that contribute to churn (i.e., customers leaving a service) and building a machine learning model to predict churn. It includes:
- Data exploration and visualization
- Feature engineering
- Predictive modeling using classification algorithms
- Interpretation of key drivers of churn
---
## Project Objective
The goal of this project is to analyze customer churn patterns and predict churn using machine learning. A Random Forest Classifier was built with 69% accuracy, and Power BI dashboards were developed to visualize key trends. This helps businesses identify at-risk customers and improve retention strategie##s.

---

## 🛠️ Tools & Technologies used
- Power BI
- Python (Pandas, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- GitHub for version control

---

## Dataset Used:
- <a href="https://github.com/JEMIMAYUSUF/Customer-churn-analyzing/blob/main/Large_Customer_Churn_Prediction.csv">View DataSet</a>

---

## Questions (KPIs):
- What is the total number of customers? 
- What is the overall churn rate (%) among customers? 
- What is the customer retention rate (%)?
- What is the average customer tenure (in months)? 
- What is the average internet usage (GB) of customers? 
- How does the contract type (multi-year, yearly, monthly) impact customer churn?
- What are the preferred payment methods among churned customers? 
- How does the churn rate (%) differ by gender? 
- What is the overall churn rate (%) among customers? 
- How does the churn rate (%) vary based on subscription length (months)? 
- How does the churn rate (%) differ by gender? 
- How does internet usage (GB),customer impact churn rates?

---

## View Power BI Dashboard:
- <a href="https://github.com/JEMIMAYUSUF/Customer-churn-analyzing/blob/main/Screenshot.png">View Dashboard</a>

## visuals
![Customer Churn Analysis Dashboard Using Power BI](https://github.com/JEMIMAYUSUF/Customer-churn-analyzing/blob/main/Screenshot.png)

## 📊 Exploratory Data Analysis (EDA)

Churns-
![Churned & Retained](https://github.com/JEMIMAYUSUF/Customer-churn-analyzing/blob/main/visual_1.png)
![Churn by Gender](https://github.com/JEMIMAYUSUF/Customer-churn-analyzing/blob/main/visual_2.png)
![Churn by Location](https://github.com/JEMIMAYUSUF/Customer-churn-analyzing/blob/main/visual_3.png)
![Churn by Age Distribution](https://github.com/JEMIMAYUSUF/Customer-churn-analyzing/blob/main/visual_4.png)
![Confusion Matrix](https://github.com/JEMIMAYUSUF/Customer-churn-analyzing/blob/main/visual_5.png)


---

## 📊 Key Visualizations

| Visualization                     | Description                                 |
|----------------------------------|---------------------------------------------|
| `churn_distribution.png`         | Count plot of churned vs non-churned users |
| `internet_usage_churn.png`       | Boxplot of internet usage grouped by churn |
| `subscription_length_churn.png`  | Histogram of subscription length by churn  |
| `payment_method_churn.png`       | Count plot of payment methods by churn     |
| `call_duration_churn.png`        | Violin plot of call duration by churn      |
| `correlation_heatmap.png`        | Correlation matrix for numeric features    |
| `feature_importances.png`        | Top predictive features from model         |

1. Churn Distribution
![Churn Distribution](https://github.com/JEMIMAYUSUF/Customer-churn-analyzing/blob/main/churn_distribution.png)

2. Internet Usage vs. Churn
![Internet Usage vs. Churn](https://github.com/JEMIMAYUSUF/Customer-churn-analyzing/blob/main/internet_usage_churn.png)

3. Subscription Length and Churn
![Subscription Length and Churn](https://github.com/JEMIMAYUSUF/Customer-churn-analyzing/blob/main/subscription_length_churn.png)

4. Payment method churn
![Payment method churn](https://github.com/JEMIMAYUSUF/Customer-churn-analyzing/blob/main/payment_method_churn.png)

5. Call duration churn
![Call duration churn](https://github.com/JEMIMAYUSUF/Customer-churn-analyzing/blob/main/call_duration_churn.png)

6. Correlation heatmap
![Correlation heatmap](https://github.com/JEMIMAYUSUF/Customer-churn-analyzing/blob/main/correlation_heatmap.png)

7. Feature importances
![Feature importances](https://github.com/JEMIMAYUSUF/Customer-churn-analyzing/blob/main/feature_importances.png)

---

## 🤖 Machine Learning Model

A Random Forest classifier was used to predict churn. The model was trained on encoded customer data and evaluated for accuracy, precision, recall, and F1-score.

---

## 📌 Key Findings

- Customers with shorter subscriptions and lower internet usage are more likely to churn.
- Gender, call duration, and payment method also influence churn.
- Random Forest outperformed other models with the best prediction metrics.

---

## Project Insights:
- Analyzed 90,000+ customer records to identify key factors influencing churn.
- Built a Random Forest Classifier with 69% accuracy to predict customer churn.
- Performed Exploratory Data Analysis (EDA) and feature engineering using Python (Pandas, NumPy, Seaborn, Scikit-learn).

---

## Conclusion:
The Customer Churn Analysis revealed key factors influencing churn, such as contract type, payment method, and subscription length. By analyzing 90,000+ records, a Random Forest model     achieved 69% accuracy in predicting churn. Power BI dashboards provided insights into trends across demographics, helping businesses identify at-risk customers. The findings highlight the importance of data-driven strategies to improve customer retention and reduce churn.
