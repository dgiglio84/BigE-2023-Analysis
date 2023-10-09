# Big E 2023 Analysis


**Introduction**

The Big E is an annual New England fair that takes place in West Springfield, Massachusetts. It opens the second Friday after Labor Day and lasts for a total of seventeen days. In 2023, the Big E ran from September 15 to October 1.

**Goal**

To find factors which affected the daily attendance.

**Gathering Data**

For this analysis, data was collected from two sources:
1.	The Big E home page (https://www.thebige.com/)
2.	Weather Underground (https://www.wunderground.com/history/daily/us/ma/west-springfield/KBDL)

**Data Cleaning**

The information on the Big E home page is in an unorthodox format. For example, the website shows the calendar of events, but it is not exportable:

![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/a67e75bb-99d9-4bc5-8f9f-82dc03bbbbdc)

As a result, the text was copied and pasted in Excel, where it was heavily cleaned:

![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/1653d193-187e-43c9-b0af-0d865c847770)

![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/f5354a7c-0c3c-4629-8a27-9561e32a1382)


The Weather Underground data was not as difficult to clean:
![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/d713cfbd-a72a-427a-bba7-9c700507bdd7)

![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/11827118-aea6-40c4-a6ff-f3bd886e3e6d)

**Analysis Process**

Imported data from Excel tables into a Power BI model. Created a date table to create a relationship between all the data. Created charts and measures to analyze relationships between attendance, weather, and events.

**Analysis - General Attendance**

-	The most popular day of the week to visit the Big E is on Saturday and Sunday. The least popular day to visit is Monday.
  
![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/c5c1d325-cdf2-44d6-8767-6e1bdf95fc38)

-	In 2023, the Big E had slightly more visitors on weekdays and weekends.
  
![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/5a40acef-be48-4a00-966f-594e8795f650)

**Analysis - Weather**

-	There does not appear to be a correlation between the amount of rainfall and daily attendance. In fact, **on its most-attended day (9/30/23), West Springfield received 3.8 inches of rain**. The only day where the attendance was slightly lower due to rain was 9/25/23:
![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/2fdb053c-614b-4dcb-8500-0938943638d5)

 -	When looking at temperature, **the daily max seems to be proportional the day’s total attendance**:
![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/c5288e9f-e917-4acf-a111-9bdf092a266a)


**About Concerts**

A popular reason to attend the Big E is for concerts. There are typically two types of concerts: small concerts that take place on the center stage, and big concerts that take place in the Big E Arena. The small concerts are included in the price of a ticket, but the big concerts cost extra.


**Analysis – Big Concerts**

Without having the actual ticket sales for each concert, I can hypothesize that artists from the 1990s greatly impacted daily attendance. When sorting attendance by highest daily average, artists from this decade headlined **three of out six days**:

![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/edceef60-396c-408b-b2a2-690292034f2c)


**Missing Data**

This analysis would have been more accurate had I been able to retrieve the following data:
-	The time in which visitors arrived at the Big E.
-	The number of tickets sold for the big concerts.

For more information, please download the PBIX file included in this repository.





