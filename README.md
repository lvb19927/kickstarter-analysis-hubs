# Kickstarted Campaign Analysis
## Overview of Project
This analysis requested by the increasingly successful playwright, Ms. Louise, reveals the most successful campaigns based on category, subcategory, monetary accomplishment, outcomes, etc... Ms Louise's goal is to execute her first fundraising campaign through a her play, *"Fever"*. Through this analysis, Ms. Louise will be able to run a successful campaign based on data findings for campaigns successful in the "theater, play" categories. Within this analysis, shewill be able to measure the stretch of her budget to successfully execute a "play" campaign.
### Purpose
The analysis was performed with by comparing the success of different categories based on time, outcomes, goals/pledged, cost, dates, and type/category.
## Analysis and Challenges
Completing the analysis, Louise has a high chance of success as illustrated below.
### Analysis of Outcomes Based on Launch Date
This chart was created by comparing the launch theater set on a play alongside the % of successes, failiures, and cancelings of campaigns. ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/117100491/204924706-63ec06e5-8b2c-48bc-949a-d4b5a936b225.png) This chart was constructed through comparing campaign launch dates, filtered to "plays" category, and compared to the campaign outcomes. The analysis concludes that Louisewill have the most success if she launches her campaign in May.
### Analysis of Subcategory Outcomes (Extra)
The chart below gives clear evidence that plays are the most common campaign and have a higher success rate than failure.![Subcategory Outcomes](https://user-images.githubusercontent.com/117100491/204925434-e4cbdd16-e392-4ce1-adfd-58182e84a819.png) This data was found by pulling the subcategory data and comparing it against the outcome data. The analysis reveals that plays are common and have a prominent success rate, with unnoticable cancelations.
### Analysis of Outcomes Based on Goals
This chart shows the outcomes of plays against the goal set for the campaign.![Outcomes_vs_Goals](https://user-images.githubusercontent.com/117100491/204931293-03307d31-10cd-4f89-a416-2e385363337c.png) The chart illustrates what campaign goal will most likely be successful, which shows that May would be the optimal time to launch the campaign.
### Challenges and Difficulties Encountered
With theater and plays existing in larger data sets than the other categories/subcategories, it was not as difficult to metric the success factors. Plays is the most common category, however, the formulas necessary to create the Outcomes vs Goals chart were complex due to the tri-factor comparison necessary between data categories. There is also the possibilty of outliers which are harder to find in the large dataset. This can be eliminated by delineating through COUNTIFS() and filters.
## Results
- We can conclude from the Outcomes Based on Launch Date chart that May is the most successful month for theater. 
December would be the worst option based on the joint data points between lower success percentages and congruent failure percentages. 
- We can draw from the Outcomes Based on Goals that a lower goal most often meets success while there is more likely failure as the goal increases *except* between the goal 35000 to 40000, roughly. 
- There is no way to metric if Louise's $10000 budget will have an affect on the campaign success. We can see the goals and pledges, but there is no data telling how the budget affects the campaign outcomes.
- Furthermore, we could compare the data on which countries were most successful for plays, as well as graphing the amount of backers against the goal, what was pledged, and the outcomes to see how many backers normally accompany a certain goal amount - average how much they pledge, and whether or not it is successful.
