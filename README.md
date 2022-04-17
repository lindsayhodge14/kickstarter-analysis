# Kickstarting with Excel

## Overview of Project

### The purpose of this project is to help Louise determine the ideal goal and launch date for her kickstarter campaign that will fund her upcoming play. 

## Analysis and Challenges

My analysis drew upon existing data, which details various kickstarter campaigns. To most accurately inform Louise, I narrowed the analysis to funding campaigns similar to hers: conducted in the US, categorized as theater, and subcategorized as plays. After filtering the data to reflect these circumstances, I then totaled the number of successful, failed, and canceled funding campaigns based on their launch date and their goal amount (goal amounts were totaled up using a range which increased in increments of 5,000). The results are depicted in the Analysis of Outcomes Based on Launch Date and Analysis of Outcomes Based on Goals. I did not facing many challenges during this process other than the monotony of inputing the COUNTIF formula specifications. I attempted to lock certain elements, but still had to manually input at least one criteria per cell. 

### Analysis of Outcomes Based on Launch Date

![Theater_Outcomes_vs_Launch](NewVolume/DataAnalyticsBootcamp/resources/Theater_Outcomes_vs_Launch.png)

The outcomes based on launch date chart illustrates a relatively similar trend, as it pertains to the likelihood of a kickstarter campaign succeeding versus failing, from the months of January to April and August to November. In October, the two outcomes do begin to converge meaning that the odds of succeeding versus failing have lowered. The odds of succeeding versus failing are nearly equal in December, when successful and failed campaigns converge. The data shows that campaigns launched in May through July have the best possibility of succeeding.

### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](NewVolume/DataAnalyticsBootcamp/resources/Outcomes_vs_Goals.png)

The outcomes based on the goals chart illustrates that their are particular ranges that have a greater chance of succeeding as opposed to failure. These are the goal ranges that Louise should be considering for her own kickstarter. The odds of success are greatest for goals within the ranges of 1000 to 4999, 10000 to 14999, and 35000 to 39999. The odds of success and failure are equal for goals in the 15000 to 19999 and 20000 to 24999 ranges. Failure is more prominent amongst campaigns whose goal is in the ranges of 25000 to 29999 and greater than 45000. 

### Challenges and Difficulties Encountered

I did not encounter any challenges. However, I believe it would have been easier to incorporate the ranges for the goals into my COUNTIFS formula if I had designated the minimum and maximum their own cells. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

I conclude that December is the worst month to launch in; and, May is the best month to launch in as its followed by June and July which also show trends of yilding more successful campaigns than failed. 

- What can you conclude about the Outcomes based on Goals?

From the data, I would conclude that someone with anticipating a high budget should set their kickstarter goal between 35000 to 39999, as this range has the highest chance of facilitating a successful campaign. If someone is anticipating a lower budget, I conclude that they would be most likely to recieve funding by setting a campaign goal of 1000 to 4999. I would also conclude that campaign seeking over 45000 have little to no chance of succeeding. 

- What are some limitations of this dataset?

The illustrations I have provided are US centric and limited to plays. Additionally, I did not consider the length of the campaign. If a campaign was conducted over multiple years, I forsee that impacting its ability to succeed or propensity to fail. 

- What are some other possible tables and/or graphs that we could create?

Based on the limitations I identified previously, I would create another table or graph to display the affect of the campaigns length on its outcome. 
