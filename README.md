# Predicting the costs of Natural Disasters
Weather disasters in the United States cost the US millions and billions of dollars every year.  When it comes to these disasters it is a question of if not when. Looking at natural disasters and their costs from 1980 to 2023, I will try to predict how much a disaster will cost so the US can be better prepared.  
1.	Data
I used 3 datasets about US billion dollar Weather and climate Disaster from 1980 to present data from the government. The datasets contains U.S. disaster cost assessments of the total, direct losses ($) inflicted by: tropical cyclones, inland floods, drought & heat waves, severe local storms (i.e., tornado, hail, straight-line wind damage), wildfires, crop freeze events and winter storms.  The datasets also show the number of deaths associated with each disaster. I also used inflation datasets to see if there was a correlation between inflation and the disaster costs.  

Billion Dollar weather disasters
https://catalog.data.gov/dataset/u-s-billion-dollar-weather-and-climate-disasters-1980-present-ncei-accession-02092681

https://www.ncei.noaa.gov/access/metadata/landing-page/bin/iso?id=gov.noaa.nodc:0209268

https://www.ncei.noaa.gov/access/billions/mapping
2.	Data Cleaning
  1.	The first part of data wrangling after I read the datasets was to merge the state disaster dataset with the state cost data set.  I also looked at the mean, max, and standard deviation of the cost of the disasters.
  2.	Created data frame with the number of deaths per disaster
  3.	Grouped the dates by year and created a data frame based on the year and disaster
   

3.  Machine Learning 
	For the Machine learning I decided to do different types of regression models to predict the price.  I used a linear regression model, a decision tree regression model, and a random forest regression model. I chose the random forest regression model due to its accuracy score and it cross validation scores.

  
4.Takaways
The models didn’t have enough predictive power so I added population data to see if I could get a better prediction.  I felt that adding the population would better help with the prediction because where there are more people there is more likely to have damage happen.
	
5.Predictions
Unfortunately adding the population to the data did not improve the predictive power.  
6. Future Improvements 
Future improvements for the data I would use is the cost and type of the infrastructure.  Knowing the type of damage done and how much it costs would be helpful for predictions.  


