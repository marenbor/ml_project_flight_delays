# Flight Delay Prediction Project
This project aims to predict flight delays using machine learning techniques. We used the Zindi challenge "Predicting flight delays for Tunisair". 

## Project Structure
- `data/` - Contains the dataset files (`Train.csv`, `Test.csv`, etc.).
- `models/` - Stores trained models including evaluation and error analysis.
- `notebooks/` - Jupyter Notebooks for EDA, data cleaning and feature engineering. 
- `docs/` - Presentation

## Uses
Run the notebooks in the chronological order (beginning with step 2). They build up on each other to create the necessary csv-files:
  1. Used `notebooks/00_EDA_Parya/Maren.ipynb` to explore data.
  2. Used `notebooks/01_data_cleaning.ipynb` to clean and preprocess data.
  3. Used `notebooks/02_feature_engineering.ipynb` to create new features especially encode categorial features. The 
     `notebooks/02_feature_engineering_classifier.ipynb` is created for the CatBoost classification model.
  5. Trained a baseline model in `models/baseline_model.ipynb`.
  6. Experimented with advanced models in `models/LightGBM.ipynb`, `models/CatBoost.ipynb` and `models/XGBoost.ipynb`
  7. Evaluated model performance in the corresponding model files.
  8. Choosed the final model with the best RMSE.

## Contributors in alphabetical order
- Eva
- Jonas
- Maren
- Parya


