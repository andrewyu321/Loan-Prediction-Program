# Loan-Prediction-Program

This program predicts whether or not someone can be approved for a loan by using Classification Machine Learning Algorithms. I've use 3 different models such as Logarithmic Regression, K Nearest Neighbours, Random Forest Classifier, Support Vector Classifier and compared which model performed the best in terms of precision, recall, f1-score and support. 

**Results**
When comparing the results of how each classification algorithm performed. The worst algorithm turns out to be SVC which is not suprising due to the fact that the data had a lot of overlap and since SVC is a linear model, it wouldn't work well. What was suprisng was that Logistic Regression and Random Forest Classification both had similar stats with a precision of 80%. This is a little suprising as Logistic Regression is also a linear model like SVC. The top performing model is K Nearest Neighbours with an accuracy of 83% which isnt suprising due to the fact that KNN relies on neighbouring data points for classification and doesn't rely on the linearity of the data. 

