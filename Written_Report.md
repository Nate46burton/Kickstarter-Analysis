# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of the exercise is to examine if there are any correlations between the launch date of a project and that projects success. It also serves to observe the success and failure percentage in accordance to their goals.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
In order to get outcomes based on launch date, I created a pivot table of all the data, filtered by parent category and years. I then sorted the "outcomes" into the columns section and the "Date created conversion" and then had it count the outcomes.

After getting the pivot table, I then created a line chart to properly illustrate the information.
### Analysis of Outcomes Based on Goals
For this exercise, I followed the steps to create a table to track the numbers and percentages successful/failed/canceled. I then wrote a "countifs" function in order to get a count for the outcomes that matched the criteria.

For instance, If I wanted to see the outcomes of all successfull projects that had a goal between 5000 and 9999 and were plays, I wrote the following function:
=COUNTIFS(Sheet1!$E:$E,">=5000",Sheet1!$E:$E,"<=9999",Sheet1!$F:$F,"successful",Sheet1!R:R,"plays")

After filling out the rest of the functions, I then created a line chart to illustrate the relationship between percent successful/failed/canceled and their goals.
### Challenges and Difficulties Encountered
For the "Outcomes Based on Goals" delivery, I found that my results were not quite matching up with what was shown on the module challenge page. Even after a 1-on-1 tutoring session, my tutor was also unable to see what was incorrect about my formula, it appears to be written correctly and is selecting the correct columns of data to reference.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Theater projects that had a launch date in May also had the highest amount of successful and failed projects, so perhaps there are just more theater productions in the summer. Also December had the lowest total amount of projects, suggesting winter is not a popular time for the theatre.
- What can you conclude about the Outcomes based on Goals?
Because my final data outcomes for this delivery are most likely skewed in some way as mentioned above, I can't quite make accurate assumptions on the outcomes based on goals. 
- What are some limitations of this dataset?
I'm not quite sure what the limitations of the data set would be other than its scale just by the nature of it being excel.
- What are some other possible tables and/or graphs that we could create?
We could create a table/graph to perhaps illustrate a possible relationship between budgets/outcomes and the countries of origin.