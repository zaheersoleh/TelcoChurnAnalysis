# Customer Churn Prediction Project

## Overview
This project aims to predict customer churn for a telecommunications company using machine learning techniques. The dataset contains various customer attributes such as demographics, services subscribed, tenure, and churn status.

## Dataset
The dataset consists of several Excel files:
- CustomerChurn.xlsx
- Telco_customer_churn.xlsx
- Telco_customer_churn_demographics.xlsx
- Telco_customer_churn_location.xlsx
- Telco_customer_churn_population.xlsx
- Telco_customer_churn_services.xlsx
- Telco_customer_churn_status.xlsx
- ~$Telco_customer_churn_status.xlsx
- ~$CustomerChurn.xlsx

Each file contains different aspects of customer data, including customer information, demographics, services subscribed, location, and churn status.

## Contents
- **Data Cleaning**: The dataset underwent cleaning to handle missing values, duplicates, and inconsistencies.
- **Exploratory Data Analysis (EDA)**: Exploratory data analysis was performed to gain insights into the dataset through visualizations and summary statistics.
- **Feature Engineering**: New features were created, and categorical variables were encoded for model training.
- **Model Building**: Logistic Regression was employed to predict customer churn based on the features.
- **Evaluation**: The model achieved an accuracy of approximately 80.76% on the test data. Precision, recall, and F1-score were computed for further evaluation.

# Predicting Customer Churn

Predicting customer churn is vital for businesses to retain customers and sustain revenue streams. This README outlines two common approaches to predicting customer churn: Machine Learning Models and Survival Analysis.

## Machine Learning Models:

Machine learning models leverage historical customer data to forecast future churn. The process involves several steps:

1. **Data Collection:** Gather relevant customer data including demographics, purchase history, usage patterns, and customer service interactions.

2. **Data Preprocessing:** Clean and prepare the data by handling missing values, encoding categorical variables, and scaling numerical features.

3. **Feature Engineering:** Create or transform features to provide additional insights into customer behavior.

4. **Model Selection:** Choose an appropriate algorithm (e.g., logistic regression, decision trees, random forests) and train it using historical data. Evaluate performance using metrics like accuracy, precision, recall, and ROC-AUC.

5. **Deployment:** Deploy the trained model for real-time churn predictions in business operations. Regularly update the model with new data for ongoing accuracy.

## Survival Analysis:

Survival analysis specializes in time-to-event data, making it suitable for predicting customer churn. The approach involves:

1. **Data Preparation:** Collect and preprocess customer data, including start date (became a customer) and end date (churned or last observed).

2. **Kaplan-Meier Estimation:** Calculate the Kaplan-Meier survival curve, illustrating the probability of customers surviving (not churning) over time.

3. **Cox Proportional-Hazards Model:** Utilize advanced models to assess factors impacting churn rates over time.

4. **Prediction:** Forecast the likelihood of individual customers churning at specific future intervals.

5. **Continuous Monitoring:** Update analyses with new data to refine predictions and identify churn risks.

## Combining Approaches:

Both methods offer valuable insights into customer behavior. Businesses can use a combination of machine learning models and survival analysis for comprehensive churn prediction. The choice depends on specific business needs, available data, and the complexity of the churn prediction problem.

By leveraging these techniques, businesses can proactively address churn, retain customers, and optimize revenue streams.

## Conclusion
Customer churn prediction is vital for businesses to retain customers and enhance profitability. The developed logistic regression model shows promising results in identifying potential churners based on various customer attributes. Further model refinement and optimization can lead to better predictive performance.
