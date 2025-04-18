# Election Voting Analysis
This is an analysis of the United States’ 2016 Election results. The analysis was conducted in python using Pandas, geospatial visualizations, linear regression, and SciKit learn pipelines.

The data set was collected from every county in all 50 states with several variables, including racial breakdown, income levels, careers, and gender.
![Votes per State](https://github.com/user-attachments/assets/1bec66d9-544a-4d70-95fb-37ba238ba644)
![Correlation between variables and county's canidate winning the election](https://github.com/user-attachments/assets/f2d85618-5a90-4efc-8896-b4579137f850)
However, as seen in the above heatmap, the strongest predictor of a county’s winning candidate wining the whole election was the total number of votes from that county. 

Another strong predictor for winning was income. As seen in the below graph, more votes came from counties in a higher income category, while relatively few came from medium and low income counties.
![Income vs Percentage of women in the local population](https://github.com/user-attachments/assets/72fcf81b-9aae-4195-9784-2aa69f345584)


Taking a closer look at the role of gender in this election, we can see from the pivot table that voting Democrat was associated with women, while the gender split for Independent and Republican was a little bit more evenly split.
![](https://github.com/user-attachments/assets/d93de8f8-ec99-444e-a171-97d0bbf95d01)

Interestingly, a higher percentage of women in the local population is also correlated with a higher income level, suggesting that gender may be correlated with party through a connection to income level.
![](https://github.com/user-attachments/assets/11ba25a0-9449-4c43-836f-bce903305f6b)
