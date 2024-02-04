# **Predictive Analytics Project for Working Capital Optimization**

## 📢 **Project Overview**

Working capital optimization involves strategically managing a company's current assets and liabilities to enhance operational efficiency and financial health. It focuses on finding the right balance between accounts receivable (AR) and accounts payable (AP) to ensure sufficient liquidity while minimizing costs and risks.


AR data refers to money customers owe the company, while AP data represents the money the company owes to suppliers.


This involves predicting the timing of customer payments and supplier payments to ensure cash flow and liquidity in a specific period for the company. By analyzing historical data and using predictive modeling techniques, the project aims to forecast the week customers are likely to pay the company and the week in which the company should pay suppliers.

These predictions enable the company to proactively manage cash flow, ensuring that customer payments are received on time to cover outgoing payments to suppliers. This helps maintain a healthy cash position, enhances liquidity, and allows the company to meet its financial obligations effectively.


The project aims to optimize working capital management by leveraging accounts receivable and payable data. Through predictive analysis, the project aims to accurately forecast the timing of customer and supplier payments, enabling the company to ensure cash flow and liquidity within a specified period.


![image.png](https://images.pexels.com/photos/5849577/pexels-photo-5849577.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)

## 📁 Data Sources
* In this project, we gathered the necessary data from various sources, including Excel files for accounts receivable ( AR DATA ), accounts payable ( AP DATA ), customer data, and supplier data, as well as from an MS SQL Server database hosted on an Amazon RDS (Relational Database Service) instance.
* To access this data, we useed the pyodbc library, which allows us to connect to the database and fetch the required data.
* Once the data was read into DataFrames, we performed data cleaning, preprocessing, and feature engineering to prepare it for further analysis and modeling.
## 🔨 Tools Used
These are the **Tech Stack** we used along the project:

**Language**: Python

**Libraries**:   pandas, numpy, matplotlib, statsmodels, seaborn, scikit-learn, pyodbc



## 🔔 Processes
This is the approach we did along the project:
* As for AR Data we performed:
    * Exploratory Data Analysis (EDA): Analyze the accounts receivable data to gain insights into the distribution, trends, and patterns.
    * Feature Engineering: Transform and manipulate the AR data to extract relevant features for the prediction model.
    * Model Building: Utilize various regression models such as RandomForestRegressor, LinearRegression, KNeighborsRegressor, GradientBoostingRegressor, and SVR to predict the week of customer payments.


* As for AP Data we performed:
    * EDA: Perform exploratory analysis on the accounts payable data to understand its characteristics and identify any anomalies.
    * Feature Engineering: Engineer additional features from the AP data that may be relevant for the analysis and prediction.
    * Model Building: Develop prediction models based on the AP data to forecast the week of supplier payments.


* For Working Capital Optimization (WCO) Calculations:
    * Group and sum the receivables and payables data on a weekly basis.
    * Calculate the working capital by subtracting the sum of payables from the sum of receivables for each week.
    * Analyze the working capital figures to identify periods of positive or negative cash flow and assess the overall liquidity.

## 💡 **Conclusion**
The Predictive Analytics Project for Working Capital Optimization aimed to strategically manage a company's current assets and liabilities to enhance operational efficiency and financial health. By finding the right balance between accounts receivable (AR) and accounts payable (AP), the project sought to ensure sufficient liquidity while minimizing costs and risks.

Through the utilization of historical AR and AP data and employing predictive modeling techniques, the project successfully forecasted the timing of customer and supplier payments. This allowed the company to proactively manage cash flow, ensuring that customer payments were received on time to cover outgoing payments to suppliers. As a result, the company maintained a healthy cash position, enhanced liquidity, and effectively met its financial obligations.

The project involved Exploratory Data Analysis (EDA) on both AR and AP data, providing valuable insights into the distribution, trends, and patterns. Feature Engineering techniques were employed to transform and manipulate the data, extracting relevant features to build prediction models. Various regression models, including RandomForestRegressor, LinearRegression, KNeighborsRegressor, GradientBoostingRegressor, and SVR, were utilized to predict the week of customer and supplier payments.
