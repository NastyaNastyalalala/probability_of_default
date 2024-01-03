# 🚀 Probability of default

Goal: learn to predict whether a gnome who forgot his wallet at home will return the money within the next few days or, in modern language, his order will default. This will increase the financial stability of the tavern by not fulfilling orders that will not be paid in advance.

Task: to build an algorithm that determines the probability of default of a particular order using historical data from taverns of various dwarf communities from 2015-02-24 to 2016-09-30.

ROC-AUC is used as the final metric on the test part of the data.

## Tested Models:
- Random Forest Classifier

## Files:
- test.csv (file with test data)
- train.csv (file with training data with target)
- prob_of_default.ipynb ()
- submission.csv (contains two columns - Deal_id and Prediction, where the first column means the unique order identifier, and the second - the probability that the orderer will not return the money.)
