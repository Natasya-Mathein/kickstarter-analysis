# kickstarter-analysis
Performing Analysis on Kickstarter data to uncover trends
# Overview Project
##### Louise is running a fundraising campaigns to fund the play FEVER in short time period. She wants to know how difference campaigns outcome in the relation of launch dates and funding goals.

# Analysis and Challenges
1.	Outcome Based on Launch Date (Month) 
Overall results was about 50:50
Successful: 54%
Failed: 38%
Canceled 8%
       


2.	Theater Outcomes on Launch Date
Result for Theater is better than overall category
Successful: 61%
Failed: 36%
Canceled 3%

 

 

3.	Outcomes Based on Goal
*	Most of Projects’ Goal value is the range of 1000 to 4999, it’s difficult to compare the value since the currency are varies. 
*	Outcomes based on Goals are more successful for less than 10000 but it’s difficult to say otherwise when the high range goals only have a couple of projects
* In Plays subcategory, there are 0 canceled project which should be verified in the source data if this is correct because there are 1047 total plays and the overall cancellation rate for all projects is 8.6%

 

 

# Results

1.	Outcomes based on Launch Date:
*	Cancelation rate is low 2.7%
* Projects that have most success occurred in the month May and June
2.	Outcomes based on Goal
*	The most successful projects are less than 5000
*	Projects with higher goals are likely to fail
3.	Limitations of the dataset
*	The currency is varies across projects, makes it difficult to compare within the projects
*	Projects could be converted to the same currency but this could have some issues due to the fluctuation of currency exchange rate and when the project occurred
*	Some of data could be incomplete it may skewed the analysis. Example: Subcategory “Plays” does not have cancelation projects
4.	Possible tables and/or graphs:
*	Number of backers based on Subcategory and Goal
*	Outcomes based on Region/Country and goal 
*	Percentage Funded based on Region/Country
*	Average Donation by SubCategory
*	Length of the campaign by SubCategory
