# US_Home_Price_Index_Home.LLC_Assignmet_Intern

Firstly Refer to Preparing_Data notebook and then Model_Building notebook to understand better.

# Approach
​
 1) Data Collection
​
 2) Data Preprocessing
​
 3) EDA & Building data science model (Machine Learning Model)
​
 4) Analyse the Results


### 1. Data Collection
Firstly, to determine the key factors that influence US Home Prices nationally, a thorough research was conducted.

Few sites and published papers were referred and some basic assumptions were made to find out the following key factors:

Articles Referred: https://www.sciencedirect.com/science/article/pii/S2666764923000383#:~:text=This%20study%20identifies%20eight%20economic,S%26P%20500%2C%20and%20government%20expenditure.

https://utkarshsinghx27.medium.com/exploring-the-impact-of-supply-demand-factors-on-us-home-prices-a-20-year-analysis-467b17447c21

https://www.westernasset.com/us/en/research/blog/deciphering-factors-that-impact-the-us-housing-market-2024-03-13.cfm

#### 1) CPI - One of the most popular measures of inflation and deflation. It is a measure of the average change over time in the prices paid by urban consumers for a market basket of consumer goods and services.


#### 2) Federal Funds Rate - It is the interest rate at which depository institutions lend reserve balances to other depository institutions overnight on an uncollateralized basis.


#### 3) Real GDP - It is an inflation-adjusted measure that reflects the value of all goods and services produced by an economy in a given year.


#### 4) Real Disposable Income per capita - It determines an individual's ability to purchase goods or services.


#### 5) Mortgage Rate - It is the interest rate charged for a home loan.


#### 6) Population


#### 7) S&P 500 - It is a stock market index tracking the stock performance of 500 of the largest companies listed on stock exchanges in the United States.


#### 8) Unemployment Rate 

#### S&P US Case-Shiller Home Price Index as a proxy for home prices.


The data for above factors was obtained from following websites:
https://fred.stlouisfed.org/series/

https://www.spglobal.com/marketintelligence/en/mi/products/us-monthly-gdp-index.html

https://finance.yahoo.com/quote/%5EGSPC/history/?guccounter=1&guce_referrer=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS8&guce_referrer_sig=AQAAABhPBaxqA-t4rzetBd4ax0Qxoad29mqpo0-zKsbOntahO8RW5Qx8X7DOQsRuPBbxfR6AmvfOIEXNgS2BWGRoIzBxq4GrCf1HbbppRe3I7UUJDUBk809N5oHLyGXCOjVhx9bu0DWYsR8YKHEXZ5SuJzc7moBUIfxJtj7Ngw9bmic0&frequency=1mo&period1=694224000&period2=1717848110




### 2. Data Preprocessing

To make data ready for analysis, preprocessing techniques such as cleaning, transforming, and integrating of data are performed which are described further in the notebook. 

The data collected from various sources is combined to form a single dataframe for efficient analysis and model building.

#### Since we're interested to find the impact in last 20 years, we'll be considering the data from 1st Jan 2004 to 1st Dec 2023.

#### The US Case-Shiller Home Price Inded is Monthly data, hence we'll be transforming data to monthly wherever necessary




### 3. EDA & Building data science model (Machine Learning Model)

Included in Model_Building.ipynb notebook

Exploratory Data Analysis is performed on the data to gain more insights and to learn hidden patterns present in the data.  




### 4. Analyse the results

Determine how each factor has historically impacted home prices.

Evaluate the overall performance of your model using metrics like R-squared, and Root Mean Squared Error (RMSE).

Understanding Coefficients (For Linear Models)

Feature Importance (For Tree-based Models)
