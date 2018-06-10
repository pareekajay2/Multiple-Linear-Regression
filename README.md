# Multiple-Linear-Regression
Backward Elimination: 
Step 1: Select a significance level(SL) to stay in the model (e.g. SL = 0.05).
Step 2: Fit the full model with all possible predictors.
Step 3: Consider the predictor with highest p-value. If p-value > SL, go to step 4 otherwise skip step 4.
Step 4: Remove the predictor with highest p-value.
Step 5: Fit the model without this predictor.
Repeat these steps until only predictors with p-value < SL are left.
