🌆 Urban Heat Island (UHI) Temperature Prediction
This project focuses on predicting urban temperature patterns using various machine learning models including Random Forest, LSTM, Support Vector Regression (SVR), and XGBoost. The study leverages geospatial features such as NDVI, LST, UHI, and UTFVI to forecast temperature variations, helping analyze Urban Heat Island effects.

📌 Features
Random Forest Regression

Long Short-Term Memory (LSTM) Neural Network

Support Vector Regression (SVR)

XGBoost (XGBRegressor)

Comparative Performance Charts

Scaled input features using MinMaxScaler and StandardScaler

Metrics used: R² Score, MAE, RMSE

🧠 Technologies & Libraries
python
Copy
Edit
from datetime import datetime, timedelta
from sklearn.ensemble import RandomForestRegressor
from sklearn.svm import SVR
from sklearn.model_selection import train_test_split, GridSearchCV
from sklearn.preprocessing import MinMaxScaler, StandardScaler, PolynomialFeatures
from sklearn.metrics import r2_score, mean_absolute_error, mean_squared_error
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import LSTM, Dense
import xgboost as xgb
📁 Project Structure
UHI.ipynb: Main Jupyter notebook containing data preprocessing, model training, and evaluation.

Data assumed to be preprocessed and prepared for time-series and regression models.

🚀 How to Run
Install dependencies:

#bash
pip install -r requirements.txt
Launch Jupyter Notebook:

#bash
jupyter notebook UHI.ipynb
Run each cell step-by-step for training and evaluation.

📊 Model Comparison
The notebook includes visualizations comparing all four models based on key regression metrics, helping determine which model best captures UHI patterns.

📌 Future Work
Incorporate additional geospatial features (e.g., land use, building density).

Optimize hyperparameters using advanced techniques.

Deploy model via web interface or mobile app.

✍️ Author
Vinit – Aspiring Data Scientist and Urban Analytics Researcher#
