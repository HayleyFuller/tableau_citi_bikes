# New York Citi Bike Data Analysis

## Challenge 18 overview

Using data from the Citi Bike Data files, create a Tableau dashboard to interpret the data and provide insights.

Dashboard link - Link to Tableau Dashboard https://public.tableau.com/app/profile/hayley.fuller/viz/NewYorkCitiBikeDataDashboard/Tripusers#2

## Data Cleaning
All data sets from Citi Bike Data are CSV files separated into individual months and downloaded 4 months of data, from February 2023 to May 2023.
These data sets provide useful information but in order to analyse the data as a whole, they needed to be joined together. By using Python in Jupyter notebook I coded the individual CSV files into a combined data set.
This combined CSV file was then uploaded into Tableau public to create a dashboard for analysis.

## Dashboard Analysis

**Trip users**

This page shows an overview of trips that people took. The total number of trips in the 4-month period is 290, 975. Of these trips we can see the following…

•	72, 940 were trips completed by casual members compared with 218, 035 trips by members. These means that a majority of trips, 74.93% were completed by members.
•	Of the overall trips 78.46% used classic bikes.
•	These results vary between months, but the majority is always with members and classic bikes used.

![plot](Images/Biketype.png)

**Monthly overview**

This page shows a monthly overview of trips completed. The total number of trips in the 4-month period is 290, 975. Of these trips we can see the following…

•	May was the month that most trips were taken. This is a steady increase from February. This could indicate that the trips would continue to rise as the warmer months begin.
•	Interestingly the day in which saw the greater number of trips is Wednesday. This could indicate a pattern in people’s habits as the week progresses. 
•	More interestingly Saturday is the day which saw the lowest usage of trips at only 34, 411 compared to Wednesday at 47, 161.

INSERT IMAGE

**Daily overview**

This page shows a daily overview of trips completed. The total number of trips in the 4-month period is 290, 975. Of these trips we can see the following…

•	Following on from above, we can see that Saturday and Sunday provide the lowest number of trips. 
•	What we can see from the trips taken on weekdays is that they all follow a pattern of when during the day are its peak hours. On all these weekdays the peak hours are 08:00 and 18:00. This could suggest people are using them on their commute to and from work.

**City points overview**

This page shows an overview of starting points and end points of trips completed. The total number of trips in the 4-month period is 290, 975. Of these trips we can see the following…

•	A large cluster of starting points are outside of the main city of New York Manhattan, with the end points in the city of New York Manhattan. This could further indicate that the Citi Bikes are being used by commuters.
•	The above is consistent across all 4 months.

**City points top 10.**

This page shows an overview of the top 10 starting points and end points of trips completed. The total number of trips in the 4-month period is 290, 975. Of these trips we can see the following…

•	This page follows on from the above and further shows that out of the top 10, the starting stations are outside of the city of New York Manhattan.
•	The top starting station is Grove St Path taking 16.88% of the over all trip count. This is consistent within each month. 

**Conclusion**

The above analysis suggests there is a regular pattern of behaviour made by users on these trips. They are consistently using classic bikes from and to specific stations and throughout peak hours of the working week. As the usage drops during Saturday and Sunday this suggests that users are in fact using Citi Bikes for their commute to work.
