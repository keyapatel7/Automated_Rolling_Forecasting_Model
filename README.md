
# Automated_Rolling_Forecasting_Model

## Project Overview
This project focuses on developing an Automated Rolling Forecasting Model for MedAire to enhance financial planning and operational efficiency. By integrating key financial KPIs and leveraging advanced time-series forecasting techniques, the project achieved a 24% improvement in forecasting accuracy. The model provides actionable insights for stakeholders, supporting data-driven decision-making in financial forecasting and resource management.

## Dataset Information
- The dataset includes historical revenue data from July 2021 to December 2024
- Data is aggregated by Region, Line of Business (LOB), and Product
- Features include:
  - Temporal trends
  - Rolling statistics
  - Lagged values
  - Key financial KPIs

## Technologies Used
- **Python**: Pandas, NumPy, Scikit-learn, XGBoost, Statsmodels
- **SQL & Excel**: Data extraction and preprocessing
- **Power BI**: Interactive dashboard for visualization

## Objectives
- Develop a Rolling Forecast Model to automate monthly revenue forecasting
- Enhance Forecasting Accuracy by 24% over traditional methods
- Optimize Resource Allocation through accurate revenue predictions
- Integrate Advanced Forecasting Techniques (ARIMA, SARIMA, XGBoost)
- Create an Interactive Dashboard for stakeholders
  
## Methodology

**Data Collection & Preprocessing**
- Cleaned missing values and created lagged features, rolling statistics, and difference features.
- Incorporated temporal features like month and year to capture seasonality.
- Integrated key financial KPIs (DNR%, Price%, New Business Contributions).
**Model Development**
- Time-Series Models: ARIMA and SARIMA to capture trends and seasonality.
- Machine Learning Model: XGBoost for capturing non-linear relationships.
- Hyperparameter Tuning: Optimized using GridSearchCV with TimeSeriesSplit.

**Interactive Forecasting Tool**
 - Built using ipywidgets to allow parameter adjustments.
 - Outputs forecasted revenue saved as CSV for Power BI integration.
**Power BI Dashboard**
- Enabled dynamic filtering by Region, LOB, Product, Year, Month, and KPIs.
- Visuals include forecasted revenue, historical trends, KPI adjustments, and detailed breakdown tables.
