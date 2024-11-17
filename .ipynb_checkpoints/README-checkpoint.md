# Predicting Customer Airline Satisfaction using Machine Learning


### Overview
This project aims to build a machine learning model to predict customer satisfaction based on various factors related to their travel experience. The dataset includes a mix of demographic, travel, and service-related features. The goal is to help airlines improve customer experience by identifying key satisfaction drivers.

---

### Dataset
The dataset contains passenger-level data with features describing their travel experience and satisfaction levels. Below are key details:

- **Target Variable**:
  - `satisfaction`: Binary classification (`1` = Satisfied, `0` = Neutral or Dissatisfied).

- **Key Features**:
  - **Demographic**:
    - `age`
    - `Gender`
  - **Travel Information**:
    - `flight_distance`
    - `departure_delay_in_minutes`
    - `arrival_delay_in_minutes`
  - **Service Ratings**:
    - Ratings from `0` to `5` for:
      - `inflight_wifi_service`
      - `food_and_drink`
      - `seat_comfort`
      - And more.

---

### Project Steps

#### 1. Data Cleaning
- Removed unnecessary columns (e.g., unnamed index column).
- Handled missing values:
  - Imputed `arrival_delay_in_minutes` with the median.
- Ensured data type consistency:
  - Converted `arrival_delay_in_minutes` from float to integer.

#### 2. Feature Engineering
- Encoded categorical features using one-hot encoding.
- Created a binary column:
  - `customer_type_loyal` (`True` = Loyal, `False` = Disloyal).
- Dropped redundant `customer_type_disloyal Customer` column.

#### 3. Exploratory Data Analysis (EDA)
- Analyzed the target variable distribution.
  - Observed a slight class imbalance (56.55% Neutral/Dissatisfied, 43.45% Satisfied).
- Key insights:
  - Longer flights were associated with higher satisfaction.
  - Higher ratings for `online_boarding` strongly correlated with satisfaction.
  - Strong correlations existed between service-related features (e.g., `seat_comfort`, `inflight_entertainment`) and satisfaction.

---

### Next Steps

#### 4. Feature Scaling
- Normalize or scale numerical features (e.g., delays, distances) to ensure consistency for model training.

#### 5. Modeling
- **Baseline Models**:
  - Logistic Regression
  - Decision Trees
- **Advanced Models**:
  - Random Forest
  - XGBoost
  - Neural Networks
- Use cross-validation for model evaluation and performance consistency.

#### 6. Evaluation
- Evaluate models using:
  - Accuracy
  - Precision, Recall, F1-score
- Address potential class imbalance using class weights or resampling.