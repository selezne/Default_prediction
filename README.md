# Default_prediction
The data set is information about individuals who, during the period under study, went into default or did not go into default(have active overdue debt).

There are two datasets available:
- Training for model training;
- Test for the final evaluation of the model.

Target attribute - client default: 1 - a default was recorded for the client at the time of data collection, 0 - no default was recorded for the client at the time of data collection.

The information is encrypted to maintain trade secrets.

Need to:
1. Conduct EDA, draw conclusions about what data we are working with: how it is distributed, what features affect the target feature, etc.
2. Perform modeling, optimize hyperparameters, select the best model based on the intermediate assessment of models and evaluate it on test.

This project was devided into two parts. In the first part, I carried out EDA, tested the decision tree, random forest, and adaptive boosting. In the second part I implemented gradient boosting(XGBoost)

Datasets are attached as csv files
