# Handling High Dimensional Data
When dealing with high-dimensional data, it is common to reduce the data set by generating a smaller set of variables that attempt to encapsulate as much of the information as possible from the original variables. There are several potential benefits to removing variables prior to modeling:

- A reduced number of variables translates into reduced computational time and complexity. 
- The presence of highly correlated variables indicates that they measure the same underlying information. In such cases, removing one of the correlated variables should not affect the model's performance and could result in a more interpretable model. 
- The removal of redundant predictors makes the model leaner and, most importantly, less prone to overfitting.
- Redundant variables often add more complexity to the model than the information they provide.

Here, we tackle a solubility dataset with a high number of correlated columns by using different approaches, among which:
- Heuristic reduction
- Principal Component Regression (PCR)
- Partial Least Squares (PLS)
- Penalized Regression: Lasso and Ridge regression
