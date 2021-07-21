# 270440_House_Prices
Codacy Badge | [![Codacy Badge](https://app.codacy.com/project/badge/Grade/91590f935db1437786776c44c64af7fc)](https://www.codacy.com?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=super-user-17/270440_House_Prices&amp;utm_campaign=Badge_Grade)

## Problem Description
With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this problem challenges to predict the final price of each home.

## Model Used
### Advanced Regression
An AdaBoost regressor is a meta-estimator that begins by fitting a regressor on the original dataset and then fits additional copies of the regressor on the same dataset but where the weights of instances are adjusted according to the error of the current prediction. As such, subsequent regressors focus more on difficult cases.

## Outcome
For each Id in the test set, the value of the SalePrice variable is predicted. 
#### Id,SalePrice
#### 1461,169000.1
#### 1462,187724.1233
#### 1463,175221
#### etc.
