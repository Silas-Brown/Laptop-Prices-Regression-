# Laptop Price Prediction


## (1) Overview

### 1.1 Background
Our dataset consists of 11,768 observations and 9 columns with the target column being laptop price. The predictors are specifications of the laptop, brands, and operating systems

### 1.2 Preprocessing
Specifications such as GPU, processor are represented as ranks. Resolution is represented as the product of its dimensions (e.g, 1920x1080=1920*1080). Each brand and OS is represented as a binary variable (0 or 1).
There are no missing values to address, and extreme values are removed.
### 1.3 Verifying regression assumptions
Homoscedasticity and normality of residuals is confirmed via plots.
No auto-correlation of residuals is verified via a 95% CI of the Durbin-Watson statistic
### 1.4 10-fold CV
10-fold CV metrics based on MSE, MAE, and R-squared for the model are examined.
### 1.5 Feature pruning
95% CIs of coefficients are used to prune features. The observed differences in 10-fold CV are negligible.
### 1.6 Prediction intervals
The data is split into training and testing. Prediction intervals of the test set are analyzed. The coverate rate of $y_{test}$ is examined. The distribution of the margins of error and how those margins change with respect to $y_{test}$ are also examined.




