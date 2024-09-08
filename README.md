# Telecom-Customer-Churn-Prediction
This project focuses on predicting the churn rate of telecom customers to help the company retain its clientele. The churn rate, or customer attrition, indicates the rate at which customers stop using the company's services over a specified period. By understanding the key factors driving churn, businesses can take corrective actions to improve customer retention.

Project Overview
Problem Statement: Telecom companies face challenges in retaining customers, often not fully understanding their needs or reasons for leaving. By predicting churn, the company can identify weak areas and optimize their offerings to reduce customer attrition.
Data Source: The dataset was obtained from Maven Analytics and contains 7,043 records with 38 columns, covering customer demographics, services, and usage patterns.
Features
CustomerID: Unique identifier for each customer.
Attributes: Includes customer demographics (gender, age, marital status), service details (internet, phone service), and usage metrics (monthly charges, tenure).
Target: Customer status, classified as Churned, Stayed, or Joined.
Models Implemented
Logistic Regression: Achieved a recall of 0.78 and an F1 score of 0.77.
Random Forest: Recall of 0.72 and F1 score of 0.75.
Support Vector Machine (SVM): Recall of 0.72 and F1 score of 0.75.
Gradient Boosting: Recall of 0.68 and F1 score of 0.73.
Key Findings
Logistic Regression emerged as the best-performing model with the highest recall and F1 score.
High monthly charges were identified as the primary reason for customer churn. By adjusting prices according to customer profiles and competitor pricing, the company can improve customer retention.
Conclusion
Predicting churn is essential for the long-term success of telecom companies. This project provides insights into which customers are more likely to churn, enabling proactive strategies to retain them.
