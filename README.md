# WineSalesForecasting

📈 Wine Sales Forecasting using Time Series Models
🚀 Project Overview

This project focuses on forecasting wine sales using time series analysis and machine learning models. The dataset consists of historical monthly sales data for two types of wine (Rose & Sparkling) from a wine company, and the goal is to build predictive models to forecast future sales trends.
🎯 Key Objectives:

    Analyze wine sales trends and seasonal patterns.
    Perform exploratory data analysis (EDA) and decomposition of time series.
    Check for stationarity and apply necessary transformations.
    Train multiple forecasting models, including:
        Naïve Forecasting & Simple Average
        Exponential Smoothing (SES, DES, TES)
        Moving Average (MA)
        ARIMA & SARIMA Models
    Compare model performances using Root Mean Squared Error (RMSE).
    Forecast wine sales for the next 12 months and provide business recommendations.

    📊 Dataset Description

The dataset consists of monthly wine sales data for Rose & Sparkling wine. Each dataset contains:

    Date (YYYY-MM): Timestamp for sales data.
    Sales Quantity: Number of wine units sold each month.

💡 Key Data Observations:

    Both wine types show seasonal patterns with a spike in sales during October–December (holiday season).
    Rose wine sales are declining over time, indicating a shift in customer preferences.
    Sparkling wine sales remain stable but show strong seasonal peaks.