# Kickstarting with Excel

## Overview of Project
- Constructing a statistical and visual analysis of the provided Kickstarter Worksheet
### Purpose
- To provide a clear and precise summary of kickstarter data that would allow Louise to properly conduct a kickstarter for her project.
## Analysis and Challenges
- Through incorporating built-in excel functions, I was able to produce an efficient and simple summary that would allow Louise to start a kickstarter that would 
 contain the greatest probability of success. 
### Analysis of Outcomes Based on Launch Date
- At first, I was confused how to properly sort the Theatre Outcomes by Launch Date pivot table in a descending order to show the successful campaigns as the first column. I eventually figured out that this option was simply next to the column labels title within the pivot table and was easily able to correctly sort the columns in the desired order. ![ColumnLabelsScreenshot](https://user-images.githubusercontent.com/35403433/124373863-13aedf80-dc64-11eb-99bb-a0ccecf5c832.png)
- After constructing this pivot table, I created a line graph that displayed the amount of successful, failed, and canceled kickstarter campaigns relative to the specific months that they were created. ![TheatreOutcomesBasedOnLaunchDate](https://user-images.githubusercontent.com/35403433/124373869-2c1efa00-dc64-11eb-8be7-9c61c26e1ee5.png)
### Analysis of Outcomes Based on Goals
- This was by far one of the most important pieces of data that contributed to the results of this project. The Outcomes Based on Goals graph that I constructed from data that was pulled from the Kickstarter Workbook via the countifs() function allowed a simple means for analyizing which kickstarter campaigns for plays succeeded, failed, or were cancelled based on their goal price ranges. ![OutcomesBasedonGoals](https://user-images.githubusercontent.com/35403433/124373979-486f6680-dc65-11eb-85dc-7a307c793ade.png).
 ### Challenges and Difficulties Encountered
 -Although I was able to produce these results in a timely manner, I encountered a few challenges allong the way. Specifically,
 the year() and countifs() functions gave me the greatest difficulty. However, after viewing and studying their documentations, I was finally able to properly implement them in my code. ![CountifsFunctionScreenshot](https://user-images.githubusercontent.com/35403433/124373660-393ae980-dc62-11eb-9340-c450f0bd0986.png) ![YearsFunctionScreenshot](https://user-images.githubusercontent.com/35403433/124373664-42c45180-dc62-11eb-9d9e-4e3fb6c946b0.png)
## Results
### What are two conclusions you can draw about the Outcomes based on Launch Date?
- One can conclude that a relatively low number of theatre campaigns were canceled, specifically only 37 out of 1369, suggesting that, on average, theatre campaigns are quite popular.  A second conclusion that can be made based on the results of this dataset analysis is that the best times to conduct theatre campaigns are during the months of February and May, as these were the two months with the highest number of successful campaigns.
### What can you conclude about the Outcomes based on Goals?
- Based on this data sample, the best goal price range for theatre campaigns is from less than $1,000 to $5,000. This does not come as a surprise as one would expect campaigns with a lower goal price to be successful.  There is approximately a 50% chance for play campaigns to be successful if their goal is less than $20,000. Therefore, as a campaign's goal increases, specifically after $20,000, the more probable the campaign will fail.     
### What are some limitations of this dataset?
While this dataset contains a large number of elements, it does not provide a large number of recent data. This would allow Louise to more easily conduct research into outcomes of theatre kickstarter campaigns within a more recent timeframe. Another limitation could be the fact that the dataset could simply contain more data. More data always allows for results with greater accuracy. For instance, since this dataset contains a large outlier, naturally it's distribution is rightly skewed. Finally, the largest limitation that follows with this dataset is the absence of outreach data, or the amount of marketing each campaign recieved to reach its goal.
### What are some other possible tables and/or graphs that we could create?
- A bar graph or pie chart would also allow for a simple analysis of success relative to goal price.
