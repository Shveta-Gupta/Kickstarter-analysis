# Kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends
# Kickstarting with Excel

## Overview of Project

### Purpose
#### By analyzing an excel sheet with data from several kickstarter campaigns, the data analytics and data visualization tools of excel were able to be explored. Several graphs and statistical calculations were used to answer various questions about the data given. Since there were so many data points about various topics, most of the analysis perfomed focused on filtering the data around plays, and whether those campaigns were successful of not. Pivot tables aided in pulling out some of those specific filters so that they could be viewed for easier comparison, and line and bar graphs were also used to visually represent our conclusions.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
#### There are many aspects to a kickstarter campaign, two of the ones we focused on for this analysis were launch date and campaign goals. The analysis on the outcomes based on launch date were shown using a pivot table. ![image](https://user-images.githubusercontent.com/58957855/123566697-4c474880-d78e-11eb-8368-8be9d7ea103c.png) The table could be filtered to show only the outcomes of the failed, canceled, and successful kickstarters, however the graph attatched showed all three categories stacked on top of each other.

### Analysis of Outcomes Based on Goals
#### Analyzing the outcomes of the kickstarters based on the monetary goal they wanted to reach was done in a new worksheet so that analysis could be done without messing with the original data. In order to filter the number of plays that were successful and within the goal range specified, a countif function was used. ![image](https://user-images.githubusercontent.com/58957855/123566898-de4f5100-d78e-11eb-99fa-bed7b4f74bdb.png) 

### Challenges and Difficulties Encountered
#### My largest difficulty I encountered were with making pivot tables and using several conditional IFS (such as =IFS and =COUNTIFS). While creating the pivot tables, I had a lot of trouble just deciding what to put in rows or columns, and how that affected the final table. By making several practice pivtot tables and seeing if they gave me the effect I wanted, I was able to eventually coerce it into showing me what I wanted. I also had some trouble with the countif function. There were times when I thought I had the right formula, but the numbers did not match what was supposed to be shown. In most of those cases, I had selected the wrong column from the kickstarter sheet, so I fixed that by moving to the sheet and selecing the columns directly from there.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. Majority of successful kickstarters for plays launched in the summer, from May to July
2. October had the most amount of failed kickstarters. 
- What can you conclude about the Outcomes based on Goals?
1. Goals above 45000 skew towards failing, however this is a very small dataset so it hard to attribute any trends right now.
- What are some limitations of this dataset?
  The successfulness of a kickstarter is not all in just the numbers, such as goals, dates, categories, etc. Often times other incentives like advertising and kickstarter rewards can play a large part in helping a campaign reach its goal.

- What are some other possible tables and/or graphs that we could create?
    A Box and Whisker Plot could've shown us if there were any outliers in our data that we might want to point out to the client while presenting our results.
