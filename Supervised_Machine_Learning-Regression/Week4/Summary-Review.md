# Summary/Review

Bias-variance tradeoff decomposes the model's Mean Square Error into two parts: Bias and Variance.

Bias- is a measure of how near the model is to the actual function we are trying to model. If your model has a high bias, the model is underfitting; this means you will do poorly on the training and test data, but the relative results will be similar. 

Ways to improve bias include making the model more complex, adding higher order polynomials, obtaining more features or finding more data.

Variance - is the average squared difference of each model you train relative to the average prediction of each model. If your model has high variance, the model will usually overfit the data; this means you will do well on the training data but not on the testing data. 

You can improve variance by making the model less complex, i.e., lowering the order of the polynomial, obtaining more data  or using Reguliztion. There are 3 regulazation techniques discussed in this Module: Ridge, LASSO, and Elastic Net.

**Ridge (L2 Regularization)**

- penalizes the size  magnitude of the regression coefficients by adding a squad term 
- enforces the coefficients to be lower, but not 0
- minimizes irrelevant features and does not remove them  
- faster to train 

**LASSO (L1 Regularization)**

- penalizes the  absolute value of the coefficients
- sets irrelevant features to 0
- finds features you don't need 

**Elastic Net (L1+L2 Regularization)**

- penalizes the size  magnitude of the regression and  absolute value of the coefficients
- sets irrelevant features to 0 and enforces the coefficients to be lower