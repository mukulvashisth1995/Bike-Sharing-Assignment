# Linear Regression - Bike Sharing Assignment

This project has been submitted for evaluation on Linear Regression module for Upgrad. This involves study of different independent features and their relationship with the target variable for making predictions.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)



## General Information
- A US bike-sharing provider BoomBikes has a daily dataset on the rental bikes based on various environmental and seasonal settings. It wishes to use this data to understand the factors affecting the demand for these shared bikes in the American market and come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown due to corona pandemic comes to an end.
- The company wants to know:
  - Which variables are significant in predicting the demand for shared bikes.
  - How well those variables describe the bike demands



## Conclusions
Studied all available features in indentifying their significance in deriving the usuage for bike users. Some of the conclusions made on data available
- Year : seeing a huge growth in the no. of users in 2019 (2047742) when compared with 2018 (1243103) as visible from plot
- Season : fall and summer account for maximum number of users availing services as compared with winter and spring (as snow and rain tend be difficult for bike rides in general)
- Month: Aug, Jun, Sep, Aug attracts maximum people where the harsh winter days (Jan, Feb, Dec) see less people
- Holiday : working days attract more people towards the service as compared to holidays
- Weekday: one interesting insight here is that people using bike services on weekends are maximum. Implying that maximum people generally run household errands or fun activities on weekends and thus only explanation for these high numbers on weekends
- Working day : on comparison w.r.t. 5 working days and 2 non-working days, for obvious reasons, people using for weekdays would come out to be higher
- Weather situation : favourable weather attracts more people to use bike services as visible from the plot (clear skies has maximum people enjoying bike services as compared with cloudy and light rain or snow. Heavy rain and snow times have no user availing bike services as for obvious reasons
- Temperature : Indicates a decent positive relation. Harsh winters seeing low users for the service and as temperature increases, it attracted more users to avail the bike services
- Humidity : Indicated very low negative relation, implying not to be an influencing factor deriving more users to bike service provider
- Windspeed : Presented significant negative relation, as high windspeeds not favourable for bike rides


## Technologies Used
- library -  pandas  version  1.4.2
- library -  numpy  version  1.21.5
- library -  seaborn  version  0.11.2
- library -  matplotlib  version  3.5.1
- library -  sklearn  version  1.0.2
- library -  statsmodels  version  0.13.2


## Acknowledgements
- This project was done as part of the Machine Learning and Artificial Intelligence Program by upGrad in asssociation with IIITB


## Contact 
Created by [@mukulvashisth1995] - feel free to contact!



