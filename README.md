# Excel: Kickstart My Chart

## Background

Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.

Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success. For this week's homework, you will organize and analyze a database of 4,000 past projects in order to uncover any hidden trends.

Using the Excel table provided, I modified and analyzed the data of 4,000 past Kickstarter projects to uncover market trends.

I used conditional formatting & formulas to uncover insights from the data set.

I created a pivot table to analyze the initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.

I created a stacked column pivot chart that can be filtered by country based on the table I created.

I created a pivot table that analyzed my initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.

 I created a stacked column pivot chart that can be filtered by country and parent-category based on the table created.

The dates stored within the `deadline` and `launched_at` columns used Unix timestamps so I converted these timestamps to a normal date.

I created a pivot chart line graph that visualizes the data.

I used the `COUNTIFS()` formula to count how many successful, failed, and canceled projects were created with goals within the ranges listed above. 

I found the percentage of projects that were successful, failed, or canceled per goal range.

I created a line chart that graphs the relationship between a goal's amount and its chances at success, failure, or cancellation.

I evaluated the following for successful campaigns, and then for unsuccessful campaigns:

  * The mean number of backers.

  * The median number of backers.

  * The minimum number of backers.

  * The maximum number of backers.

  * The variance of the number of backers.

  * The standard deviation of the number of backers.

**SUMMARY**

Given the provided data, what are three conclusions we can draw about Kickstarter campaigns?
•	The category with the greatest number of campaigns on Kickstarter is theater with a campaign success rate of 60% and a failure rate of 35%

o	In the theater sub-category, plays had the highest success rate of 65% with a failure rate of 33%

•	The category with the highest percentage of successful campaigns is music with a 77% success rate and a 17% failure rate

o	In the music sub-category, rock music had the most campaigns and a 100% success rate, but while classical, electronic, metal & pop music had fewer campaigns, they also had a 100% success rate.

•	The category with the highest percentage of canceled campaigns is journalism with a 100% cancel rate. 

•	The category with the highest percentage of failed campaigns is food with a 17% success rate and a 70% failure rate.

December doesn’t seem to be a good month for creating a Kickstarter campaign. Projects launched in December had the lowest percentage of success.
What are some limitations of this dataset?

•	You cannot drill down further than sub-category to determine, for example, exactly what kind of rock projects were funded, ie. live shows, albums, equipment purchases, etc.  We don’t know why the projects were cancelled, failed or were successful outside of whether or not they were fully backed.

•	The data set is three years old – from 2009 – 2017

•	The data provided is a sample, not a complete set of data








