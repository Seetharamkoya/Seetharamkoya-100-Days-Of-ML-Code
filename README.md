# Seetharamkoya-100-Days-Of-ML-Code
## SIMPLE LINEAR REGRESSION [simple linear regression](https://github.com/Seetharamkoya/100-Days-Of-ML-Code/blob/master/simple_Linear%20Regression.ipynb)
Predicting a response using a single feature.
It is a method to predict dependent variable (Y) based on values of independent variable (X). It is assumed that that the two variable aren linearly related. Hence, we try to find a linear function that predicts the response value(y) as  accuractely as possible as a function of the feature or independent variable(x).

y = b + b1x1

y = Dependent variable
x1 = Independent variable
b = Intercept
b1 = slope
[ksr](https://www.skysilk.com/blog/wp-content/uploads/2018/09/SimpleLinearRegressionEquation.jpg)


In this regressionmodel, we are trying to minimize the erros in the prediction by finding the "line of best fit"  - the regression line from the errors would be minimal. we are trying to minimize the length between the observed value (yi) and the predicted value from our model (yp).

min {sum(yi - yp)^2}
