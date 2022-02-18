 Digital Marketing Campaign & Data Analytics Strategy for “ The Fever”
 
1 Overview of Project

Louise, is a Toronto based playwright, started a crowdfunding campaign to fund her new play titled The Fever. Louise realised that  a data analysis could come in handy to determine campaign key factors in relation to launch dates, funding goals and outcomes of other campaigns. At her request, the analysis compared these key factors to other campaigns and sought out predictors for success. In addition, Louise is in need of a digital marketing campaign. Fundraising is never easy, but with a strategic and careful planning combined with  data analytics Louise has better chances of hitting her target. 

Data Analytics Strategy

Purpose

The purpose of this analysis is to visualise patterns  in the provided fundraising campaign data. These visual trends will help us understand if and how the launch date and funding goal of campaigns affected the campaign outcome. 


2.   Analysis and Challenges

Analysis of Outcomes Based on Launch Date
To determine the correlation between launch dates and campaign  outcomes we need a pivot table to display the frequency at which each campaign outcome  took place across each month of the year.  Before we do so, we need to convert the data from Unix timestamps and then use the YEAR() function to extract the year from launch dates. The following formula converted the data: =(cell/60)/60)/24)+DATE(1970;1;1). 
We then need to create a pivot table based on the data filtered by Parent Category and Years. (See the pivottable field list below)![1](https://user-images.githubusercontent.com/96391154/148706337-49659532-b51e-4c27-ac7c-11cd838dd1c1.png)

 
Our pivot table field list should exhibit successful, failed, cancelled outcomes and launch dates by month. In order to produce launch months we need to  select the years and then group them. Next, we filter the pivot table to demonstrate relevant data within the theatre subcategory.  The following step is to create a line chart to show the nexus between outcomes and launch months. (See  the pivot table below)
 ![wq](https://user-images.githubusercontent.com/96391154/148706352-77ee27c2-df10-4bd6-bea5-4dbbbcf99826.png)
![Theater Outcomes by Launch Date](https://user-images.githubusercontent.com/96391154/148706365-015186ea-2a3a-4f71-a7c3-85b96d41cf32.png)

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
 ![8888](https://user-images.githubusercontent.com/96391154/148706393-92f99cfb-aab3-4e87-9228-66d54534160c.png)


 Our target is to display play fundraising campaign outcomes based on goals. As such a line graph needs to be created. ![Outcomes Based on Goals](https://user-images.githubusercontent.com/96391154/148706399-dbfd7cd0-0ede-4cec-9a85-e10f017a7497.png)

Our line graph visualises the connection between the goal-amount ranges on the x-axis and the percentage of successful, failed or cancelled projects on the y-axis.  
Challenges and Difficulties Encountered
The most challenging part of this project is the analysis of  outcomes based on goals. To  make the labels reflect the goal ranges can pose a problem. Hopefully we can  rely on the excel community of professionals who are always eager to help. 


 Digital Marketing Campaign 
    
 Purpose
    
 The purpose of this report is to determine a digital marketing campaign for “The Fever” using SEO and PPC techniques. Before I begin I need to set a realistic budget for a 30-day campaign (see Launch Date & Deadline ).  
    
    •	Marketing campaign budget
![image](https://user-images.githubusercontent.com/96391154/154591415-c9abe22c-5d75-4721-b13e-26c5360c36e1.png)



3. Digital Marketing Campaign


•	Set Realistic Funding Goal for The Fever Kickstarter Campaign
As the data analysis shows above, campaigns with goals less than $5000 had the highest incidence of success.  It is advisable to follow the guidance of the analysis.

•	Launch Date & Deadline
The data analysis shows that the best period to launch a campaign is in May. Granted Louise approves the launch date, the deadline should be short. In fact the shorter, the campaign the higher rate it is going to have on Kickstarter. Creating a sense of urgency is an effective way to grab the attention of potential supporters as early as possible. Hence, a 30-day campaign,  launching in May is my recommendation.

•	Press Release Video
After the launch date is set, a press release video needs to be released to announce the upcoming campaign –“The Fever”.  Filming a video in the  Elgin Theatre where the play  launches will give legitimacy to the campaign.  The video should be posted on Instagram(see Social Media) and  landing page.

•	Buyer Personas
Creating buyer personas is an essential step in understanding a target audience for the campaign. The first step to creating buyer personas is to do in-depth market research and analysis. I decided to conduct personal interviews as a primary research method. My one-on-one interviews with 3 Canadians from different backgrounds helped me connect with a potential market.  As such, the buyer personas were created based on information like demographics, online behaviour, interests, languages, goals, frustrations etc. 


![1](https://user-images.githubusercontent.com/96391154/154591794-ebeee172-d4f8-41eb-9d01-fc9cb189af75.png)![2](https://user-images.githubusercontent.com/96391154/154591809-96aa5ae7-b3a9-42c5-9f74-519c7879cea9.png)



•	Landing Page & Blog
A self-hosted WordPress website – thefeverplay.com is an excellent opportunity for Louise to display the campaign’s progress. In addition,  WordPress plugins such Qards, Beaver Builder or WP Landing help will help set the page up. In addition, when creating a website, incorporating UX, UI best practices should make a priority. For instance, A/B testing  is one of the helpful methods of designing a successful landing page. The website is, indeed,  a great host for content. A blog, to be precise, will reassure potential backers of the campaign’s legitimacy.  Using an email marketing tool such Hubspot or MailChimp  will keep the backers updated about latest news.  
Thefeverplay.com

![landing page The Fever](https://user-images.githubusercontent.com/96391154/154591890-ed71c0a3-97b8-4b13-b90b-cdb2ee5807e7.png)



•	Rewards
Potential backers donate to a crowdfunding campaign because they want to feel like they are an integral part of the project. Low-cost items such as T-shirts or stickers with a handwritten thank you note will help promoting the campaign. Adding an invite to attend the exclusive launch event  will help building trust in the success of the campaign.


•	SEO & PPC
Starting the SEO & PPC campaign on Instagram is best   with the Facebook ads manager.  It is so as it has more scope for customization than creating ads in the  Instagram app per se.  Identifying valuable keywords to optimise the campaign page should be the focus of the SEO marketing strategy.  In fact the play launches at the Elgin Theatre, which combined with the play title gives new keyword phrases.  Facebook ads manager  is a great tool to assess the value of the keyword phrases and bid on them.  The manager gives us an option to choose the objectives. Choosing the objective – Sending people to your website will direct the visitors directly to thefeverplay.com. Before setting the bidding, budget needs to be set. I recommend choosing a daily budget  and the ad will run for the duration of the campaign (30 days).  Setting a start and end date will schedule the ads appropriately. 


![Set daily budget](https://user-images.githubusercontent.com/96391154/154591986-f1d53189-c2a7-4074-ac1f-e1b9c64cb708.png)


Targeting the desired audience is one of the main strength of PPC advertising on Instagram. I recommend using buyer personas I have created (see buyer personas). The final step when setting up the Facebook ads campaign is creating the ad itself. Single image and single video are the best choices. 


•	Social Media
For the Fever campaign to be victorious, it is paramount to be a part of online communities.  I advise to focus exclusively on the Instagram account.  Setting a goal for the Instagram marketing strategy will help visualise expectations and  outcomes.  The first goal is to get 1,000 organic, engaged followers in 30 days(campaign duration). For this to happen, certain  tactics (see below) should be applied. Next step is assessing similar fundraising campaigns on Instagram.   By doing so, the campaign will connect directly with the 3  buyer personas which will generate  Instagram followers. 
Creating a content calendar for the duration of the campaign will help be regular on the platform. Hashtags should be selected for  the campaign and content promotion.  Spending some time searching for the playwright, scriptwriter, Elgin Theatre or kickstarter hashtags, for instance, should highlight potential followers. By following them, there’s an opportunity to establish a community of people who think like Louise. Indeed, by doing so she will be able to build trust in her campaign and generate followers.



![Instagram 30 day content calendar](https://user-images.githubusercontent.com/96391154/154592049-90b0d459-33b8-43ca-b753-b428e087a84d.png)


 
    
    



 4   Results
 
 Data Analytics Strategy
 
What are two conclusions that we can draw about the Theater Outcomes by Launch Date?
The first conclusion we can draw from the "Outcomes Based on Launch Date" line graph is there are more campaigns launched overall in May, June, July. The second conclusion we can draw is campaigns launched in May had a higher incidence of success. Louise should launch future campaigns in May.

What can you conclude about the Outcomes based on Goals?
From the "Outcomes Based on Goals" chart, we can conclude that campaigns with lower goals are more successful. Campaigns with goals less than $5000 had the highest incidence of success.

What are some limitations of this dataset?
The main limitation is the lack of  information about the backers, the people who are  donating the money. 

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


Digital Marketing Campaign 


 What are three conclusions that can we can draw about the Instagram marketing campaign? 
The first conclusion is that the success of the campaign depends on the content.  The second conclusion is that deliberately choosing a certain social media platform gives us better chances of successfully targeting buyer personas. The conclusion is that being proactive and persistent on Instagram yield good results 

What are some limitation of the Instagram marketing campaign?
Instagram doesn’t offer much room for additional content. In addition,  we cannot reach men and women equally on Instagram. In fact, about 32% of the active monthly users on this social media platform are men.



