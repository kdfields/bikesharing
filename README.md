# **NYC Citi Bike Analysis**
#### Module 14 - Tableau

## **Project Overview**
The purpose of this project was to analyze New York City Citi Bike data to see if it made business sense for investors to start a similar bike-share company in Des Moines, Iowa.  The Citi Bike data will be analyzed to figure out how the bike-share business actually works in New York City before creating a business proposal on how such a bike-sharing company might work in Des Moines.  Visualizations will be created to better understand and our team will analyze these to determine how many riders, the gender breakdown of riders, the type of riders, the most popular times for rides, and the most popular spots in town to start and end a ride.

### **Resources**
+ Source Files: 201908-citibike-tripdata.csv, 201908-citibike-revised_tripdata.csv
+ Software: Tableau, Python 3.7.6, Jupyter NB, Pandas Library

## **Results**
The Tableau story containing this data can be found [here](https://public.tableau.com/app/profile/kyle.fields/viz/NYCCitiBikeData-August/NYCCitiBikeData-August).

### **NYC Citi Bike Summary Statistics - August**

![image](https://user-images.githubusercontent.com/113741694/229301565-5c0d31a0-3dcc-4673-952d-effff2182591.png)

A majority of riders are male who are Citi Bike subscribers (pay a monthly fee to access Citi Bikes).  65% of riders are male, 25% are female, and 10% are of unknown gender.  81% of riders are subscribers, while 19% ride as guests.

### **Most Popular Starting and Ending Locations**

![image](https://user-images.githubusercontent.com/113741694/229301835-70ac450e-ec0f-4a62-9dfd-898e9c35a820.png)

The maps showing the most popular starting and ending locations are almost identical (the bigger and darker spots are mostly clustered in Midtown Manhattan and Lower Manhattan) .  This indicates that the most popular starting locations are also the most popular ending locations.  This is likely because these locations are used by riders commuting to work or school on a regular basis.

### **Bikes Due For Repair**

![image](https://user-images.githubusercontent.com/113741694/229301983-5400c3c4-dd7f-44af-a9b2-1ed3b825c7fc.png)

The darker colored boxes indicate the bikes that are due for repair. More analysis needs to be done to see why these bikes need repair.  Using the data from the Most Popular Starting and Ending Locations these bikes needing repair can most likely be found in those popular starting and ending locations clustered around Midtown and Lower Manhattan.

### **Checkout Times**

![image](https://user-images.githubusercontent.com/113741694/229302080-ceffb9f2-1e56-4403-9a2d-91f8e0664db8.png)

An overwhelming majority of bike rides lasted for less than 1 hour and most of those rides lasted less than 20 minutes.  This indicates most Citi Bike rentals are riding for a purpose (commuting to work or school) and not for pleasure. Checkout Times by Gender reflects the analysis observed in the Citi Bike Summary Statistics that a majority of riders are male, however, the trip duration of female and unknown riders followed a similar pattern of male riders.

### **Trips by Weekday**

![image](https://user-images.githubusercontent.com/113741694/229302185-371e96e1-23aa-43f8-96f9-10db8895a6b3.png)

A pattern emerges showing the most popular times for Citi Bike usage are during the morning commute (6am - 9am) and evening commute (4pm - 7pm).  More analysis needs to be performed to see why there is a clear lack of riders during the Wednesday evening commute. On the weekends Citi Bike rentals are consistent from 10am to 6pm.

## **Summary**
This analysis has given us a much better understanding of the bike-share business operating in New York City and how such a business can succeed in Des Moines.  We have learned that a majority of riders are male who subscribe and pay a monthly membership fee to access Citi Bikes.  Our team has discovered that the most popular starting locations are also the most popular ending locations, indicating that most riders utilize Citi Bikes for a specific purpose like commuting to work or school. We were able to gain insight into the most popular checkout times (weekday mornings and evenings) which confirmed our belief that a majority of weekday riders use Citi Bike for a specific purpose.  More analysis needs to be done to see which rental locations are under-utilized or not used at all.  These locations could be relocated to more popular locations such as Midtown or Lower Manhattan, if necessary.  We know that more bikes are rented on weekdays compared to weekends but further analysis should be performed on the trip duration of weekday rides compared to weekend rides to see if trip duration is longer on the weekends.  Perhaps bike rental rates could be lowered on the weekend to incentivize more riders.




