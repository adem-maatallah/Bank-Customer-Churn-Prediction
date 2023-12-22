# Bank-Customer-Churn-Prediction
The ultimate goal of churn analysis is to reduce churn and increase profits. As more customers stay longer, revenue should increase, and profits should follow.

The main objective of this model is to predict if a customer is going to churn in order to:

    -Improve the customer experience
  
    -Optimize the banks products and services
  
    -Customer retention (opposite of churn)

Focusing on maximize the recall score which in our case maximize the True Positives (How many customers did really churn) and minimizing the False Negatives (How many customers we predicted they wouldn't churn but they did) 

What data is being used for the model? A dataset which contain some customers who are withdrawing their account from the bank due to some loss and other issues with the help this data we try to analyse and maintain accuracy.

How was the data obtained? This dataset was obtained from Kaggle, and it's open for public use

What are known issues in the data? Some of the features are not very predictive, so feature engineering was a challenging task.Also, there's a class imbalance in the target

How did you alter the data (transformations, imputations, other data cleaning techniques applied, etc.)? I encoded the geography and gender column, split my features into numerical and categorical (numerically-encoded), normalized the numerical data using a standard scaler, then applied polynomial feature transformation on ('CreditScore', 'Age', 'Tenure', 'EstimatedSalary'), and finally selected the the polynomial features with the highest F-score with the target variable 

Is the data usage compliant with user agreements, data privacy best practices, and relevant regulations? Yes
