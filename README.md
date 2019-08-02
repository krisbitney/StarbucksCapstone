# StarbucksCapstone

Abstract: Starbucks provided simulated data containing information from a series of promotional offers sent to members of their rewards program. I estimate the causal effect of receiving and viewing each promotional offer using a two-way fixed effects model and a two-stage least squares estimator with time effects. I find the most effective offers are those that offer discounts on small purchases. 

I explore the extent to which member characteristics predict whether customers will view and complete each offer using regularized logistic regression with natural cubic spline tensor product bases. I search through 3,250 models and select the best model for each outcome using ten-fold cross-validation. On a separate test data set, the selected models achieve 88% and 77% classification accuracy for offer viewing and completion, respectively. Older, high-income members are more likely to complete offers.

