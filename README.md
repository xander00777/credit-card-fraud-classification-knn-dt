# credit-card-fraud-classification-knn-dt
This project focuses on detecting fraudulent credit card transactions using machine learning models.

💳 Credit Card Fraud Detection using KNN and Decision Tree
📘 Overview

This project focuses on detecting fraudulent credit card transactions using machine learning models.
The notebook compares the performance of two classification algorithms — K-Nearest Neighbors (KNN) and Decision Tree Classifier — to identify fraudulent transactions from a highly imbalanced dataset.

The aim is to help financial institutions improve their fraud detection pipelines through explainable and efficient ML models.

🧠 Objective

To classify transactions as fraudulent or non-fraudulent using supervised learning methods and evaluate which model provides the best balance between accuracy and false positive rate.

🧩 Dataset

Dataset Source: Kaggle — Credit Card Fraud Detection Dataset

Records: 284,807 transactions

Fraudulent Cases: 492 (~0.17% of total)

Features:

28 anonymized numerical features (V1–V28) obtained from PCA

Time and Amount features

Target variable: Class (1 = Fraud, 0 = Non-Fraud)

⚙️ Methodology
🔹 Data Preprocessing

Loaded and explored dataset

Checked for missing values and class imbalance

Scaled features using StandardScaler

Split dataset into train and test sets (e.g., 80:20)

🔹 Model Training

Implemented and trained two models:

K-Nearest Neighbors (KNN) — distance-based classification

Decision Tree Classifier — tree-based model with tunable depth and split criteria

🔹 Evaluation Metrics

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

ROC–AUC Curve

📊 Results
| Model             | Accuracy | Precision | Recall   | F1-Score | ROC–AUC   |
| ----------------- | -------- | --------- | -------- | -------- | --------- |
| **KNN**           | ~99%     | High      | Moderate | High     | Excellent |
| **Decision Tree** | ~99%     | High      | High     | High     | Excellent |


