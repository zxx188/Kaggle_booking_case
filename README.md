# Kaggle_booking_case
This is the personal exercise code about one challenge on Kaggle website. Bascailly is about Predict how many people would cancel their booking in the future, and help hotel know this in advance.
## This code include Feature Engineering, and Model development parts.
About Model part, I trained multiple XGBoost models for each fold and saves them in the xgb_models list.Computed the validation AUC score for each fold and keeps track of the best iteration.Then finally calculated the mean AUC score across all folds using the get_mean_auc function. Which makes the result more comprehensive.
