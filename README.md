# An Analysis of Kickstarted Campaigns
## Module 1 practice analysis on kickstarter data to uncover trends for Louise
![GB Musicals](git hub url)
From this box plot we can conlude that there are a couple of outliers that are heavily affecting the skew of the data. 
----------
# Kickstarting with Excel

## Overview of Project 
The purpose of this project is to continue helping Louise draw conclusions from past kickstarter campaigns so that she can make infromed decisions. She is particularly interested in understanding the success of the campaigns in relation to their launch dates and funding goals. 

## Analysis and Challenges 
I conducted the analysis following the steps outlined in the module and challange instructions. The initial steps were focused on adding conditional formatting and clear cell text formats (such as for the dates) to allow me to more easily understand and look at the data. Here is a list of example functions that I used to set up the sheet: 
- `=IFERROR()`
- `=(((J2/60)/60)/24)+DATE(1970, 1, 1)`
- `=YEAR()`
- Conditional Formatting: Graded Color Scale 
 Below you can see an example of how the data looks after applying these changes: 
IMAGEEEEE
### Deliverable 1 
The goal of this deliverable was to visually show data patters for theater outcomes by launch date. To do this, I practiced creating and using pivot tables to create a line graph. I wanted to show how many campaigns were successful, cancelled, and failed by month of the year. I made sure to apply filters for 'Parent Category = theater' and 'Years = all'. The final pivot table can be seen below: 
IMAGGEEEE
I then followed simple stemps to insert a line graph based on the pivot table. The final line graph can be seen below: 
IMAGEE
### Deliverable 2
The goal of this deliverable was to visually show data patters for outcomes for plays based on goals. Instead of creating a pivot table with existing data, i created my own table and inserted functions to find the relevant information. I only used the `=COUNTIFS()`, `=ROUND()`, and division. The final table can be seen below:
IMAGEEEE
I then followed simple steps to insert a line graph based on the table. The final graph can be seen below: 
IMAGEEE

Explain how you performed your analysis using images and links to code, as well as any challenges you encountered and how you overcame them. If you had no challenges, describe any possible challenges or difficulties that could be encountered.

### Analysis of Outcomes Based on Launch Date

### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Theater Outcomes by Launch Date?
May was the month with the most successful campaigns
May june july august and october all have a similar amount of failed campaigns 

- What can you conclude about the Outcomes based on Goals?
I can conclude that kickstarter campaigns for plays are more than 50% successful if the goal falls between these four brackets: less than 1000, 1000 to 4999, 35000 to 39999, and 40000 to 44999. 
I can also conclude that all the kickstarter campaigns for plays that have a goal between 45000 and 49999 have a 100% failure rate. 
I can conclude that kickstarter campaigns for plays are more than 50% failed if the goal falls between these four brackets: 25000 to 29999, 30000 to 34999, 45000 to 49999, and greater than 50000. 

- What are some limitations of this dataset?


- What are some other possible tables and/or graphs that we could create?
Time of campaign 
