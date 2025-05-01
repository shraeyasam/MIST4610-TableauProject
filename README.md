# MIST4610-TableauProject

## Team Name

71552 Group 4

## Team Members

Ashleigh Myers [@ashleigh-myers](https://github.com/ashleigh-myers)

Daniel Ding [@dd68158](https://github.com/dd68158)

Shraeyas Muthaiah [@shraeyasam](https://github.com/shraeyasam)

Palak Kaur [@palakxkaur](https://github.com/palakxkaur)

Zoe Jordan [@Zoejordan012](https://github.com/Zoejordan012)

## Scenario
A politician in DC is concerned about crime and what she can do to best serve her constituents. She is concerned about where and what time of day different crimes are occurring. She is working on policies dealing with crime prevention and budgets. 


## Dataset Description
Our dataset, Crime Incidents in 2024, contains data reported by the District of Columbia Metropolitan Police Department about crimes occurring within their jurisdiction throughout 2024. The data contains the physical locations where the crimes were committed, crime types, date of the crime, time of day the crime happened, crime weapon, and various other attributes of the crimes that occurred. The coordinates, block, and specific geolocations of the crimes are automatically assigned using a geographic information system used by the District of Columbia government called the Master Address Repository (MAR). In total, the dimensions of the dataset are 29,287 rows by 25 columns, and some of the most relevant columns, including those we used in our visualizations and analysis, include shift, method, offense, voting precinct, start date, end date, block, and object ID. The data types present in the dataset are datetime, variable character, integer, and decimal.

## Question 1
How do crime types vary by shift time?

![Visualization1](https://github.com/shraeyasam/MIST4610-TableauProject/blob/ffc2eb9d22431ba494b320a81588899339a86728/group_1.jpg)

### Importance
This question is useful for the general public, law enforcement officers, as well as policymakers. The answers to this question allows for the education of the public on the most prevalent crimes, when they occur, and measures they can take to prevent crimes. In addition, law enforcement staffing and law enforcement patrol patterns may be evaluated for effectiveness or areas of potential change and improvement. Policymakers can use this question to develop crime prevention policies for societal safety and economic development. 


## Question 2
How do the amount of crimes and type of offense vary by voting precinct? (focusing on precinct 1-10)

![Visualization2](https://github.com/shraeyasam/MIST4610-TableauProject/blob/09159370aed14a84cfb11b39627d889e83d04a01/group_2.jpg)

### Importance
This question is important for the general civilian public, law enforcement, and policymakers. For normal citizens, it can help them decide where to live or places to avoid when moving or purchasing a new home, depending on crime rates. It helps law enforcement officers decide on force distribution and patrolling methods. Through answering this question, trends can be exposed in implications of policies, demographics, and poverty levels, showing policymakers potential social and economic issues that need to be solved.

## Manipulations Applied

### Visualization 1
Arson, Burglary, Homicide, Sex Abuse, Robbery, Theft F/Auto were excluded through filtering, since there were no significant changes in these offenses. Only Assault with Dangerous Weapon, Robbery, Motor Vehicle Theft, and Theft/Other showed significant trends.

### Visualization 2
Arson and Homicide were excluded through a filter in the Offense category. This is because they had little to no value. If they were included in the heatmap, there would be many “blank” boxes due to such a small amount of arson and homicide being committed or present in the dataset, and no significant trends or messages would be evident.

## Analysis and Results

### Question 1

Results

Theft is the most prevalent type of crime, with motor vehicle theft and other forms of theft occurring significantly more often than crimes like burglary or assault with a deadly weapon. Interestingly, despite the common perception that being out at night is more dangerous, crime rates are actually lower during the midnight shift compared to the day and evening shifts. In fact, day and evening shifts tend to experience similar levels of crime activity, challenging assumptions about when individuals are most at risk. In addition, burglary and assault with deadly weapons occur significantly less than motor vehicle theft and other theft crimes

Analysis: How is this useful?

Understanding time-specific crime trends can help law enforcement and city planners allocate resources more effectively. With higher crime rates during the day and evening shifts, more officers can be assigned to patrol during these times, particularly in areas prone to theft such as parking lots and residential neighborhoods. Targeted training for officers on theft prevention, along with incentives to encourage coverage during peak crime hours, can further enhance safety. Additionally, this data can guide policymakers in deciding how to allocate funds—whether through public education on theft prevention, supporting law enforcement efforts, or enforcing harsher penalties for theft-related crimes.


### Question 2

Results

The heatmap illustrates the frequency of various types of offenses across voting precincts 1 through 10 in Washington, DC, with offense types represented by rows and precincts by columns. It reveals that precincts 1, 2, 4, 5, and 6 experience significantly higher total crime rates across all categories, with theft standing out as the most commonly committed offense. This pattern highlights a clear need for targeted and enhanced efforts to address theft, especially in the precincts with the highest overall crime rates.

Analysis: How is this useful?

The data suggests a need for increased law enforcement presence and improved surveillance technology in precincts with higher crime rates, particularly precincts 1, 2, 4, 5, and 6. One possible strategy could involve reallocating executive forces from lower-crime precincts such as 3 and 7–10 to the areas with greater need. Additionally, addressing underlying social issues like poverty and homelessness could help reduce theft and other related crimes. Policy adjustments, including stricter penalties for theft like longer jail sentences and heavier fines, may also serve as deterrents. At the community level, educational programs can raise awareness about theft and encourage proactive measures for personal safety. Moreover, evaluating and improving infrastructure related to crime reporting—such as emergency call response times and reporting system reliability—is crucial. Finally, investing in environmental design solutions like better street and parking lot lighting can help prevent theft by increasing visibility and perceived safety.

## Tableau Packaged Workbook

[Page to Download Tableau Workbook](paste your link here)


