# Linear Regression Problem - Bike Share

> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short-term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock", which is usually computer-controlled, wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock in the same system.
> In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better, stand out from other service providers, and make huge profits.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
* We must model the demand for shared bikes with the available independent variables. The management will use it to understand how the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and customer expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.  
* The dataset that is being used is Bike Sharing dataset.
Dataset characteristics
=========================================
	
day.csv have the following fields:
	
	- instant: record index
	- dteday : date
	- season : season (1:spring, 2:summer, 3:fall, 4:winter)
	- yr: year (0: 2018, 1:2019)
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

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Fall season has the most bike share count, where as the Spring has the minimum count.
- The number of counts in 2019 is significantly (33.33%) more than in 2018.
- The number of counts in Jun, July, Aug and Sep are the most.
- The count is more when the weather is clear.
- The r2 score for the train and test datasets were: 0.7395, 0.7752
- We see, the important features in the final model were:
    - year, windspeed, spring, summer, winter, Jan, Sep, Sun, LightSnow and Mist.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python version 3.10
- Microsoft word

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@nbljain] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
