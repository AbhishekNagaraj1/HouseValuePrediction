# HouseValuePrediction
A linear Regression model for the prediction of the value of a house in Boston.

In this linear regression model, I have done the Exploratory Data Analysis where I have plotted the correlations between different features.
I have also displayed a heat map of the correlated features to determine the best feature for the prediction of Y (Y is the target variable - Value of the house)
The best feature that was found by the correlation plot and the heat map was the 'number of rooms'
Then, I have computed the Standard deviation and Z scores manually
I have plotted the Linear regression between the best feature for Y graph using Sci-kit learn and Matplotlib
The MSE value and R2 value for this prediction are as follows:
MSE train: 19.958, test: 27.196
R^2 train: 0.765, test: 0.673

I tried different types of regression analysis like Ridge, Lasso, Elastic Net and Random Forest. The result are as follows
MSE train Ridge: 20.145, test: 27.762
R^2 train Ridge: 0.762, test: 0.667
MSE train Lasso: 24.717, test: 32.345
R^2 train Lasso: 0.708, test: 0.612
MSE train elastic: 24.381, test: 31.874
R^2 train elastic: 0.712, test: 0.617
MSE train: 1.409, test: 14.354
R2 train: 0.983, test: 0.828

I have also plotted the Residual Graph to detect any outliers 

 MSE and R2 for Random Forest Regressor is as follows:
 cross validated MSE for random forest regressor: [ -4.19598361  -5.89813544 -23.554687    -5.96051112  -8.48541521
 -27.89186038 -38.30750076 -11.01270146 -12.24943445  -5.76512529]
Mean cross validated MSE -14.3321354714
STDV for cross validated MSE 11.0028716675
cross validated R2 for random forest regressor: [ 0.89741746  0.93961633  0.58977173  0.89567192  0.92121269  0.53917238
  0.66932404  0.91672574  0.88803085  0.9013398 ]
Mean cross validated R2: 0.815828294584
STDV for cross validated R2: 0.145351445509

For a detailed set of Results, Please go through Results.pdf
