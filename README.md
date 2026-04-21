# SF Airbnb pricing model
Predicting Airbnb prices in San Francisco using machine learning regression models.

# Features:
- Outlier removal to filter luxury listings above $500
- One-hot encoding for categorical features (neighbourhood, room type)
- Trained on 4,477 listings after outlier removal.
- Hyperparameter tuning with 5-fold GridSearchCV across all three models: Decision Tree Regressor, Random Forest Regressor, and XGBoost Regressor
- Model comparison using MAE and R² Score

# Technologies:
- scikit-learn
- pandas
- XGBoost
- Python
- Jupyter Notebook

# How to run:
- Clone the repository
- Install dependencies: pip install pandas scikit-learn xgboost jupyter
- Prepare dataset: listingsSF.csv (from Inside Airbnb)
- Open SFAirbnbPricing.ipynb in Jupyter and run 

