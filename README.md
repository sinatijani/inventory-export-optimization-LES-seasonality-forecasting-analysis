# Inventory Optimization: Linear Exponential Smoothing with Seasonality Forecasting

## Project Overview

This project focuses on analyzing and forecasting the export data of Indigo T-Shirts from 2017 to 2023 to optimize inventory management. The analysis includes trend and seasonality decomposition, forecasting model development, safety stock calculation, lead time simulation, and profit analysis.

## Analysis and Methodology

* **Exploratory Data Analysis (EDA):**
    * Performed a detailed analysis of quarterly export data spanning from 2017 to 2023.
    * Decomposed the time series data to identify trends, seasonal patterns, and residual components.
    * Observed significant trends, seasonal variations, and key data insights, including periods of sales decline and subsequent recovery, as well as seasonal peaks during the second quarter.
* **Forecasting Model Development:**
    * Evaluated and compared three forecasting models:
        * Simple Exponential Smoothing (SES)
        * Linear Exponential Smoothing (LES)
        * Linear Exponential Smoothing with Seasonality (LESwS)
    * Determined that the LESwS model provided the most accurate forecasts, demonstrating the lowest error rates.
* **Safety Stock Calculation:**
    * Calculated the optimal safety stock levels based on the LESwS forecasts to mitigate the risk of stockouts due to demand variability.
* **Lead Time Simulation:**
    * Conducted a Monte Carlo simulation (150 trials) to model demand during lead time.
    * Determined a reorder point based on the simulation results.
    * Observed a skewed distribution in demand, indicating a higher probability of lower demand scenarios.
* **Profit Analysis:**
    * Evaluated potential profit outcomes under various demand scenarios.
    * Quantified the risks associated with pursuing higher profit margins.

## Key Findings

* Accurate forecasting is critical for effective inventory optimization.
* Simulation techniques provide valuable insights into potential demand variability and risk.
* Detailed data analysis reveals actionable patterns and trends.

## Professional Competencies Demonstrated

This project showcases the following competencies:

* Proficiency in time series data analysis.
* Development and evaluation of forecasting models.
* Application of statistical methods to solve business problems.
* Execution and interpretation of simulation analyses.
* Delivery of data-driven, actionable recommendations.

## Impact

This analysis provides Indigo T-Shirts with a data-driven framework to enhance inventory management, reduce stockout risks, and optimize profitability.