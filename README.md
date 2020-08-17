# Using ARIMA model predict Covid-19 cases for US and Canada

Project Start Date: 7th March 2020 
Project End Date: 19th March 2020

Question:

- How many total number of covid-19 cases will US and Canada have in the next two weeks? 

Data Approach:

Knowing that in March 2020, China was the epicenter of this pandemic, China's confirmed cases from 22nd Jan to 13th March were taken in consideration.
This data was extracted from John Hopkins University's github page. It was parsed, cleaned and then trained using ARIMA model to predict the following two weeks of 
cases in US and Canada. 

Data Source: 

https://github.com/CSSEGISandData/COVID-19

Limitations:

The predictions were solely based on the China's covid-19 case trajectory from 22nd Jan to 13 March. No other parameters like social distance, travel ban, lockdown, etc. were taken into consideration for this analysis.
