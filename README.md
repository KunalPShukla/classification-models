# Heart Disease Prediction

The goal of this project is to predict whether a patient is at risk of **heart disease** based on various medical features. The dataset includes attributes like age, sex, blood pressure, cholesterol levels, and other medical indicators that contribute to the risk of heart disease. This is a binary classification problem where the task is to predict whether a person has heart disease (positive class) or not (negative class).

## Models Used

The following classification algorithms are implemented to solve this problem:

1. **Logistic Regression**: A simple linear model used for binary classification, useful for estimating the probability of the presence of heart disease.
2. **Decision Trees**: A non-linear model that splits the data into decision nodes based on feature values, learning rules that help classify the risk of heart disease.
3. **Random Forest**: An ensemble learning method that uses multiple decision trees to improve prediction accuracy and reduce overfitting, offering a more robust solution than individual decision trees.
4. **Naive Bayes**: A probabilistic classifier based on Bayes' Theorem, which assumes independence among the features. This model is efficient for classification tasks, especially when features are conditionally independent given the class.

In addition to the models, **Grid Search Cross-Validation (GridSearchCV)** is used to fine-tune hyperparameters and find the optimal settings for each model, improving their performance.

## Conclusion

The notebook evaluates each classification model (Logistic Regression, Decision Trees, Random Forest, and Naive Bayes) using performance metrics like **accuracy**, **precision**, **recall**, and **F1 score**. By applying **Grid Search CV**, the best hyperparameters are identified for each model, ensuring optimal performance. The results show that ensemble methods like **Random Forest** tend to perform better due to their ability to handle complex relationships in the data and reduce overfitting.
