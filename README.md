# Kickstarting with Excel

## Overview of Project

The scope of this project is to help a playwrite named Louise with a play she would like to launch called FEVER. I have grabbed data from kickstarter campaigns and analyzed it to show overall trends in campaign financing.

### Purpose

The purpose of this analysis is to find the best methods to campaign for the play.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

 - In the chart "Theater Outcomes Based on Launch Date", I found that the most successful plays luanched during between April and September with a peak in May. A challenge that arose was getting the month from the dates in a seperate column. This was fixed by the function "=TEXT(S2,"mmm")" ![Month Function Screenshot](file:///C:/Users/ejche/Documents/GitHub/kickstarter-analysis/Module%201%20Challenge/Resources/Month%20Function%20Screenshot.PNG). The text function grabs text from a cell, the S2 is the cells that the information is from, and "mmm" gets the month data and converts it into a shorthand in three letters, i.e. Jan, Feb, ... so on and so forth.

### Analysis of Outcomes Based on Goals

 - In the chart "Outcomes Based on Goals", I found that the most successful campaign goals were in the range of $0 to $15,000 and $30,000 to $45,000. The overall trend shows that the larger the goal, the less likely the show will be successful at financing itself. A challenge that arose with this analysis was the functions calling on other sheets and making sure the cells were correct. When calling the "Kickstarter" sheet, I employed the use of "$" around the column letters so that the correct data was highlighted. ![Worksheet Screenshot](file:///C:/Users/ejche/Documents/GitHub/kickstarter-analysis/Module%201%20Challenge/Resources/Worksheet%20Screenshot.PNG)

### Challenges and Difficulties Encountered

## Results

Of the Theater campaigns, the best launch date is in May, or the summer. Additionally, failed campaigns have the same a similair trend to successful ones, meaning that winter months are worse off for launch dates.

Overall, the larger campaigns are harder to finance.The smaller projects are easier to finance but the sweet spot is between $30,000 to $45,000.

The dataset is limited in that it is not sampling the population of campaigns. In the dataset, I looked at theater campaigns in certain countries. With each constraint, the sample size gets significantly smaller. 

- What are some other possible tables and/or graphs that we could create?
 Other metrics could include length of campaigns based on outcomes, goals vs pledged outcomes, and outcome based on average donation size.
