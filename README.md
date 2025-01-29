# Bike Demand Prediction
> This project focuses on predicting the demand for shared bikes based on various factors such as weather conditions, seasonal trends, and time of the day.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Background: The project aims to build a predictive model to estimate the demand for shared bikes, a critical component for optimizing bike-sharing systems and resource allocation.
- Background: The project aims to build a predictive model to estimate the demand for shared bikes, a critical component for optimizing bike-sharing systems and resource allocation.
- Dataset: The dataset used contains information about bike rentals, including weather attributes, seasonal trends, and time-related features (such as hour of the day, day of the week). It includes columns like temperature, humidity, wind speed, and weather conditions.


## Conclusions
- The demand for shared bikes is strongly correlated with weather conditions and time of the day. For instance, higher temperatures and certain weather types, like clear skies, lead to increased bike usage.
- Seasonality plays an important role, with bike demand increasing in the spring and summer seasons.
- The wind speed and humidity were found to have a less significant impact on bike demand but still contribute to variations.
- A linear regression model was used to model the demand, and residual analysis confirmed the assumptions of normality and homoscedasticity.



## Technologies Used
- Python - 3.8
- pandas - 1.3.3
- numpy - 1.21.2
- scikit-learn - 0.24.2
- statsmodels - 0.12.2
- matplotlib - 3.4.3
- seaborn - 0.11.1



## Acknowledgements
- Thanks to the creators of the dataset for providing valuable data to conduct this analysis.
- Special thanks to the open-source community for developing the Python libraries used in this project.
