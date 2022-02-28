# What factors affect a vehicle's price?

### Background
This project is part of the Data Scientist training program from Practicum by Yandex. More info in link below:

https://practicum.yandex.com/data-scientist

### Project Setup
You're an analyst at Crankshaft List. Hundreds of free advertisements for vehicles are published on your site every day. You need to study data collected over the last few years and determine which factors influence the price of a vehicle.

#### Technical Skills Used: Python (pandas,numpy,seaborn,matplotlib)

### Data Description
The dataset contains the following fields:
* price
* model_year
* model
* condition
* cylinders
* fuel — gas, diesel, etc.
* odometer — the vehicle's mileage when the ad was published
* transmission
* paint_color
* is_4wd — whether the vehicle has 4-wheel drive (Boolean type)
* date_posted — the date the ad was published
* days_listed — from publication to removal

### Conclusion

Conclusion
The main objective of this project was to discover what factors affect a vehicle's price. Below are insights discovered:

* Vehicles that are listed for more than 150 days are rare
* The average amount of days listed is about 40 days.
* Sedans and SUV's are the most popular type of vehicle listed. 
* The vehicle age when listed, average mileage, and condition of the vehicle impact price the most:
   * Newer vehicles are more expensive than older ones
   * As condition improves so does price.
   * Depending on the vehicle type we can see that certain transmission types are more expensive. For example, SUVs with a manual transmission are more expensive thatn automatic
