# Case-Study-2, Capstone

 

author: Ivett 

date: March 10, 2022 

 

Google Data Analytics Capstone Project 

CASE STUDY: How Does a Bike-Share Navigate Speedy Success? 

 

INTRODUCTION 

This optional case study will serve as my capstone for the Google Data Analytics Certificate courses. The method applied in this case study will be the “Six Phases of Data Analysis” taught in the course. The phases are: Ask, Prepare, Process, Analyze, Share and Act. As part of my findings, I was asked to issue three recommendations for the marketing department. 

 

BACKGROUND 

I’m a junior data analyst for a fictitious company named Cyclistic, a bike-share company in Chicago, Illinois. Cyclistic’s bike-share program features more than 5,800 bicycles and 600 docking stations. Users that purchase annual memberships are known as annual members. All other users are known as casual riders. 

The director of marketing, Ms. Lily Moreno, believes that the company’s future success will be based on maximizing the number of annual memberships. This means, turning casual riders into annual members. This is also based on Cyclistic’s financial analysts stating that annual members are much more profitable than casual riders. 

 

Step 1 – Ask  

Key Business Questions 

One of the most important questions that Cyclistic’s team does not yet have an answer to is how casual riders and annual members are using their bikes? In other words, how are different customer types using their services? 

Another question that needs to be answered is: why would casual riders buy annual memberships? Thirdly, how can Cyclistic use digital media to influence casual riders to become members? 

 

 

 

 

Step 2 - Prepare  

For this analysis, I have downloaded the previous 12 months of Cyclistic bike trip data in order to analyze and identify trends. The data is available here and has been made available by Motivate International Inc., under this license. It is public data that can be used to explore how different customer types are using this bike-share’s services. I’m examining data covering the period from January 2019 through January 2020. 

The data was downloaded and safely stored to my laptop during this analysis and only I have access to it. The data is in a CSV file format. This is first-party data (reliable and original), comprehensive (no important information is missing) and cited (ROCCC). There are no issues with bias. 

Due to data-privacy issues, no personally identifiable information (PII) is in this data. The limitation for my analysis is that I won’t be able to connect past credit card purchases to determine if the casual riders live within the service area of Cyclistic. 

 

Step 3 – Process 

For data processing, I initially downloaded the data into Sheets, but the size was too large and it was very slow. However, I was able to examine a few of the files and get familiar with the data. I then used BigQuery to inspect the data. Then moved onto to do the main processing, wrangling, cleaning of the data. I also and checked the data for errors.  

The packages in RStudio that I used for the entire process of preparing, cleaning, and analysis were as follows: tidyverse, dplyr, janitor, lubridate, geosphere, ggplot2. 

The documented cleaning process is found in my Github, here.  

 

Step 4 – Analyze 

For the analysis, it’s important for me to organize the data and ensure that it was properly formatted. I aggregated the data so it was useful and accessible. In addition, I performed various calculations and descriptive analysis, including mean, max, min, and median. I also exported a summary file for further visualizations in Tableau. 

The documented analysis process if found in my Github, here. 

 

 

 

 

 

 

Step 5 – Share 

The answer to the main question of how annual members and casual riders use Cyclistic differently was found by analyzing the data. 

Casual users tend to ride for leisure, which means longer ride times. Annual members are more likely to use the bikes to commute, have shorter ride times, but rode more often. Another insight about annual members is that they were consistent in using the service throughout the year.  

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

We can see from the graphic above that for both casual riders and members, Fridays, Saturdays and Sundays are the most popular days for usage. On Fridays, casual riders tend to ride a little bit longer. A surprise for me was to see that on Mondays, casual rider numbers is high. 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

                       

Examining the usage for the past twelve months, the most popular months for riding are June, July, August, and September. This is the case for both casual riders and members. The peak month is July with 822,410 rides, and most of the riders are casual riders. Casual riders in July outnumber members by 61,702 rides. 

Going into the fall and winter months, there is a remarkable drop from October 2021 to November 2021, a difference of 271,248 distinct rides. Not surprisingly, as the months get colder, the number of rides decline, but what surprised me is to find that November had a significantly lower number of members than casual riders.  

Basically, November had 108,064 more casual rides than member rides. Perhaps there was a festival or some special event that accounts for the large number of casual riders during a very cold month. In January 2021 and February 2021, we see that the number of casual riders is less than members, jwhich is more like what would be expected since that is still the winter season in Chicago. Members are more consistent users as the climate gets colder, but also throughout the year. 

  

 

 

 

 

Step 6 – Act 

Summary and Recommendations 

There is a lot of opportunity for Cyclistic to increase membership rolls. Based on my analysis and the  information I had to work with, here are my top three recommendations (and a bonus fourth) for converting casual riders into annual members: 

    Annual Membership for Weekend Users: Since the most popular days for casual riders are on weekends, offer a special weekend only annual membership. The price of this membership would be lower than the annual membership. If the rider wants to use the services during the week, the membership won’t cover that, but they could still ride at a reduced rate than that of the casual rider price.  

    App improvements: Improve the current app by not only rewarding annual members, but casual riders. Offer a discounted membership to casual riders that sign up within a grace period. Currently, it appears that the app is only for annual members. In addition, through my research, I found a lot of complaints about the app, mainly that it is not always accurate with information about which stations have bikes available, and stations with free or full docks. 

    Phase out docked bikes: The two most popular bikes are the classic and the electric. The usage of docked bikes is very low. I suggest concentrating efforts on advertising specials for the two most popular bike types. One way could be by using stickers on the bike with a QR code that has the promoted membership special. 

    Focus on reaching families: During the busies months when kids are out of school and families are looking for things to do, there is a strong need for the company to be advertising their services and converting casual users into members, through a special discount or incentive. One group that could be pursued is families. Make an effort to incentivize families to become annual members, perhaps by increasing the advertisement for annual memberships in family friendly areas. In addition, for each adult membership include an unlimited free pass for one. Or perhaps, a child under 18 rides for 0.01 cent with an accompanying adult annual member. 

This analysis is limited, but from looking at Cyclistic’s (Divvy) website and reviews of their app, it would also be a good idea for the company to improve in other areas that may be holding them back from turning casual riders into annual members. We may need to explore how customer service and customer’s experience with the service is affecting membership numbers. 

Thank you! 
