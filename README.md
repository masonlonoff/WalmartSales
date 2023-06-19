# An Analysis on Walmart Sales
![image](https://github.com/masonlonoff/WalmartSales/assets/117112918/de4fdb22-580a-4304-84ad-357867da6407)

## File Descriptions:
* [Data_Exploration](https://github.com/masonlonoff/WalmartSales/blob/main/Data_Exploration.ipynb): Contains high-level analysis of the dataset consisting of checking for nulls, checking data types, and more.
* [Exploratory_Data_Analysis](https://github.com/masonlonoff/WalmartSales/blob/main/Data_Exploration.ipynb): Contains frequency analysis, outlier analysis, correlation analysis, and column-specific EDA analysis.
* [Preprocessing_Manipulation](https://github.com/masonlonoff/WalmartSales/blob/main/Preprocessing_Manipulation.ipynb): Contains the preprocessing steps that are needed to achieve the neccessary dataframes for the visualizations and machine learning. 
* [Data_Visualizations](https://github.com/masonlonoff/WalmartSales/blob/main/Data_Visualizations.ipynb): Contains visualizations that explore the relationship between each column and Weekly Sales. Also, the file attempts to analyze whether or not there is a relationship between holidays and Weekly Sales.
* [Predictive_Modeling](https://github.com/masonlonoff/WalmartSales/blob/main/Predictive_Modeling.ipynb): Contains different models which attept to predict Weekly Sales. The end of the file compares the R2 and MPE scores for each model. 

### Table of Contents:

- [Description](#description)
- [Dataset Information](#dataset_information)
- [Objectives](#objectives)
- [Strategic Plan of Action](#strategic-plan-of-action)
- [Acknowledgement](#acknowledgement)
- [Disclaimer](#disclaimer)




### Description:
One of the leading retail stores in the US, Walmart, would like to predict the sales and demand accurately. There are certain events and holidays which impact sales on each day. There are sales data available for 45 stores of Walmart. The business is facing a challenge due to unforeseen demands and runs out of stock some times, due to the inappropriate machine learning algorithm. An ideal ML algorithm will predict demand accurately and ingest factors like economic conditions including CPI, Unemployment Index, etc.

Walmart runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of all, which are the Super Bowl, Labour Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks. Part of the challenge presented by this competition is modeling the effects of markdowns on these holiday weeks in the absence of complete/ideal historical data. Historical sales data for 45 Walmart stores located in different regions are available.

### Dataset Information:
**Store** - the store number\
**Date** - the week of sales\
**Weekly_Sales** - sales for the given store\
**Holiday_Flag** - whether the week is a special holiday week 1 – Holiday week 0 – Non-holiday week\
**Temperature** - Temperature on the day of sale\
**Fuel_Price** - Cost of fuel in the region\
**CPI** – Prevailing consumer price index\
**Unemployment** - Prevailing unemployment rate\
**Holiday Events:**
- **Super Bowl**: 12-Feb-10, 11-Feb-11, 10-Feb-12, 8-Feb-13
- **Labour Day**: 10-Sep-10, 9-Sep-11, 7-Sep-12, 6-Sep-13
- **Thanksgiving**: 26-Nov-10, 25-Nov-11, 23-Nov-12, 29-Nov-13
- **Christmas**: 31-Dec-10, 30-Dec-11, 28-Dec-12, 27-Dec-13



### Objectives:
1) Understand and clean-up the dataset if neccessary.
2) Conduct analysis on the dataset to determine the relationship between each column and sales
3) Determine the extent that holidays affect sales
4) Create ML models to predict sales for each store
5) Compare and rank the accuracies

### Strategic Plan of Action:
1) Data Exploration
2) Exploratory Data Analysis
3) Data Pre-Processing and Manipulation
4) Data Visualizations 
5) Predictive Modeling
6) Comparing Results


### Acknowledgement:
This analysis was conducted based on the **Walmart Dataset** by M YASSER H on Kaggle.\
(https://www.kaggle.com/datasets/yasserh/walmart-dataset?datasetId=1820993)

### Disclaimer:
The data used in this analysis was obtained from a source that does not provide an official data origin or explicit information regarding the locations associated with the data. As a result, the accuracy and reliability of the data cannot be independently verified.

Please exercise caution when interpreting and relying on the findings presented in this analysis. The absence of official data sources and location details may introduce uncertainties and potential limitations in the analysis.

The analysis is conducted based on the available data, acknowledging the possibility of data inaccuracies or biases. Therefore, the results and conclusions should be considered with caution and may not reflect the true and accurate representation of the intended population or region.

It is recommended to consult official government sources, reputable data providers, or subject matter experts for more reliable and validated information regarding the specific variables or factors under investigation.
