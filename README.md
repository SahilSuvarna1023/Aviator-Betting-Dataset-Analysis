# Aviator-Betting-Dataset-Analysis
This project analyzes the Aviator betting dataset, focusing on profitable betting strategies using historical data, machine learning, and statistical analysis.
📖 Overview

This project analyzes betting payouts using machine learning, fraud detection, and clustering. It leverages historical betting data to predict future payouts, detect anomalies, and classify betting behaviors into meaningful clusters.

📊 Key Features

Data Cleaning & Preprocessing: Handles missing values, duplicates, and formats timestamps.

Exploratory Data Analysis (EDA): Provides insights into payout distributions, trends, and correlations.

Machine Learning Models:

Random Forest & XGBoost for payout prediction.

Performance Evaluation using MAE, RMSE, and R² score.

Fraud Detection: Uses Isolation Forest to flag suspicious payouts.

Clustering Analysis: Applies K-Means to group users based on betting behavior.

Visualizations: Time series trends, correlation heatmaps, fraud detection plots, and clustering insights.

🗂 Dataset

The dataset consists of betting transactions with the following key features:

id: Unique identifier for each transaction.

created_at: Timestamp of the bet.

payout: Amount won (target variable).

app: Betting platform or app used.

Feature Engineered Variables: Lag payouts for ML models.

🚀 How to Use

Upload the dataset (.csv).

Run the script for data cleaning and feature engineering.

Train ML models and evaluate predictions.

Detect fraudulent transactions.

Perform clustering to understand betting patterns.

📊 Results & Insights

Predicting high payout events can optimize betting strategies.

Fraud detection helps flag suspicious activities.

Clustering reveals different betting behaviors.

🛠 Technologies Used

Python (Pandas, NumPy, Matplotlib, Seaborn)

Machine Learning (Scikit-Learn, XGBoost, Random Forest)

Data Visualization (Seaborn, Matplotlib)

📌 Future Improvements

Implementing deep learning models for better predictions.

Incorporating real-time data streams for live betting analysis.

Enhancing fraud detection using advanced anomaly detection techniques.

