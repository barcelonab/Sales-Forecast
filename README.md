**This report shows the different types of forecasting that a company can implement depending on the trends and patterns in its sales history.**

**Forecast Types**

Month Rolling Forecast    
Recursive Forecasting - predicts the next value by using the average (or sum) of the previous 3 months of actual data. As new months come in, the window “rolls forward” and the oldest month drops out. It is used when you want to predict future values based on the recent past, especially when the data does not have strong yearly seasonality but does show short-term patterns.

Forecast YoY   
Seasonal Forecasting - Can be used any time your data shows repeating patterns at regular intervals.
These repeating patterns are called seasonality, and they occur consistently every day, week, month, quarter, or year.

Forecast YoY + Growth   
Seasonal Baseline Forecasting - Predicts a future value by averaging the values from the same period in each of the previous years. It is used when the data has stable seasonality but individual years show volatility.

**Here are the steps taken to complete the analysis**

* Created ODBC connection from Unidata to SQL Server.
* Created a Linked Server and view at the same time.
* Used SQL Server as the data source and choose view as table in Power BI Get Data.
* Created a Date Table and marked it as Date Table.
* Transformed and cleaned the categorical data using Power Query to keep the final report simple.
* Created several DAX measures for the desired metrics.
* Published, administered and created an App in Power BI Service for end users and business stakeholders.
