# Weather_trend_forecasting
# 🌦️ Weather Trend Forecasting Project

## 📌 Project Overview

This project analyzes global weather data to forecast future weather
trends using time series and machine learning models. The objective is
to perform data cleaning, exploratory data analysis (EDA), build
forecasting models, and evaluate their performance.

The dataset used is the **Global Weather Repository** from Kaggle,
containing daily weather information for cities worldwide.

------------------------------------------------------------------------

## 📂 Dataset

-   Source: Kaggle - Global Weather Repository
-   Features: 40+ weather-related attributes including temperature,
    humidity, precipitation, air quality, wind speed, and more.
-   Time Column Used: `lastupdated` (converted to datetime for time
    series analysis)

------------------------------------------------------------------------

## 🧹 Data Cleaning & Preprocessing

-   Handled missing values using median/mean imputation
-   Removed outliers using IQR method
-   Converted `lastupdated` to datetime format
-   Set datetime as index for time series forecasting
-   Applied normalization where required

------------------------------------------------------------------------

## 📊 Exploratory Data Analysis (EDA)

-   Temperature trends over time
-   Precipitation pattern visualization
-   Correlation heatmap for feature relationships
-   Statistical summaries for major weather parameters

Key Insights: - Identified seasonal trends in temperature - Observed
correlations between humidity, precipitation, and air quality - Detected
potential anomalies in extreme weather conditions

------------------------------------------------------------------------

## 🤖 Forecasting Models Used

### 1️⃣ ARIMA (Time Series Model)

-   Used for univariate temperature forecasting
-   Evaluated using MAE and RMSE

### 2️⃣ Prophet Model

-   Applied for capturing seasonality and trend components
-   Compared against ARIMA for accuracy

### 3️⃣ Machine Learning Models

-   Random Forest
-   Decision Tree
-   Logistic Regression (for categorical classification tasks)

------------------------------------------------------------------------

## 📈 Model Evaluation Metrics

-   MAE (Mean Absolute Error)
-   RMSE (Root Mean Squared Error)
-   Accuracy (for classification tasks)

Comparison of models was performed to determine the best forecasting
performance.

------------------------------------------------------------------------

## 🔎 Advanced Analysis

-   Anomaly Detection using statistical techniques
-   Feature Importance analysis using Random Forest
-   Multi-model comparison for improved forecast accuracy

------------------------------------------------------------------------

## 🛠️ Technologies Used

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Scikit-learn
-   Statsmodels
-   Prophet
-   Jupyter Notebook

------------------------------------------------------------------------

## 🚀 How to Run the Project

1.  Clone the repository:

        git clone <https://github.com/piyushsrvastava/Weather_trend_forecasting>

2.  Install dependencies:

        pip install -r requirements.txt

3.  Open Jupyter Notebook:

        jupyter notebook

4.  Run `Weather_Trend_Forecast.ipynb`

------------------------------------------------------------------------

## 📌 Conclusion

This project demonstrates practical implementation of data
preprocessing, exploratory analysis, and forecasting techniques using
both classical time series models and machine learning approaches. The
results provide insights into global weather patterns and predictive
modeling strategies.

------------------------------------------------------------------------

## 👨‍💻 Author

Piyush Srivastava
