# Surfs Up 
## Overview
Vacationing in Hawaii is a new passion and I would like to return there forever and open a Surf N' Shake shop and be able to surf during my downtime.  I have some savings but need investor backing for the project.  I have put together a business plan and reached out to W. Avy as a potential investor.  He likes the business plan but wants to gather more information about the weather on Oahu before determining if he will invest. 

### Purpose
W. Avy also tried to open a similar shop at the beginning of his career and he was unsuccessful due to weather.  As a result, in order to get investor backing I will need to run analytics on weather data for Hawaii pulling information from a SQLite database to provide more sound evidence the shop will be successful.  Data was queried from a SQLite database and temperature on Oahu in June and December from 2010-2017 was reviewed.  

## Results and Summary
### Results
You can see an overview of the statistics from the data below.  

Oahu December Temperature Statistics       |  Oahu June Temperature Statistics
:--------------------------------------------------:|:----------------------------------------------------------:
![](https://github.com/lauras521/surfs_up/blob/25c9e695719b01dc9939f53e476cf48c6b6d179e/Resources/Dec_Temp_Describe.PNG)  |  ![](https://github.com/lauras521/surfs_up/blob/25c9e695719b01dc9939f53e476cf48c6b6d179e/Resources/June_Temp_Describe.PNG)

* The mean temperature in June (75F) is only 4 degrees higher than the mean temperature in December (71F)
* The standard deviations between the data sets is relatively the same.  Dec = 3.7F and June = 3.3F
* While the mean temperature is only 4 degrees lower in December, the minimum temperature is 8 degrees colder in December (December min=56F vs June min=64F).

### Summary
In addition to temperature data, precipitation data can be queried for December and June.  Below you can see the overview statistics from that data.

Oahu December Precipitation Statistics       |  Oahu June Precipitation Statistics
:--------------------------------------------------:|:----------------------------------------------------------:
![](https://github.com/lauras521/surfs_up/blob/25c9e695719b01dc9939f53e476cf48c6b6d179e/Resources/Dec_Prcp_Describe.PNG)  |  ![](https://github.com/lauras521/surfs_up/blob/25c9e695719b01dc9939f53e476cf48c6b6d179e/Resources/June_Prcp_Describe.PNG)

From the precipitation data you can see the following:
* It rains more in December (mean=0.216) than in June (mean=0.136).
* Both months have very high standard deviations for precipitation.  If you create box and whisker plots for these data sets you can see many outliers on the high side.  This data could be further investigated to see if certain stations have higher precipitation and if others have low precipitation to better finalize the location of the surf shop.  


Oahu December Precipitation Box Plot       |  Oahu June Precipitation Box Plot
:--------------------------------------------------:|:----------------------------------------------------------:
![](https://github.com/lauras521/surfs_up/blob/a1c151b112f0e697cc172a6e4adf399c27b1887f/Resources/Dec_Prcp_Box.PNG)  |  ![](https://github.com/lauras521/surfs_up/blob/a1c151b112f0e697cc172a6e4adf399c27b1887f/Resources/Jun_Prcp_Box.PNG)

Overall Oahu looks like a good location for a surf and shake shop.  The weather is warm enough year round for people to be outside wanting to surf and there are many days without rain.  I would build some coverage and/or indoor seats for those wanting to enjoy a shake on days there might be a popup shower, but it looks like a shake and surf shop has plenty of opportunity to be successful in Oahu.  
