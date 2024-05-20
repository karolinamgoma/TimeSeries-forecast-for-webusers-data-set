# TimeSeries-forecast-for-webusers-data-set
It is a TimeSeries analysis with forecast using ARIMA methods.
Data is coming from 
https://www.kaggle.com/datasets/bertiemackie/daily-website-users. It contains the number of unique customers who logged in to their accounts on a website. The user_numbers column shows this count. 
First part of the analysis aming forecast for daily number of users who are willing to log in the webside. I used method ARIMA (6,0,0) and ARIMA (8,0,0). Both gives similar results but better performed ARIMA( 8,0,0).
Second part of analysis is focusing on finding some monthly sesonality. I build two model for comparison, one where we eliminate sesonal component but didn't do differencing and second one with elimination of sesonal component and differencing. Model Forecast for webusers_diff, where we eliminate sesonal component and did differencing is performing better however far away from good prediction.
