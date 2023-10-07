# WEEK 3 QUIZ

## Q1. In K-fold cross-validation, how will increasing k affect the variance (across subsamples) of estimated model parameters?
   - Increasing k will usually increase the variance of estimated model parameters.

## Q2. Which statement about K-fold cross-validation below is TRUE?
   - Each of the k subsamples in K-fold cross-validation is used as a test set

## Q3. If a low-complexity model is underfitting during estimation, which of the following is MOST LIKELY true (holding the model constant) about K-fold cross-validation?
   - K-fold cross-validation will still lead to underfitting, for any k

## Q4. Which of the following statements about a high-complexity model in a linear regression setting is TRUE?
   - A high variance of parameter estimates across cross-validation subsamples indicates likely overfitting.

## Q5. Reviewing the below graph, what is the model considered when associated with the left side of this curve before hitting the plateau?
   - Underfitting

## Q6. Reviewing the below graph, what is the model considered when associated with the right side of the cross-validation error?
   - Overfitting

## Q7. Which of the following functions perform K-fold cross-validation for us, appropriately fitting and transforming at every step of the way?
   - 'cross_val_predict'

## Q8. Which of the following statements about cross-validation is/are True?
   - Cross-validation is an essential step in hyperparameter tuning.
   - We can manually generate folds by using the KFold function.
   - ALL THE ABOVE 

## Q9. Which of the following statements about GridSearchCV is/are True?
   - GridSearchCV scans over a dictionary of parameters.
   - GridSearchCV finds the hyperparameter set that has the best out-of-sample score.
   - GridSearchCV retrains on all data with the "best" hyperparameters.
   - ALL THE ABOVE

## Q10. Which of the below functions randomly selects data to be in the train/test folds?
    - 'KFold' and `StratifiedKFold`

