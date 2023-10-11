# The Big E 2023 - Attendance Analysis


**Introduction**

The Big E is an annual New England fair that takes place in West Springfield, Massachusetts. It opens the second Friday after Labor Day and lasts for a total of seventeen days. In 2023, the Big E ran from September 15 to October 1.

**Goal**

To analyze factors, such as weather and events, which affected the daily attendance.

**Gathering Data**

For this analysis, data was collected from two sources:
1.	The Big E home page (https://www.thebige.com/)
2.	Weather Underground (https://www.wunderground.com/history/daily/us/ma/west-springfield/KBDL)

**Data Cleaning**

The information on the Big E home page is in an unorthodox format. For example, the website shows the calendar of events, but it is not exportable:

![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/a67e75bb-99d9-4bc5-8f9f-82dc03bbbbdc)

As a result, the text was copied and pasted in Excel, where it was heavily cleaned:

![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/2f72f8d9-16b5-412a-a935-7f225e96eb15)         ![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/f5354a7c-0c3c-4629-8a27-9561e32a1382)


The Weather Underground data was not as difficult to clean:
![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/d713cfbd-a72a-427a-bba7-9c700507bdd7)

![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/11827118-aea6-40c4-a6ff-f3bd886e3e6d)

**Analysis Steps**

- Imported data from Excel tables into a Power BI model. 
- Created a date table to create a relationship between all the data.
- Created charts and measures to analyze relationships between attendance, weather, and events.

**Analysis - General Attendance**

-	The most popular day of the week to visit the Big E is on Saturday and Sunday. The least popular day to visit is Monday.
  
![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/c5c1d325-cdf2-44d6-8767-6e1bdf95fc38)

-	Conversely, there were slightly more visitors during the weekdays than on weekends.
  
![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/5a40acef-be48-4a00-966f-594e8795f650)

**Analysis - Weather**

-	There does not appear to be a correlation between the amount of rainfall and daily attendance. In fact, **on its most-attended day (9/30/23), West Springfield received 3.8 inches of rain**. The only day in which the attendance was lower due to rain was 9/25/23:

![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/a61c3afe-99e5-4bb0-8ae2-43d23a47dc66)


 -	However, when looking at the temperature data, **the daily max seems to be proportional the day’s total attendance**:

![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/ac7e1e2e-27d3-46c6-9a7f-f34955aa2a2f)




**About Concerts**

At the Big E, there are typically two types of concerts: small concerts that take place on the center stage, and big concerts that take place in the Big E Arena. The small concerts are included in the price of a ticket, but the big concerts require the purchase of an additional concert ticket.

**Analysis - Small Concerts**

Although it is impossible to gauge how many people attended each concert, based on attendance The Edge Effect had the highest probability of being attended. The table below shows an aggregate of the attendance for each they were at the event.

![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/07a11c58-eda0-4819-9ec6-0b9f94ec95d6)


**Analysis – Big Concerts**

Without having the actual ticket sales for each concert, I can hypothesize that artists from the 1990s greatly impacted daily attendance. When sorting attendance by highest daily average, artists from this decade headlined **three of out six days**:

![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/edceef60-396c-408b-b2a2-690292034f2c)


**Conclusion**

Based on this analysis, the weather did not seem to play a significant role in the overall attendance. However, it can be argued that headlining acts drew more crowds towards the end of the fair’s season.

This analysis may have been more accurate had I been able to retrieve the following data:
-	The time in which visitors arrived at the Big E.
-	The number of tickets sold for the big concerts.

For more information, please download the PBIX file included in this repository.





