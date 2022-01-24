# Optimize, Monitor and Track Classification task

This Notebook explores and models the Patient Survival Prediction dataset. The goal is to predict if a patient is going to survive a stay in a hospital, or not. The data has 91713 samples and 85 features. I use `Neptune` to monitor and track model performance, and `Optuna` to find a combination of Random Forest hyperparameters which returns the highest *accuracy* and *f1 score*. I did Exploratory Data Analysis to get familiar with data and to clean `NaN` values and unnecessary features. Both `Optuna` visuals and `Scikit-Plot` very much helped to understand feature importances and model performance. `SHAP` was used to interpret predictions. There is a screen shot of `Neptune` logs at the end of the Notebook. 
