#  Kaggle House Price Prediction Competition

### Project Overview
 - This repository contains my solution for the Kaggle House Price Prediction competition. The objective of this competition was to predict house prices based on a set of      features using regression techniques. I participated in this competition, implemented various regression models, and achieved a rank of 3200 with a score of 0.196. This     README provides an overview of the project, the data, the models used, and how to reproduce the results.

### Dataset
- https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques
- It includes a training set and a test set, each with various features related to houses.

### Data Preprocessing
Before modeling, I conducted thorough data preprocessing, which included handling missing values, feature engineering, and encoding categorical variables. The preprocessed data was then split into training and validation sets.

### Models
I experimented with several regression models to predict house prices. Here are the models I tried:

- Ridge Regression: Used to mitigate multicollinearity and overfitting.
- Random Forest Regression: Provided the best R-squared value during experimentation.
- XGBoost Regression: An ensemble model.
- Support Vector Regression (SVR): Explored SVR as it can handle non-linear relationships.

After evaluating these models, I selected Random Forest Regression as the final model due to its superior performance.

### Results
My final model achieved an R-squared value of 0.196 on the Kaggle competition leaderboard, resulting in a rank of 3200 out of 4300. While the model performed well, there is always room for improvement, and further feature engineering could potentially enhance the results.
