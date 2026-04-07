## Customer Segmentation Using Excel.
This is an end to end project that I recreated. 

The objective of the project is to provide valuable insights into "Who are our custonmers in the banking sector?"

Time is moving fast and technology is evolving. Covid-19 Lockdown led to the closure of many businesses and massive layoffs.

This dataset holds records dating as far as 2015 to 2025; a 10 years anlaysing of customers in the banking sector.

The process of analysing this data involved dividing our customers in terms of their:

-Demographic i.e age, gender and income, 

-Geographic i.e City and State,

## Data Dictionary

The dataset comprises of 500 rows and 9 columns.

- CustomerID	
- Name	
- Gender	
- Age	
- Region	
- Occupation	
- Income	
- Customer_Segment i.e private, corporate or Retail	
- Join_Date


## Dashboard Overview

<img src="./Customer Segmenatation.png" Alt="Customer Segmenatation Report">

Other than the objective, this project gave me a refresher on:

-Data cleaning;

-Excel conditional formatting;

-Report connections; 

-Charts  styling & formatting; &

-Creation of Navigation bar.

## Data Preparation & Cleaning

I checked for duplicates, missing values and outliers; the data did not need too much cleaning. As such, I move to data prepartion for Analysis.

1. I added new columns using power query's Conditional formatting:
- Generation i.e Gen Z = 13-28 years & Millenials 29-44 years;
- Income Bracket i.e 0-100,000 = "Low", 100,001 - 300,000 = "Medium"; &
- Tenure Group i.e < 1 year = "New", < 3 years = "Emerging".


2. Created Pivot tables for my Key Performance Indicators:

- Count of customers;
- Average Age
- Average Income 
- Average Total Years 


<img src="./Pivot Tables.png">

-Went ahead and created pivot tables to compare customers by:

- Age group Vs Gender

- Income bracket Vs Gender

- customer tenure representation by %.

-Used time series analysis to show the growth of customers over the years. 

## Insights

1. Customer by generation

Gen Zs hold the lowest number of accounts whereas Female Boomers and Male Mellenials hold the highet number of accounts.

2. Customer Growth Timeline

There was a steady growtgh of customers from the year 2015 and at its peak in 2019. The numbers drop from the same year through 2020. This might have been caused by the covid-19 pandemic as business closed down. 

The growth came in hand with the removal of the lock downs around 2021. Peaked in 2023 and has been dropping gradually towrds 2025.

3. Customer Wealth Profile

Both genders: male and female, from the low income (below 100,000,000.00) hold the highest number of accounts in the bank. 

4. Professional Profile of Our customer Base

Female doctors top in the number of accounts they have Followed by female engineers. 

## Recommendations. 

- Study the marketing strategies used to get clients during the early years of 2017 through 2019 and apply them in the comming years. 

- Adopt the new technologies of storing and investing money to appeal to the new generation (Gen Zs) who are into crypto currency. This resonates with them. Better still, embrace the new technologies- everything shouuld be done online from the comfort of ones' home, office or a holiday hotel.

