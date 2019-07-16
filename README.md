# Capstone-Project-2

## Introduction

### Background
The value of individual stocks often do not seem to reflect the fair value due to human error. Instead, the price stocks trade at seem to be determined more by the human perception of the stock. Behavioral economics states that the emotions and moods of
individuals affect their decision making process. People and news outlets are constantly voicing their opinions about a variety of subjects, stocks included, on Twitter. Though a single tweet may not be signiﬁcant, a large collection of them can provide data with valuable insight about the common opinion on a particular subject. Twitter, therefore, can be used to gauge the public sentiment and possibly predict stock price movements. The famous research paper by Bollen et al had performed Twitter sentiment analysis to predict price movement of the Dow Jones Industrial Average (DJIA). However, this study will focus on 4 individual stocks: Netflix ($NFLX), Disney ($DIS), Amazon ($AMZN), and Google ($GOOGL).

### Impact
Applying sentiment analysis to stock movement forecasting has been prominent field due to the potential financial gains from it. Without a doubt, investment banking firms have done extensive research and built model based of the idea. Twitter API makes its data readily available to the public, so why shouldn’t individual investors benefit from the wealth as well? By analyzing these trends and monitoring public opinion of companies, we can possibly build a predictive model to exploit market inefficiencies and anticipate changes in the market before they happen.

### Data
**Twitter data:** The Twitter API was used to pull tweets mentioning the stocks of interest. (Note: Twitter prevents users from pulling tweets past 7 days old with the standard API key) Sentiment Analysis “VADER” will be used to analyze the sentiment of the tweet.
**Historical Stock Data:** Alpha Vantage API was used to retrieve historical data for the stocks of interest. 

## Reports
### Final Report
Written report that walks through the data wrangling, exploratory data analysis, and process of building the final time series regression model.

### Final Powerpoint
A summary presentation of the data wrangling, exploratory data analysis, and regression model.

## Other Files
### Code
This folder contains all the code for each segment of the exploration.

### Intermediary Reports
This folder contains all the reports created throughout the exploration.
