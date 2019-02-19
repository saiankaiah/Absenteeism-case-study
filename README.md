# Absenteeism-case-study
1.       Can we find what are the major drivers of absenteeism amongst employees ?

          Used the scores of stability selection via Randomized lasso Method,Recursive featute elimination,linear model future    coefficients(Linear Regression,Lasso and Ridge) and random forest feature selection to come with the above ranking.The mean of the scores is used to rank the features.
# So our major drivers of absenteeism are Social drinker,Reason of absense,son,day of the week and education

2.       Do you think that clustering data would help ?

Based on the Analysis,Clustering can be done  into 3 groups based on the 5 major drivers of the dataset

3.       Can we build a predictive model for absenteeism? How do you evaluate the model ?
Even though we took the top 5 drivers to predict the model,still R^2 Score is very low.because all the predictors are categorical.We cant build predictive model for this problem set rather we can forecast the data
