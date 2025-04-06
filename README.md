# Election Voting Analysis
This is an analysis of the United States’ 2016 Election results. The analysis was conducted in python using Pandas, geospatial visualizations, linear regression, and SciKit learn pipelines.

The data set was collected from every county in all 50 states with several variables, including racial breakdown, income levels, careers, and gender.
![Votes per State][assets/image.png]
![Correlation between variable and county's canidate winning the election][assets/image(1).png]
However, as seen in the above heatmap, the strongest predictor of a county’s winning candidate wining the whole election was the total number of votes from that county. 

Another strong predictor for winning was income. As seen in the below graph, more votes came from counties in a higher income category, while relatively few came from medium and low income counties.
![Income vs Percentage of women in the local population][assets/image(2).png]

Taking a closer look at the role of gender in this election, we can see from the pivot table that voting Democrat was associated with women, while the gender split for Independent and Republican was a little bit more evenly split.
![][assets/image(3).png]

Interestingly, a higher percentage of women in the local population is also correlated with a higher income level, suggesting that gender may be correlated with party through a connection to income level.
![][assets/image(4).png]