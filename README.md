# VBA_Challenge

## Overview of Project

The purpose of this analysis is to gather stock market data for Steve which will help him decide which stocks to buy. The stock market data we used for this analysis includes stock ticker, date, opening price, high price, low price, closing price, adj close, and volume. The data is recorded in daily increments. 

To help Steve get a big picture understanding of the data, I found the total daily volume and yearly return for the years 2017 and 2018.

I had already found this data in a previous analysis, but in this analysis I refactored the code so that so that the stock market data only needs to be looped through once. The purpose of doing this is to make the application run faster.

## Results

In 2017, all stocks had positive returns except for TERP. DQ had the highest return and the lowest total daily volume.

![All_Stocks(2017)](https://github.com/jolwig/VBA_Challenge/blob/main/All_Stocks(2017).PNG)

In 2018, 10 out of the 12 stocks in the dataset had negative returns. The two stocks that had positive returns, ENPH and RUN, outperformed the average return (-6.6%) of the dataset by a large margin. ENPH and RUN also had the highest total daily volume. JKS and DQ were the two lowest perfroming stocks.

![All_Stocks(2018)](https://github.com/jolwig/VBA_Challenge/blob/main/All_Stocks(2018).PNG)

## Summary

The advantage of the refactored code is that it runs faster than the original code. However, the original code looks easier to read and understand which is good if you are working with a team.

![refactored 2017](https://github.com/jolwig/VBA_Challenge/blob/main/VBA_Challenge_2017.PNG)
![refactored 2018](https://github.com/jolwig/VBA_Challenge/blob/main/VBA_Challenge_2018.PNG)
