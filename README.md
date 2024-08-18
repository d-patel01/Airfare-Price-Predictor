# Airfare Price Prediction Using Machine Learning

## Project Overview

This project focuses on predicting airfare prices using machine learning techniques. By analyzing historical data from various airlines and flight routes, the goal is to provide a model that helps consumers make informed decisions about when to book their flights.

## Objectives

- The objective is the make accurate airfare predictions based on existing airfare prices.

## Methodology

1. **Data Collection & Cleaning:**
   - The dataset used in this project contains 10,683 entries and 11 features, including airline names, flight routes, departure and arrival times, total stops, and airfare prices. The data was cleaned to handle missing values and outliers, and necessary transformations were applied.

2. **Feature Engineering:**
   - Additional features were engineered to capture relevant aspects of the data, such as the number of days until departure, whether the flight was during a holiday period, and time-based features like hour of departure.

3. **Exploratory Data Analysis (EDA):**
   - EDA was performed to uncover insights such as the influence of booking time on price, the effect of different airlines, and the impact of specific routes on pricing. Visualizations and statistical tests were used to guide feature selection and model choice.

4. **Model Training & Evaluation:**
   - Several machine learning models were trained, including linear regression, decision trees, Random Forest, and distance based models. The models were evaluated based on metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE), with cross-validation to ensure model robustness.

## Conclusion

The Airfare Price Prediction project successfully developed a machine learning model that provides accurate predictions of airline ticket prices. The model achieved a **training score** of `0.9508`, indicating strong performance during training.

In terms of evaluation metrics, the model produced an **Adjusted R-squared** of `0.8100`, which suggests a good fit to the data. The error metrics were as follows:

- **Mean Absolute Error (MAE):** `1183.28`
- **Mean Squared Error (MSE):** `3729872.29`
- **Root Mean Squared Error (RMSE):** `1931.29`

These results highlight the model's effectiveness in predicting airfare prices with a reasonable degree of accuracy. The project underscores the importance of thorough data preprocessing, feature engineering, and rigorous model evaluation in developing reliable predictive models.

