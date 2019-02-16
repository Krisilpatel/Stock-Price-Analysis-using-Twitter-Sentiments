# Stock-Price-Analysis-using-Twitter-Sentiments

Problem Statement:
Stock market is one of the important places where the scope of data science is unprecedented. One of the major factor driving stock prices are people's sentiments.
It is historically proven that when sentiments are negative for a financially strong company, it can dwindle the prices in short run and vice versa.
The primary objective of this project is to analyze how greatly prices are affected by sentiments and to judge the market based on it.

Approach:

The workflow of this project is divided as follows:
1) Get the historical prices of Dow Jones index companies.
2) Web scrap text of December month from tweeter using Python code and convert it csv files for each company.
3) Upload data to Hive to perform sentiment analysis.
4) Upload DJIA files on R to perform linear regression.
5) Upload all files on Tableau to create visual inferences.

I have used Tweepy library to perform scrapping using Python and stored it in JSON format. After that I have converted JSON files to CSV files. 

