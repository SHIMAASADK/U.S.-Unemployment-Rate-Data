# U.S. Unemployment Rate Data

This repository contains monthly U.S. unemployment rate data used for statistical modeling and forecasting.

## 📊 Dataset Description

| Field                 | Value                                                                 |
|----------------------|-----------------------------------------------------------------------|
| **Title**            | Unemployment Rate                                                    |
| **Series ID**        | UNRATENSA                                                            |
| **Source**           | U.S. Bureau of Labor Statistics                                       |
| **Release**          | Employment Situation                                                  |
| **Seasonal Adjustment** | Not Seasonally Adjusted                                          |
| **Frequency**        | Monthly                                                               |
| **Units**            | Percent                                                               |
| **Date Range**       | 1948-01-01 to 2025-04-01                                               |
| **Last Updated**     | 2025-05-02 7:46 AM CDT                                                 |

## 🧾 Usage

This data is intended for:
- Time series modeling (ARIMA, SARIMA, etc.)
- Forecasting unemployment trends
- Economic and labor market analysis

## 📂 Files

- `unemployment_data.csv`: Cleaned and preprocessed monthly unemployment rates
- `forecast_results.csv`: Forecasts generated using ARIMA models
- `plots/`: Diagnostic and forecast visualization

## 📌 Notes

- Data is **not seasonally adjusted**.
- All values are in **percent**.

## 📚 Source

U.S. Bureau of Labor Statistics – [https://www.bls.gov/](https://www.bls.gov/)
