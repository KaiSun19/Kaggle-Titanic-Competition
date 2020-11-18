# Kaggle-Titanic-Competition
A notebook describing my approach towards the famous Titanic Classification problem on Kaggle

Initial data exploration began with dropping columns that were irrelevant to the problem of predicting the likelihood that a pasenger would survive the titanic crashing. Then , observations with outliers were dropped to prevent bias. A multi correlation matrix was produced to see if any features had a high correlation and relevant features were dropped. Several algorithm classifiers were tested based on their Mean Absolute Error. The logistic regression approach proved to be have the lowest MAE and was optimized via a Randomized Search Cross Validation. After optimization, a classification report was created and feature importances were listed via their relevant coefficients. 

