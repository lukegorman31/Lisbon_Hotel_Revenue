# Lisbon_Hotel_Revenue
Forecast of hotel industry revenue in the city of Lisbon, Portugal. Our data was obtained from INE which is an open source government database for all statistics relating to Portugal. 

This project was a forecating project which came with its own set of problems mainly the impact of the covid pandemic in forecasting. 
Initally we built an ARIMA model to forecast, but we were unsatififed with the results and knew Covid had a massive impact on our models performance and lead to a large mean absolute percentage error. 

![ARIMA_FC_24](https://user-images.githubusercontent.com/116017484/234243203-5c6f9582-a647-4e97-836c-73d4a7594fac.png)


One way we circumvented this was the use of Meta's Prophet algorithm which allowed us assign holidays to covid lockdowns. This was good because the model took less weight in holidays when building teh forecast and making predictions.

![prophet_24_fc](https://user-images.githubusercontent.com/116017484/234242775-9195b144-8a03-4d63-8446-9072fed3ed00.png)

With our Prophet prediction we were able to estimate the revenue of the Hotel industry in Lisbon. 


![prophet_FC_Bar](https://user-images.githubusercontent.com/116017484/234243554-63832612-2901-41ac-b6f1-a391141a35f2.png)

