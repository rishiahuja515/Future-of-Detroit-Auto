# Future of Detroit Auto  
---  

General Motors is the largest automanufacturing company headquartered in the United Staes. With the recent shift to Electric Vehicles, GM has hired Ahuja Consulting to predict the future price of gasoline to decide whether to invest drastically more in EV.

![GM](Images/GM%20Factory.jpeg)  
*GM Factoryh*  

---
## Study Authors  


**Rishi Ahuja**  
rishiahuja515@gmail.com  
https://github.com/rishiahuja515  



---
## Business understanding  

Stakeholder: General Moters  
Business Problem: Will gasoline prices continue to rise over time?  

Our goal is to inform General Motors if the price of Gasoline will continue to raise over time and because of our results, should General Motors decide to invest significantly more in Electric Vehicles. The cost of a barrel is nearing an all time high and ccording to the US Department of Energy, Gasoline has to be at $2.50 a gallon to make the cost of owning and operating an EV worth it.With that said, according to Car and Driver 5% of all vehicles in the United States are electric in 2022...which is a 97% increase from 2021. Currently, Ford, your main competitior is out shining you in EV investment. They have recently passed Hundai to 2nd in all US EV sales. Ford Plans to spend $30 billion by 2025 as compared to GMs $6.6 Billion 

  

---  
## Data Understanding & Preperation

The analysis data was provided by the United States Energy Information Administration, (https://www.eia.gov/). The dataset included information about oil prices from the WTI, natural gas prices form Henry Hub, and the average price of gasoline from the EIA.   

The dataset was reduced to 1600 data points, just looking at the average EIA Gasoline prices.  



---
## Data Analysis  

We initially generated some charts to examine the data at a high level.  
Our first chart plotted the price of WTI Oil and the Price of Henry Hub Gas.  
![Oil vs Gas](Images/Oil%20vs%20Gas.png)  

We decided not to use this data becauase we were able to find the Weekly Gas Price According to the EIA. 

We Split this Data using a Train/Test Split using May 4, 2020 as our date. If you refer to the graph above you can see the negative Oil Price due to the COVID-19 Pandemic.
![Train/Test](Images/Train%3ATest.png)  

Some of the limitations of the data include a possible change in refining costs and if that will effect the price of gas. We were also only able to access Weekly Data instead of Daily Data. We beleive that Daily Oil Prices would give us a more accurate model. Our Data is only through June 2022 and with the very recent drop in oil prices, we would need to use the more recent numbers. Also another limitation is the current war in the Ukraine a resolution could drastically effect the future price. 

---
## Models  

We used an ARIMA  model to predict and forecast future Gas prices. It's a model used in to measure events that happen over a period of time. The model is used to understand past data and predict future data in a series. Our Root mean square error was 1.59 dollars. This tells us that the price my future gas is off by an average of a $1.59. Although the error is high, it still keeps the prediction above the target line of $2.50. Unfortunately with the volatility of the market and War going on in Ukraine my model needs more data to more accurately predict the price of gas. 
![Prediction Model](Images/Gas%20Price%20Pred.png) 

---
## Recommendations  

Based on our findings, GM Should follow fords path and increase their currently forecasted $6.6 billion dramatically. With the Price of Gasoline projected to stay over $2.50 nationwide, it only makes sense for GM to increase their spending in EV. Furthermore, the Enviromental impact this would have would increase public relations for GM.

---
## Next Steps  

We recommend 3 different areas in which to concentrate for future study and analysis.  
1. The current,  price of gas is dramatically different depending on what part of the country you are in. We would like to look at Regional data so I can better recommend on where most to market the new EV plan. 

2. With new regulation, we would like to further dive into the Tax benefit this would have for General Motors. 

3. Lastly, We were only able to look at gasoline data. We would want to look as Diesel data as well. 




```