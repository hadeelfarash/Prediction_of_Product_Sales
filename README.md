# Prediction of Product Sales
# Overview
This project aims to predict sales for food items sold across different stores. The primary goal is to provide actionable insights to retailers by analyzing various features that influence sales, ultimately assisting in optimizing sales performance.

**ِِAuthor** : Hadeel Fatash

# Business problem:

Predict sales figures for food items in various stores.
Analyze key features influencing sales.
Offer recommendations to enhance sales based on insights derived from the data.

# Data:
sales_predictions_2023.csv
https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/

# Methods
** Explatory the data 
** clean the data by preprocessing methods (duplicates, null values, nuniuqe categories , inconsistent categories, inconsistent numeric features)
** Imputation & satandarization(Encoder, one hot encode) and use them throgh pipeline
** colom transformer
** models pipeline
** Evaluation
# Results
The second Model (Random Forest): Training Data (R² = 0.706): Approximately 70.6% of the variable being predicted is explained by the independent variable(s) used in the regression model when training the model on the provided dataset.

Test Data (R² = 0.595): When applying the trained model to new, unseen data (test data), approximately 59.5% of the variable being predicted in the dependent variable is explained by the independent variable(s).

Interpreting this for a non-technical audience:

"The model performed relatively well on the training data, explaining about 70.6% of the changes in the predicted outcome based on the included factors. However, when tested on new data that the model hasn’t seen before, it explains around 59.5% of the variability. This difference between the training and test performance suggests that the model might be slightly overfitting to the training data, which means it may not generalize as well to new, unseen data."

The first Model (linear reg): Training Data (R² = 0.562): Approximately 56.2% of the variability in the dependent variable (the variable being predicted) is explained by the independent variable(s) used in the regression model when training the model on the provided dataset.

Test Data (R² = 0.567): When applying the trained model to new, unseen data (test data), approximately 56.7% of the variability in the dependent variable is explained by the independent variable(s).

Interpreting this for a non-technical audience:

"The model shows moderate performance on both the training and test datasets. On the training data, it explains about 56.2% of the changes in the predicted outcome based on the included factors, and on the test data, it explains around 56.7%. This similarity in performance between training and test data suggests that the model doesn't suffer from significant overfitting or underfitting. However, there might be additional factors beyond those considered in the model that influence the predicted outcome."

# Recommendations:
you can instantiat another model to increase performance 
# Limitations & Next Steps
i will applay another kind of models to optimize the prediction 
# For further information
For any additional questions, please contact email : **hadeel-frashat@live.com**

