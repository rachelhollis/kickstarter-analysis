# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends

## Overview of Project
### Purpose
Kickstarter data was used to perform an analysis on the potential relationships between a campaign’s launch date and funding goals to their campaign outcomes. Knowing the time of year to launch a Kickstarter may be a fundamental key to success as well as knowing a realistic funding goal. Louise is mainly concerned with Theater and Plays thus will be the focus of the analysis. 

## Analysis and Challenges
### General
For the purpose of this analysis, live campaigns are omitted from the data set. Live campaign data does not provide any insight into campaign outcomes for Louise. 

In total, there are 1,369 theater campaigns in the Kickstarter data set.  Out of this data, there are 839 successful campaigns (61%) and 493 failed campaigns (36%). Out of the three categories under theater, plays contributed the most. Drilling deeper into the play subcategory, there is a total of 1,047 campaigns with 694 (51%) successful and 353 (26%) failed campaigns. There are no canceled campaigns in the play category but there is a total of 37 failed campaigns in the whole theater parent category.
![Theater_outcomes_total](theater_outcomes_total.png)

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](Theater_Outcomes_vs_Launch.png)

For this analysis, the outcome of each campaign in the Theater category was compared to their launch date for the purpose of determining if dates have an impact on outcome. 

There appears to be a strong correlation between the time of year and success of a campaign. There is a significant spike in the number of successful campaigns between the months of April and July. The number of successful campaigns has doubled failed campaigns for this time period. This analysis shows it would be wise to launch a campaign between these months for a potentially higher success rate. However, for cancelled campaigns there is no evident relationship with launch dates. Therefore, there are other factors that attribute to a canceled campaign. There is a similar lack of relationship between the number of failed campaigns and the launch date. In comparison to the number of successful campaigns, the number of cancelled campaigns stays relatively the same throughout the year. Further analysis of what contributes to a campaign failed outcome is needed. 

#### Challenges and Difficulties Encountered
![Theater_outcome_vs_launch_pivot](Theater_outcome_vs_launch_pivot.png)
![theateroutcomes_launch_percentage](theateroutcomes_launch_percentage.png)

