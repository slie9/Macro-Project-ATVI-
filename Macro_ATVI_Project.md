| **Activision Blizzard (ATVI)**   **5 Years of Data**      |
|-----------------------------------------------------------|
|   **Sydney Lieske** -- | 

## Abstract

This project takes 5 years of ATVI stocks and has an analysis using R. We found this data and decided to do basic summary statistics, linear regression (residuals vs fitted, normal q-q, scale-location, and residuals vs leverage), and plotted two moving averages for the stock price for all days since 2017. We wanted to use Blizzard-Activision as we enjoy Blizzard games, and the company has had some issues in the recent years that would be interesting to show with data. All of us had done some research on what we should do for this project, and we agreed that using R would be beneficial. We found that in 2019 \~ there was a sharp decrease in the closing price, which could be due to the Hong-Kong issue and delays on key games.

## Introduction

Our group felt that this would have been an interesting topic to cover as we knew that there would be interesting data. In R, we had run a linear regression on the monthly time index and the closing price. From there we took a 10 day window and 30 day window, and using the time series data plotted the price and moving averages since the start of our dataset which is 2017.

By doing this we were able to visualize how the stock fit against time. It was really interesting to see the sharp decrease around the time that the company had issues. Our goal was to be able to see if we could find anything from the stocks that we could relate to real time issues that the company had. What made us want to do this project was not just because we played Blizzard games, but the surrounding issues the company had as a whole.

## Data

The dataset that we used for this project comes from Yahoo Finance. We had taken the last 5 years of the historical data to use for our analysis. The data included in this dataset are the date, open, high, low, close, adj. close, volume, and we added an ID time index for it. For the time series portion, the data needed to be indexed.

## Prior Literature

Some research we did was look up if Blizzard-Activision had any reason of why their stocks would have decreased sharply during 2019. We had forgotten about some of the issues that Blizzard, as a company had. We did not do much research when looking for a dataset as Yahoo Finance had everything we needed. The research we did was to help us understand our analysis better and why our plots looked like they did.

## Methods

We decided to use R and RStudio for this project as we found it to be beneficial with our data analysis. Most of our group is comfortable enough with R to use. We did not want to just use Excel as we thought R could provide us with better information about our dataset.

## Results

Anyone interested in stocks or data analysis could benefit from our project. Being curious was the first step in starting this project. At the end of this project, we had found interesting data and were able to put it together with the real-world issues. Our linear regression model of monthly close prices vs the time index shows that the coefficient is statistically significant. We had also found the peak closing price, lowest recorded closing price, and the average. Which are, in order: Min: 68.22, Mean: 68.22, and Max: 68.22.

<img src = "Images/res_fitted.png"> 
Figure 1 is the residuals vs fitted plot of the linear regression. Linearity is violated.
<img src = "Images/moving_avg.png"> 
Figure 2: The price and moving averages for all days since 2017, we can see the dip where ATVI plummeted in 2019 and where it starts to build back up.

## References

https://finance.yahoo.com/quote/ATVI/history/
