# Investigation of Trends in Electricity Generation in the U.S.A with a Focus on the Effects of the Climate Urgency, Population and Efficiency on the Deployment of Different Energy Sources
Packages: Pandas (latest version recommended), xlrd, plotly, 
matplotlib, seaborn, chart studio
## Introduction
The energy data used pulled from the [United States' Energy Information Administration (EIA)](https://www.eia.gov/) while population data was extracted from [Wikipedia](https://https://en.wikipedia.org/wiki/Wikipedia:About).
Questions answered:
- What has been the trend of the various energy sources in electricity generation from 1990-2020?
- Rank up the total electricity generated by each state from 1990-2020. Which states have the highest and lowest generations?
-Rank up the total electricity generated by each state from different energy sources in 2020
- Classify the states based on how efficient and conservative their respective residential and commercial end-use sectors consume generated electricity. 
- How fast are US states in phasing-out coal since COP21? 
- How fast are U.S. states adopting natural gas as a transition fuel since COP21?
- How green has U.S. states' electricity generation been since COP21? 
- How pink has the U.S. states' electricity generation been since COP21?
- For the High-Efficient states, how clean has their electricity been since the adoption of the Paris Agreement? 
- For the Low-Efficient states, how clean has their electricity been since the adoption of the Paris Agreement? 
- Was the electricity generated dependent on the population in 2020?
## Few Highlights
![newplot (3)](https://user-images.githubusercontent.com/85615800/188329905-ca92654f-fb42-4a7e-a184-b32b89d9576a.png)
![newplot (5)](https://user-images.githubusercontent.com/85615800/188330144-135b90e9-e58e-4043-895a-5eae6296e99f.png)
![newplot (4)](https://user-images.githubusercontent.com/85615800/188329929-e832fd0c-2410-4d54-913e-75881ee8e042.png)
## Limitations
The author ignored the presence of outliers in the energy dataset for 2 reasons:
- The is coming from a very authoritative source (the EIA) and has a reputable history of providing accurate and precise data.
- Electricity is sourced from energy sources which are critically both geopolitically and economically. For instance, according to the EIA, natural gas price is dependent on supply-side factors such as the amount of natural gas production, the level of natural gas in storage, the volumes of natural gas imports and exports. it is also dependent on demand-side factors such as variations in winter and summer weather, the level of economic growth and the availability and prices of other fuels
## Conclusion
**Trends**
- Coal is gradually been phased out with Natural gas use for electricity generation exceeding it in 2016, a year after the COP21. Renewables have maintained a steady increase since 2007 and exceeded coal-fired electricity in 2020. In 2020, Nuclear electricity generation also exceeded coal-fired electricity generation. Petroleum-Fired electricity started plummetting in 2005 after peaking in 1998. Petroleum, other gases and others energy sources were all the least used energy energy sources for electricity generation in the U.S.A from 1990-2020.
- Texas has generated the highest cummulative electricity generation between 1900-2020 while the District of Columbia generated the least.
- In 2020, 19 states majorly sourced their electricity from natural gas. Renewables was the most-used energy source in 10 states. Coal was also the most used electricity source in 10 states in 2020  while Nuclear was the most used in 6 states.

**Efficiency**
- High Efficiency: 12 states and 1 capital
- Medium Efficiency: 13 states
- Low Efficiency: 13 states
- Mid-High Efficiency: 12 states

**Comparison of Electricity Generation Level in 2020 and 2015 to Indicate the Likely Effect of the Climate Urgency**
- Coal-Fired Electricity: Decreased in 3 states. Increased in 47 states and 1 capital.
- Natural Gas-Fired Electricity: Decreased in 11 states. Increased in 39 states and 1 capital.
- Nuclear-Sourced Electricity: Decreased in 13 states. Increased in 17 states.
- Renewables-Sourced Electricity: Decreased in 11 states. Increased in 39 states and 1 capital.

**Relationship**
- Electricity generation seemed fairly positively dependent on population size,with land area playing in a factor in few occasions.
## Author: Clifford Okwudili Aniakor
## Date: 04/09/2022
