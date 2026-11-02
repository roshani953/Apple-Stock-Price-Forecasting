Apple Stock Price Forecasting 
**Live Demo** 
[Try the Apple Stock Closing Price Forecasting App]
(https://apple-stock-price-forecasting-for-next-30-days.streamlit.app/)

PROJECT OVERVIEW

This project uses machine learning and time-series forecasting techniques to predict Apple's Closing 
stock price for the next 30 days based on historical stock data from 2012 to 2019.
An Interactive Streamlit dashboard allows users to explore historical trends, view forecasted 
prices and compare model performance.

PROJECT OBJECTIVES

1.Analyze historical Apple stock price data.

2.Perform Exploratory Data Analysis (EDA).

3.Create time-based and lag-based features.

4.Build and evaluate multiple forecasting models.

5.Select a suitable model using forecasting evaluation metrics.

6.Develop an interactive Streamlit application.

DATASET

1.Historical period: 2012–2019

2.Target variable: Close

3.Original dataset: 2,011 daily records

4.Features include Date, Open, High, Low, Close, Adj Close, and Volume.

PROJECT WORKFLOW

1.Data loading and preprocessing

2.Exploratory Data Analysis

3.Stationarity testing using the Augmented Dickey-Fuller (ADF) test

4.Feature engineering

5.Chronological train-test split

6.Model building and evaluation

7.Model comparison and selection

8.Streamlit dashboard development

MODELS EVALUATED

1.ARIMA

2.SARIMA

3.Support Vector Regression (SVR)

4.Random Forest Regressor

5.XGBoost Regressor

6.AdaBoost Regressor

7.Gradient Boosting Regressor

8.Decision Tree Regressor

MODEL PERFORMANCE

The original SVR model was selected based on its lowest MAE 
and MAPE among the evaluated models. Gradient Boosting achieved the lowest RMSE.

STREAMLIT DASHBOARD

The application includes:

1.30-trading-day stock price forecasting

2.Historical stock price exploration

3.Interactive trend charts

4.Model performance comparison

5.Forecast data table

6.CSV download option

TECHNOLOGIES USED

1.Python

2.Pandas and NumPy

3.Matplotlib and Seaborn

4.Scikit-learn

5.Statsmodels

6.XGBoost

7.Streamlit

8.Plotly

9.Jupyter Notebook

Run the Application Locally

Clone the repository:
git clone https://github.com/roshani953/Apple-Stock-Price-Forecasting.git

Navigate to the project folder:

cd Apple-Stock-Price-Forecasting

Install dependencies:

pip install -r requirements.txt

Run the Streamlit application:

streamlit run app.py

Important Note

This is an educational forecasting project trained on historical data from 2012–2019. 
Its predictions are based on historical patterns and should not be treated as live market forecasts or financial advice.
The reported evaluation covers only the first 30 observations of the test period. 
Actual future stock prices may differ significantly.

Author

Roshani Kundu

Aspiring Data Scientist | Python | Machine Learning | Data Analysis
