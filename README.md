# Airline Passenger Satisfaction Prediction

## Overview
This project was developed during my internship to predict airline passenger satisfaction using machine learning models. The work was completed for a company that provides services to a major airline. The goal was to identify key drivers of customer satisfaction and build predictive models to assist in enhancing customer experiences.

The project explores multiple machine learning algorithms, evaluates their performance, and highlights actionable insights for improving airline operations.

---

## Features
- **Dataset**: A comprehensive dataset containing features like inflight services, online boarding, and flight delays, alongside satisfaction labels.
- **Models**:
  - Baseline models: Logistic Regression, Decision Tree
  - Advanced models: Random Forest, XGBoost, MLP Classifier
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score, and ROC-AUC

---

## Business Applications
The insights and models developed provide significant value to the service provider for the airline. Below are the primary applications:
1. **Customer Satisfaction Prediction**: Predict satisfaction levels in real-time to enable proactive responses to dissatisfied passengers.
2. **Service Improvement**: Feature importance analysis identifies areas such as inflight entertainment and online boarding for targeted improvements.
3. **Personalized Engagement**: Enable the creation of personalized offers and enhanced services for high-value customers.

---

## Models and Results
| Model                | Accuracy | Precision | Recall | F1-Score |
|----------------------|----------|-----------|--------|----------|
| Logistic Regression  | 87.5%    | 87.5%     | 87.5%  | 87.5%    |
| Decision Tree        | 94.3%    | 94.3%     | 94.3%  | 94.3%    |
| Random Forest        | 96.2%    | 96.2%     | 96.2%  | 96.2%    |
| XGBoost              | 96.3%    | 96.3%     | 96.3%  | 96.3%    |
| MLP Classifier       | 95.6%    | 95.6%     | 95.6%  | 95.6%    |

**Best Model**: XGBoost was the top-performing model, achieving a 96.3% score across all evaluation metrics.

---

## Key Insights
- **Feature Importance**:
  - The most critical factors influencing satisfaction are inflight entertainment, online boarding, and inflight service quality.
  - These insights enable targeted improvements in customer service.
- **Scalability**:
  - The models are designed to scale and can be deployed in real-time systems via APIs for operational use.

---
