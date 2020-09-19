# Analysis of Kickstarter Results for Theater Campaigns

## This project looks at how the success of theater kickstarter campaigns differs in relation to their launch dates and their funding goals

### Purpose - The purpose of this project is to determine if there is a best time of year in which to launch a kickstarter campaign in order to increase the chance of being successful.  In addition, the project will determine if there is a target funding goal range that is more likely to result in a successful campaign. 

## Analysis and Challenges 

### Analysis of Outcomes Based on Launch Date

A database of kickstarter campaign results has been provided that includes 1,369 completed campaigns for theater projects.  To examine the outcomes based on launch date, the data is filtered to include only kickstarter campaigns for Theater.  All countries are included in this first analysis although most campaigns are launched in the US and the UK.  The data includes campaigns from the years 2009 to 2017.  The theater campaigns are bucketed into months based on their launch date month and whether or not they were successful, failed or canceled.  The following graph illustrates the results of this analysis:

![alt text](https://github.com/xactuary/kickstarter-analysis/blob/afaf8b9c7d2a360c568dd2ffb0ae7b7a91bba015/Resources/Theater_Outcomes_vs_Launch.png)

The blue line shows the monthly volume of successful campaigns.  It is easy to see that there is a clear jump in successful campaigns in May with a continuation of higher
level of successful campaigns in June.  The level of success then decreases continually to the low point in December. The data highly suggests that Theater campaigns should be launched in May for best probability of success given no other contributing factors.  The data also shows that launching a campaign in December would be the least likely to succeed. 

 
### Analysis of Outcomes Based on Goals
The second part of the analysis looks at the success of campaigns based on the initial fundraising goals set.  A set of ranges has been determined for campaign
goals and the number of campaigns by range have been allocated into whether or not they were successful, failed or canceled.  Note the Live 
campaigns have been removed from this part of the analysis in order to look at completed campaigns only.  In addition, the results are limited to just Plays within the Theater category since Louise's current campaign is for a play.  The following graph illustrates the results of this analysis:

![alt text](https://github.com/xactuary/kickstarter-analysis/blob/afaf8b9c7d2a360c568dd2ffb0ae7b7a91bba015/Resources/Outcomes_vs_Goals.png)

The blue line shows the percentage of the campaigns that were successful in each of the different goal ranges.  More than 50% of campaigns are successful if the goal range is less than 20,000. At this goal point, the campaigns start to fail more often than not except from 35,000 to 45,000 where again there is about a 60% probability of being successful. However, it is likely that these higher levels are not statistically reliable because there are only 6 successful campaigns in these ranges out of 9 total projects.  The table of results is as follows:


  The highest probability of success is in the two lowest buckets which have goals less than $5,000.  

### Challenges and Difficulties Encountered


The dataset provided includes 1,369 Theater campaigns of which 1,047 are completed campaigns for Plays. For the Launch data analysis, looking at it by sub category gives the same results as using the whole theater database.  

The majority of these challenges are for goals with smaller amounts below $20,000.  There is not enough data available to make highly reliable conclusions for campaigns with larger goals.  
It is interesting to note that there are very few canceled campaigns so these are 
probably not important to the analysis.  

The data includes several large outliers which needs to be considered when choosing an analysis methodology.  By looking at the goals by smaller ranges, the outliers get put in the highest range and do not affect the outcome of the analysis since they can easily be ignored.  



## CONCLUSION

In conclusion, the data analysis shows that theater campaigns launched in May have the highest probability of success and those launched in December have the least probability of success given no other over-riding factors.  For outcomes based on goals, the smallest campaigns with goals below $5,000 have the greatest chance for success.  The data is limited because there are only a few data points for goals above $20,000 and there are some very large outliers that skew any results that look at averages or don't separate them out.  


