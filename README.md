 Bike-Rental-Prediction
Description
Problem Statement:
In bike-sharing systems, the entire process from membership to rental and return has been automated. Using these systems, users can easily rent a bike from one location and return it to another. Hence, a bike rental company wants to understand and predict the number of bikes rented daily based on the environment and seasons.
Objective: The objective of this case is to predict bike rental counts based on environmental and seasonal settings with the help of a machine learning algorithm.
Data Set: day.csv
 
Data Description
Variable	Description
instant	Record index
dteday	Date
season	Season (1: springer, 2: summer, 3: fall, 4: winter)
yr	Year (0: 2011, 1:2012)
mnth	Month (1 to 12)
holiday	Weather day is a holiday or not
weekday	Day of the week
workingday	Working day (1: neither weekend nor holiday, 0: other days)
weathersit	1: Clear, few clouds, partly cloudy, partly cloudy
	2: Mist + cloudy, mist + broken clouds, mist + few clouds, mist
	3: Light snow, light rain + thunderstorm + scattered clouds, light rain + scattered clouds
	4: Heavy rain + ice pallets
temp	Normalized temperature in Celsius; The values are divided into 41 (max)
atemp	Normalized feeling temperature in Celsius; The values are divided into 50 (max)
hum	Normalized humidity; The values are divided into 100 (max)
windspeed	Normalized wind speed; The values are divided into 67 (max)
casual	Count of casual users
registered	Count of registered users
cnt	Count of total rental bikes including both casual and registered
 
Steps to Perform: 
1.    Exploratory data analysis
•    Load dataset and libraries
•    Perform data type conversion of the attributes
•    Carry out the missing value analysis
2. Attributes distributions and trends
•    Plot monthly distribution of the total number of bikes rented
•    Plot yearly distribution of the total number of bikes rented
•    Plot boxplot for outliers analysis
3. Split the dataset into train and test dataset
4. Create a model using the random forest algorithm
5. Predict the performance of the model on the test dataset
![image](https://github.com/user-attachments/assets/13b02097-4e00-47c8-a6e4-02df38d0053f)
