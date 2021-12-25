# ExcelChallenge

## Overview of Project

Create two new analysis based on outcomes for launch dates and funding goals.

### Purpose

Analyse how different campaigns fared in relation to their launch dates and their funding goals.

## Analysis and Challenges

The excel worksheet with the sheet mentioned in this is located at [GitHub Repository](https://github.com/CodyMorin25/ExcelChallenge).

### Analysis of Outcomes Based on Launch Date

In the "Theater Outcomes by Launch Date" sheet I created a pivot table based off all the data in the "Kickstarter" excel sheet. Having outcomes in the columns section, the date ended converstion in the rows, outcomes in the values, and lastly the parent category and years as filters. Then I filtered the parent category to just show theater,
then with this pivot table I created a pivot line chart in order to better see the realationship between the outcomes and launch month for theaters then I made it into a PNG file located at [GitHub Repository](https://github.com/CodyMorin25/ExcelChallenge) in the resources folder named "Theater_Outcomes_vs_Launch.png".

### Analysis of Outcomes Based on Goals

In the "Outcomes Based on Goals" sheet I created new data sets with "Goal", "Number Successful", "Number Failed", "Number Canceled", "Total Projects", "Percentage Successful", "Percentage Failed", and "Percentage Canceled" representing a different columns. Then under the Goal column I put specific values for the data to follow
like <1000, 1000-49999, 5000-9999,..., up until >50000. Then by using the COUNTIFS formula in order to calculate the next three columns specifically for the subcategory of plays. Then for the Total Projects I used the SUM formula to calulate the total number of projects that eiter were successful, failed, or canceled for each
set of specific values. Next I found the Percentages for Successful, Failed, and Canceled. Next I created a line chart with my data set located at [GitHub Repository](https://github.com/CodyMorin25/ExcelChallenge) in the resources file named "Outcomes_vs_Goals.png".

###Challenges and Difficulties Encountered

I encountered a couple difficulties in doing the analysis which included the pivot table for the theater outcomes. I had trobles in getting the years to show up so I could put it into the filters section. But after some testing I figured out that be putting the date ended converstion into the rows section more fields showed
up including years. The other challenge I came across was the line chart for the outcomes based on goals which I could get the values on the y-axis to show percentage but after messing with it a little I found that I needed to mess with the filters on the table and only have the percent values checked.

##Results

-In the "Theater Outcomes by Launch Date" June and July tended to have the most success and that the number of failures tended to stay consistent through each month.

-In the "Outcomes Based on Goals" you are more likly to succeed with your goal for a play if it is less than $1000 but having your goal <= to $4999 doesn't hurt your chances by much.

-Some limitations are that because of how big the data set is in total the accuracy of it is dependent on the data set being correct. Another is that if the dataset is what is needed or if something else is required.

-Some other tables that could make reading the data better are pie and bar charts. Pie charts especially for date including percents.