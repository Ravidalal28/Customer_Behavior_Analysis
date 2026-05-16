🛒 Customer Behavior Analysis & Segmentation

📌 Project Overview

This project focuses on analyzing customer transaction data to understand purchasing behavior, identify customer segments, and detect churn risk patterns. Using data cleaning, feature engineering, exploratory data analysis (EDA), and K-Means clustering, the project provides actionable business insights for improving customer engagement and retention.

The analysis is based on the Kaggle dataset:

🔗 Dataset: https://www.kaggle.com/datasets/bhanupratapbiswas/customer-behavior-analysis

🎯 Objectives:

Clean and preprocess customer transaction data

Engineer meaningful behavioral features

Segment customers using clustering (K-Means)

Analyze churn patterns across segments

Visualize purchase behavior and trends

Provide actionable business recommendations

🧰 Tech Stack

Python 🐍,
Pandas,
NumPy,
Matplotlib,
Seaborn,
Scikit-learn (KMeans, StandardScaler)


📊 Project Workflow

1. Data Cleaning
Standardized column names
Handled missing values
Converted categorical variables (churn, returns) into numeric format
Ensured numeric consistency for analysis
2. Feature Engineering
Created new feature:
Average Spend per Item = Total Purchase Amount / Quantity
Handled infinite and missing values
3. Exploratory Data Analysis (EDA)
Distribution of purchase amounts
Quantity distribution
Churn rate visualization
Age distribution
Correlation analysis
4. Customer Segmentation
Applied StandardScaler for normalization
Used Elbow Method to determine optimal clusters
Applied K-Means Clustering (k=4)
Assigned customers into behavioral segments
5. Segment Profiling
Analyzed each cluster based on:
Product price
Quantity purchased
Total purchase amount
Returns rate
Churn rate


📈 Key Visualizations

Purchase amount distribution

Customer segmentation scatter plot

Churn distribution across clusters

Return rate by segment

Correlation heatmap

Pairplot of key variables


💡 Key Insights

High-spending customers represent the most valuable segment

Customers with higher return rates are more likely to chur

Low purchase behavior strongly correlates with churn

Distinct behavioral clusters exist among customers

Customer segmentation enables targeted marketing strategies


📌 Business Recommendations

🎁 Launch loyalty programs for high-value customers

📉 Re-engage churn-risk customers with personalized offers

🔧 Improve product quality to reduce returns

🎯 Use targeted marketing campaigns for each segment

🔄 Implement product recommendation systems for cross-selling


👨‍💻 Author

Ravi 
Data Science / Machine Learning Project
