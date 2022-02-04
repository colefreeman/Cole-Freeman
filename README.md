# **Customer Service Call Center Forecast**

## **Introduction**

A common business problem for busy call centers are call volume peaks and valleys where business operations and employee staffing levels are not optimized for peak calling periods. For this example project I built a Call Center Forecasting tool to predict call volume by day for a 30 day horizon. I visualized the forecasted daily call volume in addition to Call Center KPIs in a Tableau Dashboard. A call center can use the forecast and dashboard to increase efficiencies in their Operations. Employee work hours and overtime can be more efficiently distrbuted during high volume call hours. 

### **Steps:**

* Created a tool that forecasts call center data gathered from Kaggle to increase efficiencies in Call Center Operaions
* Compared traditional and nontraditional time-series models to the LightGBM Regressor
* Engineered features to increase Mean Squared Error score for future forecast
* Optimized LightGBM Regressor to forecast Daily Calls
* Built client dashboard in Tableau Public to visualy display timeseries forecast and other KPIs

**Note:** You can utilize the accompanying code in this google colab notebook (**insert link around the google colab notebook**)

## **The Data:**

The data was collected from the Kaggle website and and is titled Call Center Data. The data is aggregated by day and contains number of calls recieved, answered, dropped and additional aggregation of ratios based on these call types. The data consists of 1251 days of data, but does not contain a date for the aggregated call data. The prepared dataset **be sure to link prepared dataset** in the Github repository contains a full dataset with dates joined to the original dataset. 

## **Data Analysis:**



#### **Pearson's Correlation Matrix**

![image](https://user-images.githubusercontent.com/92221031/152280183-3f8ef194-79e2-4725-bb0d-6f3c0bcd20c1.png)


