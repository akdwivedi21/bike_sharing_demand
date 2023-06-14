# bike_sharing_demand
  ## Project Objective
    The objective of this project is to forecast the demand of bike base on various features given in the dataset.
    This model will help to make the business more profitable.
    
  ## Table of Contents
  * [General Info](#general-information)
  * [Technologies Used](#technologies-used)
  * [Conclusions](#conclusions)
  * [Acknowledgements](#acknowledgements)


   ## General Information
     The objective of this project is to forecast the demand of bike base on various features given in the dataset.
     This model will help to make the business more profitable.
     day.csv is used as dataset of model building.
   
   ## data set
     day.csv is the given dataset.
    
   ## data dictionary
      - instant: record index
      - dteday : date
      - season : season (1:spring, 2:summer, 3:fall, 4:winter)
      - yr : year (0: 2018, 1:2019)
      - mnth : month ( 1 to 12)
      - holiday : weather day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
      - weekday : day of the week
      - workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
      + weathersit : 
        - 1: Clear, Few clouds, Partly cloudy, Partly cloudy
        - 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
        - 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
        - 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
      - temp : temperature in Celsius
      - atemp: feeling temperature in Celsius
      - hum: humidity
      - windspeed: wind speed
      - casual: count of casual users
      - registered: count of registered users
    - cnt: count of total rental bikes including both casual and registered
    
   
     
   ## Technologies Used
      - python
      - jupyter notebook
      - pandas
      - numpy
      - matplotlib
      - seaborn
      - sklearn
      
     
   ## Acknowledgements
     - This project is part of assignment done as part of  IIIT-B EPGP program.
     
   ## Conclusions
     Below are the top 3 features:
     1) Temp
     2) Year (yr)
     3) weatersit as "Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds"
      
   ## References: 
     - https://seaborn.pydata.org/
     - https://pandas.pydata.org/pandas-docs/stable/reference/frame.html
     - https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.RFE.html

  ## Contact
    Created by [@akdwivedi21] - feel free to contact!
