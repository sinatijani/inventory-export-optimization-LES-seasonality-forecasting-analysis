# inventory-optimization-LES-seasonality-forecasting

# Indigo T-Shirt

I dug into Indigo T-Shirt's export data. This project was all about figuring out how to predict their sales better and keep their inventory on point. Check it out:

## What I Did & How

* **Data Exploration:**
    * I took a long look at their quarterly export data from 2017 to 2023.
    * Broke it down to see the trends, seasonal ups and downs, and the random noise.
    * Found some interesting stuff: sales were down for a bit, then picked back up, and they sell more in the second quarter.
* **Forecasting Models:**
    * Tried out three different ways to predict future sales:
        * Simple Exponential Smoothing (SES): Easy, but didn't catch everything.
        * Linear Exponential Smoothing (LES): Better with trends, but not perfect.
        * Linear Exponential Smoothing with Seasonality (LESwS): This one was the best! Super accurate, with low error rates.
    * Basically, I tested which model was the most accurate.
* **Safety Stock:**
    * Calculated how many extra t-shirts they should keep on hand, using my best forecast.
    * Helps them avoid running out of stock, even if things get a bit unpredictable.
* **Lead Time Simulation:**
    * Ran a simulation (150 trials) to see how much demand they might get during lead time.
    * figured out a reorder point.
    * The results were a bit skewed, meaning lower demand was more common.
* **Profit Analysis:**
    * Looked at how much profit they could make, considering different demand scenarios.
    * Figured out the risks involved in aiming for higher profits.

## What I Learned

* **Forecasting is Key:** Getting the forecasts right is super important for inventory.
* **Simulations are Powerful:** They help you see what *could* happen, not just what *will* happen.
* **Data tells a story:** There's a lot you can learn from looking closely at the numbers.

## Why This Matters

This project proves I can:

* Handle time series data like a pro.
* Build and test forecasting models.
* Use stats to solve real business problems.
* Run simulations and understand risk.
* Give solid, actionable advice.

Basically, I can use data to make businesses run smoother.