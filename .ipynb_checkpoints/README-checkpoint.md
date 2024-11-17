# Predicting Customer Airline Satisfaction using Machine Learning

### Overview
This project aims to build a machine learning model to predict customer satisfaction based on various factors related to their travel experience. The dataset includes a mix of demographic, travel, and service-related features. The goal is to help airlines improve customer experience by identifying key satisfaction drivers.

### Dataset
The dataset contains passenger-level data with features describing their travel experience and satisfaction levels. Below are key details:
* Target Variable:
*     satisfaction. Binary classification (1 = Satisfied, 0 = Neutral or Dissatisfied)
* Key Features:
*     Demographic: age, gender.
*     Travel Information: flight_distance, departure_delay_in_minutes, arrival_delay_in_minutes
*     Service Ratings: Ratings from 0 to 5 for features like inflight_wifi_service, food_and_drink, seat_comfort, etc.

### Project Steps
1. Data Cleaning
2.     Removed unnecessary columns (e.g., unnamed index column).
3.     Handled missing values (arrival_delay_in_minutes imputed with the median).
4.     Ensured data type consistency (e.g., converted arrival_delay_in_minutes from float to integer).
5. Feature Engineering
6.     Encoded categorical features using one-hot encoding.
7.     Created a binary column customer_type_loyal to indicate loyal customers (True) and dropped redundant customer_type_disloyal Customer.
8. Exploratory Data Analysis
9.     Analyzed the distribution of the target variable and relationships between features and satisfaction.
10.     Key Insights:
11.         Slight class imbalance in satisfaction (56.55% Neutral/Dissatisfied, 43.45% Satisfied).
12.         Features like online_boarding and flight_distance showed strong relationships with satisfaction.
13.         Correlation heatmap revealed strong associations between service-related features and satisfaction.

### Next Steps
1. Feature Scaling
2.     Normalize or scale numerical features (e.g., delays, distances) to ensure consistency for model training.
3. Modeling
4.     Baseline Models: Logistic Regression, Decision Trees.
5.     Advanced Models: Random Forest, XGBoost, or Neural Networks
6.     Use cross-validation for model evaluation and performance consistency.
7. Evaluation
8.     Metrics: Accuracy, Precision, Recall, F1-score
9.     Address potential issues with class imbalance using class weights or resampling.