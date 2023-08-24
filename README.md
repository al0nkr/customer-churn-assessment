# Customer Churn Prediction Model

This repository contains a customer churn prediction model that aims to predict whether a customer will churn based on certain features. The dataset used for this project contains a variety of customer attributes and a binary churn label.

## Project Overview

The main goal of this project was to build a predictive model to determine whether a customer is likely to churn based on their characteristics. The project followed these general steps:

1. **Data Exploration and Preprocessing:** The initial step was to explore the dataset, understand the distribution of features, and preprocess the data for modeling. This included handling missing values, encoding categorical features, and scaling numerical features.

2. **Model Selection:** Various machine learning models were tried, including Logistic Regression, Random Forest, Gradient Boosting, and XGBoost. Each model was evaluated using cross-validation to measure its performance.

3. **Challenges with Randomized Data:** A significant challenge was encountered due to the randomized nature of the dataset. Despite trying various models and feature engineering techniques, achieving high accuracy proved difficult due to the lack of clear patterns or correlations in the data.

4. **Model Evaluation:** Each model's performance was evaluated using accuracy, precision, recall, F1-score, and confusion matrices. Cross-validation was used to estimate generalization performance.

5. **User Input Prediction:** A method was developed to take user inputs for specific features and predict whether a customer is likely to churn using the trained model. Standardization of user input was also implemented.

## Model Performance

After extensive experimentation, the best performing model achieved an accuracy of around 50%. This suggests that the dataset's random nature poses a significant challenge in building an accurate predictive model. The confusion matrices and classification reports indicate that the models are struggling to distinguish between the classes effectively.

## Conclusion

Despite rigorous efforts in exploring different models, preprocessing techniques, and feature engineering, the unpredictable and random nature of the data prevented achieving high accuracy in predicting customer churn. The lack of clear patterns and correlations among features made model tuning and optimization difficult.

While the model's accuracy remains modest, this project provides valuable insights into the challenges of working with randomized data and highlights the importance of data quality and consistency in building accurate predictive models.

Feel free to explore the code and documentation to understand the approach taken in detail.

---
