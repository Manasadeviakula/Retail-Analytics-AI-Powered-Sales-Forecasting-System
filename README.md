# Retail Analytics & AI-Powered Sales Forecasting System

## Project Overview

Retail businesses generate vast amounts of sales data across multiple stores and product categories. Analyzing this data can help organizations optimize inventory, improve revenue generation, understand customer demand, and make informed business decisions.

This project develops an AI-powered Retail Sales Analytics and Forecasting System that performs data analysis, identifies sales trends, forecasts future revenue, and segments stores based on performance. The system provides actionable business insights to support strategic decision-making.

---

## Objectives

* Analyze retail sales data across multiple stores and product categories.
* Identify sales patterns, growth drivers, and seasonal trends.
* Forecast future sales revenue using time-series forecasting models.
* Segment stores based on performance and sales behavior.
* Generate business insights and recommendations for decision-makers.

---

## Dataset Information

* **Dataset Name:** Retail_Sales_Data_Unlox
* **Duration:** January 2023 – December 2024
* **Records:** Approximately 73,000 transactions
* **Format:** Excel (.xlsx)

### Dataset Features

* Date
* Store ID
* Product Category
* Quantity Sold
* Unit Price
* Total Sales
* Additional sales-related attributes

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Prophet
* Statsmodels
* Scikit-learn

---

## Machine Learning Concepts Used

### 1. Feature Engineering

Created additional date-based features such as:

* Year
* Month
* Quarter
* Day of Week

### 2. Time Series Forecasting

Used forecasting techniques to predict future sales:

#### Prophet

* Captures trend and seasonality
* Generates future sales forecasts

#### ARIMA

* Statistical time-series forecasting model
* Used for comparative sales prediction

### 3. Unsupervised Learning

#### K-Means Clustering

Used to segment stores into:

* High Performing Stores
* Medium Performing Stores
* Low Performing Stores

### 4. Feature Scaling

#### StandardScaler

Used to normalize features before clustering.

### 5. Correlation Analysis

Identified relationships between sales-related variables.

### 6. Model Evaluation

Forecasting performance evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

---

## Project Workflow

### Step 1: Data Collection

Load retail sales data from the Excel dataset.

### Step 2: Data Preprocessing

* Handle missing values
* Remove duplicates
* Convert data types
* Prepare data for analysis

### Step 3: Exploratory Data Analysis (EDA)

Performed:

* Sales trend analysis
* Monthly sales analysis
* Quarterly sales analysis
* Product category analysis
* Store performance analysis
* Correlation analysis

### Step 4: Forecasting

Implemented:

* Prophet Forecasting
* ARIMA Forecasting

Predicted future revenue and identified sales trends.

### Step 5: Store Segmentation

Applied K-Means Clustering to group stores based on:

* Total Revenue
* Average Sales
* Sales Volatility
* Business Performance

### Step 6: Business Insights

Generated actionable recommendations for:

* Inventory Management
* Sales Planning
* Revenue Optimization
* Store Performance Improvement

---

## Model Performance

### Forecasting Evaluation Metrics

| Metric | Value        |
| ------ | ------------ |
| MAE    | 6,576,983.15 |
| RMSE   | 7,720,306.67 |

### Interpretation

* Lower MAE indicates better prediction accuracy.
* RMSE penalizes larger forecasting errors and evaluates overall model performance.

---

## Key Findings

* Significant seasonal sales patterns were identified.
* Certain product categories contribute more revenue than others.
* Store performance varies considerably across locations.
* Forecasting models successfully captured future sales trends.
* Store segmentation helps identify high-performing and low-performing stores.

---

## Business Recommendations

1. Increase inventory allocation for high-demand product categories.
2. Focus marketing campaigns on top-performing products.
3. Use forecasted sales to improve inventory planning.
4. Monitor underperforming stores and implement corrective actions.
5. Utilize store segmentation for targeted business strategies.

---

## Conclusion

The Retail Analytics & AI-Powered Sales Forecasting System successfully analyzes retail sales data, forecasts future revenue, and segments stores using machine learning techniques. The project demonstrates how data analytics and AI can support strategic decision-making, optimize operations, and improve business performance in the retail industry.

---

## Future Enhancements

* Interactive Streamlit Dashboard
* Customer Segmentation
* Demand Forecasting
* Real-Time Sales Monitoring
* XGBoost and LSTM Forecasting Models
* Power BI Integration

---

## Author

**Manasa Devi Akula**

Computer Science Student | Data Analytics & Machine Learning Enthusiast
