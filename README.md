# Kickstarting with Excel

## Overview of Project

### Purpose
Louise's play *Fever* almost reached its fundraising goal within a short time period, but ultimately missed its goal amount by $400. She is now interested in seeing the outcomes of other campaigns based on two main variables. The kickstarter analysis was conducted to provide Louise with a view of other campaign's outcomes in relation to their launch dates and their funding goals.  The three main outcomes within the analysis are successful, failed and canceled. The first part of the analysis regarding the variable launch date, provides a sum and visualization by month for campaign outcomes within the theater parent category. The second part of the analysis takes a look at outcomes of campaigns within the plays subcategory  and their fundraising goals. The fundraising goals are detailed as 12 groups ranging from less than 1000 to greater than 50000. The sum of outcomes are provided as well as percentages of each outcome based on the total number of projects. A line graph was used as the visualization showing the percentage of each outcome and their fundraising goals. 
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Prior to the module challenge there was additional work put into the worksheet. This additional work allowed us to create the date created column into a more readable format. This feature was the main factor for this analysis. The goal was to get the sum of successful, failed, and canceled campaigns individually and have the sums displayed by the month that they launched. In order to do this I created a pivot table by selecting all of the data and inserting a pivot table into a separate sheet. The goal is view all theater campaign outcomes by month so the first step was to use parent category and years as the filters. The table was then filtered so that it is only showing campaigns from the theater parent category.  In order to view the outcomes by the month they launched the date created conversion attribute is placed into the pivot table as a row. The values that need to be displayed relates to the outcomes so the next step was to place the outcomes in the values and columns, placing the outcomes in the columns allows us to have the desired column headers. Three out of the four outcomes are requested, so I filtered on the column labels to display only the requested. For visualization purposes a line chart with markers was created.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/87450415/133506926-66a1bf0c-2cd2-4890-9afc-95547c51e215.PNG)

The line graph displays a visualization of the number of successful, failed, and canceled theater campaigns and the month to which they correlate. The values are displayed on the y axis and the months are displayed on the x axis. I did not have any challenges while completing the excercise, however one challenge that I could see occuring would be placing the correct fields in the appropriate places and making sure they have the correct format. For example the date created conversion does not just provide the month, however we only want the month to be displayed within the pivot table and graph. This could be a challenge for someone who is unfamiliar with how to format fields within a pivot table. 
### Analysis of Outcomes Based on Goals
In order to prepare the correct analysis for the outcomes based on fundraising goals we first needed to format a separate sheet that will hold the data. The goal of this analysis was the see the number of successful, failed, and canceled play campaigns grouped by their fundraising goals. Also, we needed to find the percentage of each compared to the total amount of projects. Column headers were placed in row 1 and the groupings of goals were placed in column A. There were 12 grouping ranging from less than 1000 up to greater than 50000. In order to populate the correct values in the sheet a countifs equation was used. The equation allows us to filter on the information we are looking for. The first part of the equation is to filter on the fundraising goal amounts to ensure we are collecting the correct values for the grouping. The next two parts of the equation are to filter on the desired outcome as well as the plays subcategory. After all of the countifs equations were completed the sum of all 3 outcomes was displayed in a separate column for each goal grouping. Three additional columns were used to obtain the percentage of each outcome relating to the total number of projects. This is done by dividing either the number of successful, failed or canceled projects by the total number of projects. Then a line graph was created using the goals as the values on the x axis and percentages on the y axis.
 
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/87450415/133506992-a1d26dd8-81c6-450b-b331-f8c32523fa9f.png)

The line graph contains separate lines for each outcome and displays a visual of how the percentages vary as the fundraising goal amounts increase. The main difficulty I had with this data was using the countifs equation correctly. This is an equation I have not worked with much in the past and getting the formula to take info from the specified goal ranges was the biggest difficulty I encountered. 
### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The first conclusion I notice from the data is that May through August is peak time of the year for theater campaigns to launch. These months posted the top 4 total campaign amount throughout the year with 166, 153, 138, and 123 respectively. May and June also produced the highest percentage of succesful campaigns at 67% and 65%, which could indicate them as being the prime months to launch theater campaigns. 
- What can you conclude about the Outcomes based on Goals?
The large majority of play campaigns have fundraising goals below $5,000. Collectively there were 1,043 total projects and 720 were below the threshold of $5,000. Fundraising goals under $5,000 also offer the highest probability of success. The percentage of success for these projects was roughly 60% while all projects with fundraising goals above $5,000 posted a success rate of 51%.
- What are some limitations of this dataset?
One of the main limitations that I notice is that the two veriables are being looked at differently. Theater outcomes based on launch date filters the findings by the parents category while outcomes based on goals specifies the filter even more by using the subcategory of plays. I believe taking a look at both launch date and fundraising goals through the same filters will allow for a more accurate portrayal of the data. Another limitation is that there could be numerous external factors that are not accounted for when looking at the outcomes of these campaigns. One of the main factors not accounted for in the quality and quantity of effort put towards the fundraising process.
- What are some other possible tables and/or graphs that we could create?
An additional type of graph that could have been used for theater outcomes by launch date would be a clustered column chart. This would allow the data to be represented in a neat and easy to read format with the months on the x axis and number of projects on the y axis. The three columns per month will provide separation to differentiate between the different types of outcomes as well. A clustered column chart could also be used for the Outcomes based on goals for the same purpose. Pie charts are generally good for displaying data that includes percentages, but in order to capture all the goal groupings there would need to be a separate chart for each goal in order to maitain a neat and readable format. 
