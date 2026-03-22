
# Flight Fare Prediction 

This project presents a complete end-to-end machine learning workflow for predicting airline ticket prices. The study includes comprehensive data preprocessing (missing value handling, outlier treatment, and categorical encoding), exploratory data analysis (EDA), feature engineering (time-based and duration features), and model development using multiple regression algorithms. Several models—including Linear Regression, Decision Trees, Random Forest, Gradient Boosting, and XGBoost—were trained and evaluated using log-transformed target values to address skewness.

After extensive comparison and hyperparameter tuning via RandomizedSearchCV, XGBoost emerged as the best-performing model based on R², RMSE, and MAE on actual price values. SHAP explainability techniques were further applied to interpret feature contributions and ensure model transparency. The final model was saved using a full preprocessing pipeline to support deployment. This notebook demonstrates a robust machine learning methodology for real-world flight fare prediction.
