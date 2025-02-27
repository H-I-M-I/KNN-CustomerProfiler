# KNN Customer Classification

This repository contains an implementation of the **K-Nearest Neighbors (KNN) algorithm** to classify customers into different categories based on given features. The dataset used is `CustCat.csv`, and the model is evaluated for optimal performance.

## Features
- **Data Preprocessing:** Handles data normalization using `StandardScaler()`.
- **KNN Classification:** Implements KNN for customer category prediction.
- **Hyperparameter Tuning:** Finds the best `k` value for optimal accuracy.
- **Evaluation Metrics:** Measures model performance using accuracy scores.

## Dataset
- The dataset `CustCat.csv` contains customer information and their respective categories.
- Features include demographic and behavioral attributes.
- The `CustCat` column represents the target class (customer category).

## Benefits of Customer Classification
Using KNN for customer classification offers several advantages:

1. **Personalized Marketing** – Helps in targeted promotions, personalized offers, and better customer engagement.
2. **Customer Retention & Loyalty** – Enables businesses to identify high-value customers and design loyalty programs.
3. **Product Recommendations** – Improves sales by suggesting relevant products to customers with similar behaviors.
4. **Fraud Detection & Risk Management** – Helps detect anomalies or fraudulent activities based on customer patterns.
5. **Resource Allocation & Business Strategy** – Optimizes marketing and sales efforts by focusing on high-value customer segments.
6. **Automated Decision-Making** – Reduces manual efforts in customer classification, making business processes more efficient.
7. **Improved Customer Experience** – Tailors services, communication, and pricing strategies to enhance customer satisfaction.

## Results
- The model classifies customers into distinct categories based on nearest neighbors.
- Accuracy improves by tuning the value of `k`.
