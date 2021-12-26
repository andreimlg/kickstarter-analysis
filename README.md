# Kickstarting with Excel

## Overview of Project:
Quick analysis on the Kickstarter dataset to understand the behavior different campaings have and the relationship between variables that might determine if the outcome will be successful, failed or canceled.

### Purpose
The purpose of this analysis is to understand if the launch date and the goals have an impact on the success of a campaign 

## Analysis and Challenges
In order to get the most insights of a dataset it is important to understand each of the values that live in the sheet. As Data Analysts, we need to make the right questions even tough we don't know for sure that we'll get an answer. The process followed to get the most out of these files was the following:

-Understand the meaning behind each column.
-Start filtering and formatting so all the data is understandable.
-Statistical Exploration
-What questions are we looking for an answer? 
    -Is the outcome determined by the launch date?
    -Is the outcome determined by the Goal?

### Analysis of Outcomes Based on Launch Date
<img width="297" alt="Theater_Outcomes_vs_Launch" src="https://user-images.githubusercontent.com/31755703/147422266-e87eb188-f621-412f-bf39-10706c72dcb1.png">

### Analysis of Outcomes Based on Goals
<img width="379" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/31755703/147422268-7469056f-cbc7-438b-b2c0-2be3b2d5285d.png">

### Challenges and Difficulties Encountered
You need to be very careful with the criteria used in the countif formula, you can get mistakes if you don't use the right sintaxys or if you forget to put the criteria for each of the cells.

Another challenge is to not get lost in the data, as one of my teachers used to say "Too much analysis causes paralysis", we need to focus on what we are looking for so you don't waste time and energy exploring information that might not be exactly what you are looking for. In order to avoid this, the questions you are looking for an answer must be very specific and we need to be sure that are in the right direction.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
-There's a high probability that launching in May or June will give the campaign higher chances of being successful.
-We also may consider as we move through the end of the year there's less chances of sucess.

- What can you conclude about the Outcomes based on Goals?
As we move from a low budget to the highest budget, we notice a tendency to failure. The recommendation here would be to go for a low budget campaign. Eventough this theory doesn't apply to the range from 35,000 to 45,000 that might be an outlier that needs more analysis and that might get us distracted from the big picture.
- What are some limitations of this dataset?
-We might get more information about the gendre of the plays. More information about the origin of the donation to understand if we need to target a specific public in order to grant success.
- What are some other possible tables and/or graphs that we could create?
- The evolution of the same KPI's through the years.
- <img width="241" alt="years_performance" src="https://user-images.githubusercontent.com/31755703/147422622-ba0dfb65-3031-4e96-b5b9-549cea9aaa58.png">

- Long campaigns vs short campaings performance.
<img width="241" alt="Duration" src="https://user-images.githubusercontent.com/31755703/147422625-a135baa3-25ed-4a75-876f-2c81f39e0105.png">
