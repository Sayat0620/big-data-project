# Comprehensive Analysis of E-Commerce Transactional Data

##  Project Overview
An end-to-end data analysis was conducted on an e-commerce dataset to identify purchasing patterns, segment customers, and forecast future revenue. The project aimed to connect socio-economic customer profiles with their transaction history.

##  Dataset
* **Transactions:** 10,000 records containing order dates, revenue, profit, and discounts.
* **Customers:** ~1,500 records including age, income, and job-related satisfaction indicators.

##  Tech Stack
* **Analysis:** Python (Pandas, NumPy, Statsmodels)
* **Clustering:** Scikit-learn (K-Means, PCA)
* **Forecasting:** SARIMA (Seasonal Autoregressive Integrated Moving Average)
* **Visualization:** Matplotlib, Seaborn

##  Methodology
* **Data Integration:** Transactional and customer datasets were merged to create a unified analytical view.
* **Customer Segmentation:** **K-Means clustering** combined with **Principal Component Analysis (PCA)** was applied to categorize the user base into high-value and low-value segments.
* **Time Series Forecasting:** A **SARIMA model** was implemented to analyze 20 years of historical data and generate a 12-month sales forecast.
* **Feature Importance:** Demographic vs. transactional features were evaluated to determine primary drivers of profitability.

##  Key Results
* **Segmentation:** Two distinct clusters were identified, revealing that a small group of high-income, older customers generates the majority of revenue.
* **Forecasting:** Seasonal trends were successfully captured, providing a data-driven basis for inventory planning.

##  Team Contribution
This work was performed as part of a group project. My role involved the development of the clustering logic and the interpretation of statistical results.
