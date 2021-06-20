# Kickstarting with Excel

## Overview of Project
Leveraged data analytic & Microsoft Excel skills to analyze crowdfunded data and deliver a concise & precise insight to reach Louise's fundraising goal.

### Purpose 
Is to identify if there are specific trends/factors for successfully fundraising a playwright. To use the aforementioned in planning a campaign for Louise so that she can achieive her goal.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/84733540/122655773-187f7980-d123-11eb-9aef-68f686395bac.png)
The objectice of this analysis is to identify if certain months of the year were more advantageous for fundraising than others. In this analysis our data population consisted of 1,369 international data points of outcomes for only theater based campaigns over a nine year span. Louise did not specify where her fundraising would take place so the data population is inclusive of all surveyed geographic areas, this is in order to reflect a comprehensive picture of the surveyed locations on an aggregate level.
### Analysis of Outcomes Based on Goals
Outcomes_vs_Goals.png![Outcomes_vs_Goals](https://user-images.githubusercontent.com/84733540/122655822-93489480-d123-11eb-8e83-de0766b7fe05.png)
The objective of this analysis was to visualize the success, failed and canceled rates vs. fundraising goal amounts as they increase. In this analysis our data population consisted of 1,047 international data points specific to only plays and their aforementioned rates. 

### Challenges and Difficulties Encountered
During this analysis there were multiple challenges but two stood out amongst the rest: data formatting and outliers in my dataset.  The first challenge was data formatting, while I was familiarizing myself with the dataset I noticed that the 'Deadline" and 'Launched' cells were formatted in Unix Timestamp, which has to be manually converted so that Excel can process and format it as a date. I quickly researched how to solve this issue and implemented a formula in columns S & T to display the readable dates.  The second challenge was much more subjective than the first. My data's outliers were based on the "goals" and "pledged" categories' values. I used the Interquartile Rule Test in order to identify them, along with a standard "eye test". I did not collect the data myself, so I can not properly identify "typo" data points, so I kept all of the data as is and did not remove any in order to keep the picture whole.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
First conclusion drawn from this analysis is that the month that contains the most successful campaigns is May. Therefore making it the most advantageous month for Louise to start her fundraising campaigns. The second is that both failed and successful campaigns follow a similar trend for most of the year but there are always more successful campaigns than failed, but Louise should beware of starting in December because it has the lowest marginal success rate of all the months. It is almost equaling the failure rate.

- What can you conclude about the Outcomes based on Goals?
First conclusion drawn from this analysis is that the most successful goal range for plays was less than $1,000. The second was that Louise's goal of raising $10,000-$15,000 has over a 54% success rate, which is favorable for her.

- What are some limitations of this dataset?
In my opinion, this was a pretty complete data set. It covered most of the proverbial bases to include a comprehensive analysis but if I were to expand the dataset I would be interested in the demographic of the targeted funders/audience of each campaign. This would give me insight as to if there is a correlation of successful fundraising for plays in one certain demographic or a group of them and which to target.

- What are some other possible tables and/or graphs that we could create?
There are three tables/graphs that I would create to give Louise extra insight to make more informed decisions for her campaign planning. First would be a graph of the average pledged amount per backer of successful campaigns, this would give her an idea of an "ask amount" during her campaign from each backer. Second would a graph consisting of success, fail and canceled rates of the ranges of campaign life. This would give insight to how long the average life of a successful campaign is, giving Louise a better picture of her own timeline. Third I would make a pivot table of all plays' success, fail & canceled rates per country. This would give Louise insight as to where her fundraising and play would be most successful.
