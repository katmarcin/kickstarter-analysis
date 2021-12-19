# Kickstarting with Excel

## Overview of Project 

Data analysis was performed from the [Kickstarter_Challenge](path/to/filename.xlsx) dataset to compile graphical visualizations using Microsoft Excel. 1,369 campaigns belonging to the theater category in this dataset were further categorized into 'successful', 'canceled', or 'failed' and their outcomes were analyzed against their launch date. The outcomes of 1,047 plays, a theater subcategory, were also analyzed against their funding goal amount.

### Purpose

The purpose of this analysis is to uncover trends related to how different campaigns fared based on their respective launch dates and funding goals. For background, our client Louise, a playwright, has reached out to us to analyze Kickstarter data to present campaign outcome visualizations. This will help our client understand some factors that may have influenced her ability to come close to her fundraising goals in such a short period of time. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

For the analysis of Theater Outcomes Based on Launch Date, "months" is used on the x-axis to compare the data on a monthly basis for all years and for the y-axis, the count of outcomes is used to compare "successful, "failed", and "canceled" theater campaigns. From the graphical visualization, we can determine May to be the month with the highest number of successful outcomes. The least successful outcomes were found in December. The highest number of failed campaigns are represented in both October and May. The least amount of failed campaigns are found in November. The highest number of canceled outcomes is represented in January, and the lowest number of canceled outcomes is in October, where there were no canceled outcomes reported. However, the trend for canceled outcomes remains approximately linear through the months as visualized on the graph.

![Theater_Outcomes_vs_Launch](path/to/Theaters_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

For the analysis of Outcomes Based on Goal, the x-axis resresents the monetary value of funds that each play campaign set as a goal. It is broken up into 12 different data points, with each interval ranging $5000, except for our end two intervals, for "less than $1000" and "greater than $50000." Our y-axis represents percentage to compare "successful, "failed", and "canceled" play campaign outcomes. From the graphical visualization, we can determine the most successful play campaigns had a fundraising goal of less than $1000. Campaigns that failed the most, or were the least successful, had a fundraising goal of $45000-49999. Lastly, there were no play campaigns specifically that were canceled, therefore a gray line along the x-axis represents this group of data.

![Outcomes_vs_Goals](path/to/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

There were no difficulties in obtaining our data for our client Louise.  However, challenges that may be encountered upon manipulation of data include filtering errors and formulaic discrepancies. As an example. it is important to filter the "Outcomes Based on Goal" data to show the "plays" subcategory only, otherwise the entire "theater" parent category which also includes musicals and spaces would be included in the graph. If this happens, the client may unknowingly be presented data that is not specific to her need and this may skew her judgments from the presentation. In determining the number of successful play campaigns and its percentages amongst those that have failed or been canceled, it is important to gather the data with the correct formulas assigned to their functions. One minor typo may lead to data that is incorrect. This example of a formula used for the "Outcomes Based on Goal" graph can easily be typoed if overlooked: "=COUNTIFS(Kickstarter!$D:$D, "<1000", Kickstarter!$F:$F, "Failed", Kickstarter!$R:$R, "plays"." If copied and modified in adjacent cells, this formula is a timesaver. However, if "Failed" is not changed to "Successful" to get the number of successful play outcomes, then this will produce invalid data. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Based on Launch Date, I can conclude the most successful theater outcomes were launched in May where there was 111 successful plays. A high yield was also found in surrounding months like April and June. The least successful play outcomes were launched in December; only 37 plays succeeded and this trend is also seen is surrounding months of November and January.

- What can you conclude about the Outcomes based on Goals?

Based on the monetary value of Goals, I can conclude the most successful play outcomes had a goal of less than $1000. The least successful play campaign had a goal of $45000-49999. 

- What are some limitations of this dataset?

Some of the limitations of this dataset would include the following:

-Very broad country representations can create bias and assumptions. If we are to assume warmer or colder months influence successful outcomes, we must not forget that this particular dataset extracts data from a variety of countries in various geographical locations. Example: June in Australia is generally a colder month. June in Great Britain is generally a warmer month. If the dataset was restricted to continents or regions, it is likely that we would get outcomes that would be more helpful for Louise as a playwright for comparison.

-A large timeline for Launch Date in terms of years can create generalizability. Perhaps, Louise would want to see data within the past 2 years instead of 7 years. The specific dataset we used for play campaigns consists of launch dates from 2010 to 2017. Anything can influence the success of campaigns from year to year. For example: if a particular country's economy is generally doing well in a specific year, you might see more successful campaigns as backers might be more willing to invest. Data that is collected more recently might be more helpful for Louise.  


- What are some other possible tables and/or graphs that we could create?

Other possible trends that we can create to help our client Louise are Outcomes Based on Pledged and Outcomes Based on Average Donation. 

![Outcomes_Based_on_Pledged](path/to/Outcomes_Based_on_Pledged.png)
