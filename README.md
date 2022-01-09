Challenge Kickstarter Analysis with Excel
1 Overview of Project
Louise, an up and coming playwright, started a crowdfunding campaign to fund her new play titled Fever. Louise realised that  a data analysis could come in handy to determine campaign key factors in relation to launch dates, funding goals and outcomes of other campaigns. At her request, the analysis compared these key factors to other campaigns and sought out predictors for success. Fortunately her campaign was victorious, and the fundraising goal was met. 

Purpose
The purpose of this analysis is to visualise patterns  in the provided fundraising campaign data. These visual trends will help us understand if and how the launch date and funding goal of campaigns affected the campaign outcome. 
2.   Analysis and Challenges
Analysis of Outcomes Based on Launch Date
To determine the correlation between launch dates and campaign  outcomes we need a pivot table to display the frequency at which each campaign outcome  took place across each month of the year.  Before we do so, we need to convert the data from Unix timestamps and then use the YEAR() function to extract the year from launch dates. The following formula converted the data: =(cell/60)/60)/24)+DATE(1970;1;1). 
We then need to create a pivot table based on the data filtered by Parent Category and Years. (See the pivottable field list below)
 
Our pivot table field list should exhibit successful, failed, cancelled outcomes and launch dates by month. In order to produce launch months we need to  select the years and then group them. Next, we filter the pivot table to demonstrate relevant data within the theatre subcategory.  The following step is to create a line chart to show the nexus between outcomes and launch months. (See  the pivot table below)
 
 Analysis of Outcomes Based on Goals
In order analyse the outcomes based on goals  and visualize the percentage of: successful, failed, cancelled plays based on the funding goal amount, we need to generate a new worksheet populating it with the  following columns: 
-Goal
- Number Successful
- Number Failed
- Number Cancelled
- Total Projects
- Percentage Successful
- Percentage Failed
- Percentage Canceled
The goals need to be grouped in categories of less than $1,000, more than $50,000 and increments of $5,000 for all goals in between. By using the COUNTFITS() function we now can populate the "Number Successful", "Number Failed", "Number Canceled" columns.  .  We then need to apply the following formula to calculate the results:
=COUNTIFS(Kickstarter!$D:$D;"<1000";Kickstarter!$R:$R;"plays";Kickstarter!$F:$F; "successful")

We can get the total number of projects goal range by using the SUM() function. 
The following table shows the result of the calculations:
 

 Our target is to display play fundraising campaign outcomes based on goals. As such a line graph needs to be created. 
Our line graph visualises the connection between the goal-amount ranges on the x-axis and the percentage of successful, failed or cancelled projects on the y-axis.  
Challenges and Difficulties Encountered
The most challenging part of this project is the analysis of  outcomes based on goals. To  make the labels reflect the goal ranges can pose a problem. Hopefully we can  rely on the excel community of professionals who are always eager to help. 
 3.   Results
What are two conclusions you can draw about the Theater Outcomes by Launch Date?
The first conclusion we can draw from the "Outcomes Based on Launch Date" line graph is there are more campaigns launched overall in May, June, July. The second conclusion we can draw is campaigns launched in May had a higher incidence of success. Louise should launch future campaigns in May.

What can you conclude about the Outcomes based on Goals?
From the "Outcomes Based on Goals" chart, we can conclude that campaigns with lower goals are more successful. Campaigns with goals less than $5000 had the highest incidence of success.

What are some limitations of this dataset?
The main limitation is the lack of  information about the backers, the people who are  donating the money. Having the demographic information can help Louise create a persona-based segmentation marketing strategy for future fundraising endeavours.  
What are some other possible tables and/or graphs that we could create?
Column Chart
Bar Graph
Line Graph
Dual Axis Chart
Area Chart
Stacked Bar Graph
Mekko Chart
Pie Chart
Scatter Plot Chart
Bubble Chart
Waterfall Chart
Funnel Chart
Bullet Chart
Heat Map


