# **Bike Sharing Demand Prediction**

## **Introduction**

In many urban cities, rental bikes are an excellent way to enhance mobility comfort. However, ensuring a stable supply of rental bikes at the right time is critical. That's where predictive modeling comes in. By accurately predicting the number of bikes needed per hour, companies can allocate their services better and ensure more sufficient circulation of bikes for customers, ultimately providing the city with a better bike-sharing experience.

## **Project Overview**

This project uses machine learning algorithms such as Linear Regression, Lasso Regression, Ridge Regression, Decision Tree, Random Forest, and Gradient Boosting to predict the bike count per hour. We've also implemented feature engineering, feature selection, imputation of missing values, categorical feature encoding, outlier handling, and multicollinearity checking to ensure the models' accuracy.

Through this project, we've developed hyper-parameter tuned Gradient Boosting to predict the number of bikes that can be rented per hour by the company. The same modeling techniques can also be applied to other industries, such as transportation, e-commerce, and taxi demand prediction.

## **Project Flowchart**

Our project flowchart includes the following steps:

- Loading and diagnosing the data
- Data Cleaning
- Data Visualization
- Feature Selection
- Model Building
- Model Evaluation

## **Models Used**
We have used popular regression models such as Linear Regression, Lasso Regression, Ridge Regression, Decision Tree, Random Forest, and Gradient Boosting to determine which model provides the best deployment.

## **Key Findings**

Our analysis shows that bike rental count is mostly correlated with the time of day, with peaks at 8 am in the morning and 6 pm in the evening. Additionally, the bike rental count is high during working days compared to non-working days, and people generally prefer to bike in moderate to high temperatures and when it's a little windy. Achieved high model performance with R2 scores of 91% for Gradient Boosting GridSearchCV and 87% for Random Forest GridSearchCV, which can provide a stable supply of rental bikes to the public.

## **Conclusions**

By accurately predicting the bike demand, we can help companies provide their customers with the best bike-sharing experience without any delays. We hope our project can be helpful in the future development of the bike-sharing industry and inspire further research in the field.
