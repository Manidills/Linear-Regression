# Linear-Regression
Linear Regression with Feature selection


Predict the target value by fitting best linear line relationship between independant and dependant variables.

Least square method:
        y=mx+c
        
simple LR:
  use only single independant variable
  
Multiple LR:
  use multiple independant variables
  reduce the cost function using gradient descent, when they have multiple parameters
  
Metrics:{some imp}
  MSE: average square distance between predicted and actual output
  MAE: avearge distance between predicted and actuacl output{ we go with MAE when we have outliers }
  RMSE: square root of MSE
  
  
CODE EXPLANATION:
1. Boston dataset loaded from sklearn
2. check for null values and split the dataset
3. Find feature importance using Extratree classsifer(){ feature selection }
4. Find the correlation between the features
5. use chi2 method to pick best features {selectKbest}
6. fit the model
7. check the metrics values


Here we used 3 feature selection methods to find the best fit !
