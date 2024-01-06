# Project Name
> BoomBikes Bike-Sharing Demand Analysis


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
BoomBikes, a U.S. bike-sharing provider, is addressing revenue decline due to the COVID-19 pandemic by focusing on understanding bike-sharing demand in the American market. The company has engaged a consulting firm to analyze key variables that influence demand, including meteorological factors and user preferences. The goal is to develop a predictive model for shared bike demand, using insights from a comprehensive dataset. This model will guide management in strategic decision-making, ensuring they meet customer expectations and adapt effectively to changing market conditions. The approach involves three main steps: data understanding, cleaning, and exploration; data modeling and model tuning; and prediction and inference. The primary objectives are to identify significant factors influencing bike-sharing demand and to evaluate how effectively these factors predict demand.

For this analysis, we are using a dataset containing the number of bookings for several days across 2018-2019 along with some potentially relevant attributes that the business feels might influence the demand.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
The determinants of bike-sharing demand can be categorized as follows:

1. Annual Trend: There is an observable upward trend in demand on a yearly basis, as initially indicated in our analysis.
2. Holiday Influence: Demand fluctuates based on whether the day is a holiday.
3. Weekday Impact: The distinction between weekdays and weekends significantly affects demand.
4. Daily Temperature: The ambient temperature on any given day plays a crucial role.
5. Weather Conditions: Specific weather patterns such as Light Snow, Light Rain with Thunderstorm and Scattered Clouds, or Light 
6. Rain with Scattered Clouds have a notable impact.
7. Mist-Related Weather: Variations of misty conditions, including Mist with Cloudy, Broken Clouds, Few Clouds, or Solely Mist, also influence demand.
8. Seasonal Effects: The demand varies considerably across different seasons, especially during spring, summer, and winter.

Assuming all other variables remain constant, each specific factor impacts the demand for bike sharing as follows:

1. Year-over-Year (YoY) growth is approximately 23.2%, based on data from 2018 to 2019.
2. Demand typically reduces by about 7% during holidays.
3. Weekdays experience a 5.3% increase in demand.
4. A one-degree Celsius increase in temperature correlates with a 48% surge in demand.
5. Adverse weather conditions such as thunderstorms or light rain/snow lead to a 29.4% decrease in demand.
6. Cloudy or misty weather conditions result in a roughly 7% reduction in demand.
7. Seasonal variations show a 9.8% decrease in spring, a 3.3% increase in summer, and an 8.5% increase in winter.

These data points indicate that weather conditions and temperature significantly influence bike sharing demand. Inclement weather and cooler temperatures generally reduce demand. Apart from weather factors, demand is higher on holidays and weekdays, potentially attributable to increased leisure activities and commuting needs. Additionally, there is a marked preference for bike rides during summer and winter compared to spring.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Python version 3.12.1
Jupyter Notebook

- numpy==1.26.3
- matplotlib==3.8.2
- pandas==2.1.4
- scikit-learn==1.3.2
- scipy==1.11.4
- seaborn==0.13.1
- statsmodels==0.14.1


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project was conducted as a component of the Linear Regression assignment, integrated within the curriculum of the Executive Post Graduate Program in Artificial Intelligence and Machine Learning offered by UpGrad. I extend my sincere gratitude to the International Institute of Information Technology Bangalore (IIITB) and the UpGrad team for their meticulous efforts in structuring and providing this educational assignment. Their contributions have been instrumental in enhancing my learning experience.


## Contact
Created by [@somrikbanerjee] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->