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

![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/0cfee6c9-1d7d-4c7b-90d7-686c0f0220a4)

As a result, the text was copied and pasted in Excel, where it was heavily cleaned:

![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/e33ad202-d2d7-4475-8453-9bfa248b4f37)

![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/2a235968-2c30-4194-a9f3-1e9ffcc3fa1f)

The Weather Underground data was not as difficult to clean:
![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/86711120-6080-4486-8789-a4302af7c6c1)

![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/5f48a3f1-c4aa-4825-a5b0-a854f0ca27d2)

**Analysis Process**

Imported data from Excel tables into a Power BI model. Created a date table to create a relationship between all the data. Created charts and measures to analyze relationships between attendance, weather, and events.

**General attendance observations**

-	The most popular day of the week to visit the Big E is on Saturday and Sunday. The least popular day to visit is Monday.
![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/8486ec92-196d-45d4-a54a-40c283129d52)

-	In 2023, the Big E had slightly more visitors on weekdays and weekends.
![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/e8846527-abfb-4c90-aa1c-5c7c1dffb174)

**Analysis - Weather**

-	There does not appear to be a correlation between the amount of rainfall and daily attendance. In fact, on its most-attended day (9/30/23), West Springfield received 3.8 inches of rain. The only day where the attendance was slightly lower due to rain was 9/25/23:
![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/653765cf-ea8a-4a28-98ab-65337d06d75e)

 -	When looking at temperature, the daily max seems to be proportional the day’s total attendance:
![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/f1e2f6e9-b1e0-4b88-8d3d-bfccb347a897)

**About Concerts**

A popular reason to attend the Big E is for concerts. There are typically two types of concerts: small concerts that take place on the center stage, and big concerts that take place in the Big E Arena. The small concerts are included in the price of a ticket, but the big concerts cost extra.

**Analysis - Small Concerts**

Although it is impossible to gauge how many people attended each concert, based on the attendance The Edge Effect had the highest probability of being seen. The table below shows an aggregate of the attendance for each they were at the event.
![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/ace555e6-f663-403a-a85b-345577e2b1a3)

**Analysis – Big Concerts**

Without having the actual ticket sales for each concert, I can hypothesize that artists from the 1990s greatly impacted daily attendance. When sorting attendance by highest daily average, artists from this decade headlined three of out the six days:
![image](https://github.com/dgiglio84/BigE-2023-Analysis/assets/120340086/e60511b6-d6b3-4fdb-aa22-3d55cd5bde75)

**Missing Data**

This analysis would have been more accurate had I been able to retrieve the following data:
-	The time in which visitors arrived at the Big E.
-	The number of tickets sold for the big concerts.

For more information, please download the PBIX file included in this repository.





