# Machine-learning-project
This is a Churn Prediction project.
The goal of this project is to predict customer churn rate for a telecom company with Machine Learning. These predictions allow to set up a targeted strategy for customer retention.

## Run the code
To see the project and run the code run "customer-churn.ipynb". The file "data/WA_Fn-UseC_-Telco-Customer-Churn.csv" contains the dataset

## Models
1. Logistic Regression
2. Decision Tree

## Metric
The metric used to evaluate the quality of the model is area under ROC curve (good explanation here), its value is between 0 and 1. Higher the AUC, better the model is at predicting 0s as 0s and 1s as 1s. "The area under ROC curve specifies the probability that, when we draw one positive and one negative example at random, the decision function assigns a higher value to the positive than to the negative example."

Why use this metric instead of accuracy ? : because having a good accuracy doesn't necessarily means it's a good classifier.<br>
<br>
<img src="https://user-images.githubusercontent.com/86122364/152940256-06341696-f94b-4c81-86a8-e4b79c849c71.png" width="300" height="300">


## Results
Retained model : Logistic Regression<br>
Final ROC AUC Score: 0.8244643585459234<br>
Recall Score: 0.3479<br>
Precision Score: 0.7364<br>
