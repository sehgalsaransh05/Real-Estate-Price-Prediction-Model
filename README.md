# Real Estate Price Prediction Model

## Data Overview
This project aims to predict the sale prices of houses and improve the log error using regression techniques and feature engineering. The dataset used for this project is the Zillow’s Home Value Prediction on Kaggle.com

## Data Source
The data for this project was obtained from the [Zillow’s Home Value Prediction Dataset](https://www.kaggle.com/competitions/zillow-prize-1/data) on Kaggle, which includes information about the sale prices of houses and their features.

## Methodology
The following regression techniques were used to build and train the model:
- Linear Regression
- Elastic Net
- Ridge
- Lasso
- XGBoost Regressor
- Adaboost Regressor
- Gradient Boosting Regressor
- Random Forest Regressor

The models were evaluated using the mean absolute error (MAE) metric. Feature engineering was used to create additional features from the existing dataset to improve model performance. The Random Forest Regressor was hyperparameter tuned using GridSearchCV to achieve better model performance. The feature importance was checked to determine which features have the most impact on the model.

## Usage
The code for this project can be found in the 'xx.ipynb' notebook. The notebook contains the data preprocessing steps, the model training, and the prediction of the test set. The 'requirements.txt' file contains the necessary dependencies to run the notebook.

## Results
The model achieved a low mean absolute error (MAE) metric, indicating good predictive performance. The feature importance analysis identified the most important features for predicting house sale prices.

## Future Work
Future work includes deploying the model on Google Cloud Platform (GCP) and improving the model's accuracy by incorporating additional features and optimizing the existing model.
