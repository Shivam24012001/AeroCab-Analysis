AeroCab Services provides cab services from five designated airport pickup points to various destinations in the Bangalore metropolitan area. The company has identified two primary peak periods:

Morning Peak Time: 5:00 AM to 9:00 AM

Evening Peak Time: 6:00 PM to 11:00 PM.

Outside these hours, the service operates during non-peak times. Management is keen to gather insights into the efficiency of ride request confirmations during both peak and non-peak hours across the various pickup points. For which you have been provided with the CSV files linked below:

CabRidersTable.csv

AeroCab_OriginAreaTable.csv


You are required to:

Click on the above link to open the CSV file.

Download the CSV file.

Perform the below task to complete this exercise.


Task 1

Complete the ETL process and load the file into PowerBI.


Task 2 

Management wants to understand the booking process efficiency. For this, management wants to know about the average time for booking process in all the areas of the city filtered by the peak and non peak period of the day.

For this please prepare a dashboard which provides the following information 



For this Dashboard, you will be required to calculate the following measures in a separate measure table: 

Total Rides

Confirmed Ride 

Confirmed Ride %

Unconfirmed Ride 

Unconfirmed Ride %

Average Cancellation Time: ACT

Average Booking Time: ABT

Average Booking Outcome Time: ABOT


Task 3

Management wants to understand the impact of outliers on the booking outcome time of the rides. They believe that if a ride booking outcome time has a Z score of more than 2 then it is an outlier otherwise it is not an outlier.  

For this,


Calculate the Z-Score Columns for identifying the outliers.

Group the Z-Score Columns into 0.20 bins and name the column  Z-Score(bin)

Categories the Z-Score(bin) column, which are more than 2 as outliers and others as “Normal”

Prepare the dashboard as provided below:


Task 4

Management wants to compare the impact of outliers on normal ride Data. For this they have asked you to prepare a dashboard (as shown below) to compare the data after filtering out the outliers.
