# Rainfall_Estimation
Rainfall_Prediction
TOPIC:
Comparison of different machine learning models for rainfall prediction.
Data Visualization Project submitted to Dr. Parvathi R, in lieu of completion of partial requirements for the course CSE 3020, under Vellore Institute of Technology, Chennai.

Submitted By:
Jesmine Akhter     Khushi Mattu
20BCE1945         20BCE1189

Tools used:
Python, R, Tableau
Implementation Platform:
Colab, RStudio, Tableau
Synopsis:
The estimation of rainfall at any region, using the predictive attributes, is a constant area of research in recent times. Although considerable progress has been made in this regard, the accuracy that the existing models achieved highly depends on the attributes that have been utilized to predict the intended entity.Current rainfall predictio models rely on intricate statistical calculations that are frequently very expensive financially and computationally or do not apply to applications further down the line. Hence, methods that combine time-series data with Machine Learning algorithms are being investigated as a substitute to get over these problems.

The main objective of our project is to compare the existing machine learning regressors, alongside a stacked ensemble regressor with the motive to display that ensemble regressors give a better performance as compared to existing state of the art models. We compared the performance of the models with respect to the mean square errors obtained in making the predictions. In order to implement the same, we have made use of the publicly available austin weather data available in Kaggle. The ensemble regressors performed better than traditional regressors and attained a mean average error of 0.1, with a root mean square error of 0.05 and 0.07 respectively, seconded by the Random Forest Regressor, with a mean average error and a root mean square error of 0.2 and 0.08 respectively. The coefficients obtained from the Random Forest regressor model were then used to build a linear regression model - which can predict the rainfall values based on the predictor attributes.

To perform the same, we made use of the historical weather data of Austin, Texas. The preprocessing steps involve checking for null values, normalizing the feature values, visualizing the distribution of the features, finding the statistical summary of the features, finding and testing the correlation between the attributes, splitting into training and test sets and performing regression. We divide the dataset into two parts for training and one dataset is used the stated models. All the models are trained and hypertuned accordinly to reduce the MSE. Then, predictions are made on the models and results are compared and analyzed, with further co-efficient extraction in order to build the linear regression model.

Algorithms Used

Multivariate Linear Regression
Multilayer Perceptron Regression
KNN Regression
Ridge Regression
Random Forest Regression
Support Vector Regression
Gradient Boosting Regressor
Stacking Regressor
Preview of Tableau Dashboard:
image
