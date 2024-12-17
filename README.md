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

## Models and Results
| Model                | Accuracy | Precision | Recall | F1-Score |
|----------------------|----------|-----------|--------|----------|
| Logistic Regression  | 87.5%    | 87.5%     | 87.5%  | 87.5%    |
| Decision Tree        | 94.3%    | 94.3%     | 94.3%  | 94.3%    |
| Random Forest        | 96.2%    | 96.2%     | 96.2%  | 96.2%    |
| XGBoost              | 96.3%    | 96.3%     | 96.3%  | 96.3%    |
| MLP Classifier       | 95.6%    | 95.6%     | 95.6%  | 95.6%    |

---

## Applications and Insights

### Best Model
After extensive evaluation, the **XGBoost classifier** emerged as the best-performing model, achieving a **96.3% score** across key evaluation metrics: accuracy, precision, recall, and F1-score. Its robustness and ability to handle complex relationships between features make it an ideal candidate for deployment to address the airline's needs.

### Business Applications
As part of this internship project, the insights and models developed can provide significant value to the customer, who serves as a key service provider for the airline. Below are the primary applications of this work:
1. **Customer Satisfaction Prediction**:
   - The XGBoost model can be integrated into the customer’s systems, with compatibility for the airline's CRM, to predict customer satisfaction in real-time and proactively address passenger concerns.
2. **Service Improvement**:
   - The feature importance analysis highlights that reason for travel, quality of online boarding options, and inflight wifi service are major drivers of satisfaction. By focusing on improving these areas, the airline can enhance overall customer experiences.
3. **Personalized Engagement**:
   - By identifying passengers likely to be dissatisfied, the airline can offer personalized services, such as exclusive offers or targeted interventions, to improve retention and loyalty.

### Ethical Considerations
- **Fairness and Transparency**:
  - The model should make unbiased predictions across diverse customer demographics, ensuring equitable treatment for all passengers.
- **Regular Auditing**:
  - Frequent reviews of model predictions and feature importance should be conducted to detect and mitigate potential biases.

### Deployment Recommendations
To maximize the business value of this project, the following steps are recommended:
1. **Model Deployment**:
   - Deploy the XGBoost model via a **cloud-based API** that integrates seamlessly with the customer’s systems.
   - Ensure compatibility with the airline’s CRM system to enable real-time satisfaction predictions during booking or flight operations.
2. **Collaboration**:
   - Work closely with the customer’s IT team to ensure proper integration, scalability, and monitoring of the deployed model.
3. **Future Enhancements**:
   - Include additional features in the dataset, such as loyalty program membership and weather conditions, to further improve model predictions.
   - Implement a continuous learning pipeline to retrain the model periodically with updated data.
   - Explore additional advanced models or ensemble techniques for potentially higher performance.
