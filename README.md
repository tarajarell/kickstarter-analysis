# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this project is to synthesize information for Louise, who is seeking analysis on plays/theater to better understand how to findraise for her own productions. Following her fundraising efforts for one play, she sought a comparison of how other play/theater fundraising efforts had fared - particularly in relation to launch date and fundraising goal amount. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://github.com/tarajarell/kickstarter-analysis/blob/master/Theater_Outcomes_vs_Launch.png)

The Kickstarter data set indicates overall that there were more successful theater outcomes than failed, and that there were more failed outcomes than cancelled fundraisers. Successful months for theater fundraisers peaked in May, and failed fundraisers for theater projects were at their highest May thorugh August and again in October. Cancelled fundraising intitiatives maintained a low and steady trend. There appear to be zero cancelled fundraising campaigns in October. December showed the lowest amount of successful theater fundraising campaigns, with September and November showing the lowest numbers of failed fundraising initiatives.

### Analysis of Outcomes Based on Goals
![Graph of Outcomes Based on Goals](https://github.com/tarajarell/kickstarter-analysis/blob/master/Outcomes_vs_Goals.png)

Goal amounts appear to have a slight overall upward trend among failed play fundraising, and a slight overall downward trend among successful play fundraising. Data from goal amounts in the range of $35000-44999 appear to be against this trend, while the fundraising campaigns with goals of $45000 or more added to the trends previously described. There were no cancelled play fundraising initiatives found in the Kickstarter data set for plays. An even split in the percentage of successful vs failed fundraising campaigns occurred when the goal amount was $15000-19999, while there was a 100% failure outcome when play fundraising goals were $45000-49999. 

### Challenges and Difficulties Encountered
Some challenges in compiling this data into visuals for client comprehension included changing the data information from Theater to Plays between data analyses. The data sets utilized not only changed in what outcomes were being compared against (goal amount and launch date), but also by categories with the parent category of theater (for launch date) and the subcategory of plays (by goal amount). This complicated some aspects of comparing the data sets, as one included larger numbers while the other was more specific and more similar to what Louise's fundraising goals were. It was also difficult to discuss overall Outcomes Based on Goals with the goal criteria being chunked into amounts of $5000s. This did not allow for the graph to scale how many data points were in each goal category. For example, there were 500 total projects in the $1000-4999 goal section (with 73% successful and 27% failed) and 1 total project in the $45000-49999 goal section (with 0% successful and 100% failed), while the chart shows these differences with the same weight on the graph, based on overall percentage.

## Results

### Conclusion of Outcomes based on Launch Date

Launch date did seem to have a level of correlation or predictability with fundraising success. Conclusions may be drawn to recommend to Louise that future fundraising efforts may fare best when launching the initiative in the months of **May**, June, and July. Further, it may be least advantageous to launch new fundraising for theater projects in November and December. 

### Conclusion of Outcomes based on Goal

Fundraising goals did appear to have a relationship with fundraising success when analysing for plays using Kickstarter data. In particular, having a goal of $5000-24999 proved to have a cloaer to 50/50% split on success versus fauilure of a fundraising campaign for plays. The success of a play markedly improved from those which were failures when goals were set at less than $1000 and $35000-49999. It is also important to note that plays with a goal set at $25000-29999 and 45000-49999 both showed substantially more likelihood for failure toward meeting their goal than having success in obtaining the goal. Louise may have the best chance of successfully meeting her fundraising goal if they are set at less than $5000, based on this data.

### Limitations of this dataset

Data is not available for the year 2018 and beyond, specifically for Theater and Plays. While there may not be much variability in fundraising across a given year, it may nonetheless behoove a campaign to look at more recent data sets prior to honing in on fundraising goals in the year 2020 or beyond. 

### Some other possible tables and graphs that we could create
Data variability in the line graph for Outcomes Based on Goals led interpretation of an overall trend difficult to visually analyze. With the addition of a graph showing the trend lines (below), the visual analysis of overall outcomes for play fundraising data may have lent to better interpretation and use by the client.

![Graph of Outcomes Based on Goals with trendlines](https://github.com/tarajarell/kickstarter-analysis/blob/master/Outcomes_vs_Goals_with_trendlines.png)

To account for differences in comparing the findraising outcomes based on launch date (for theater) and the outcomes based on fundraising goals (for plays), a graph could have been created to additionally demonstrate a visual analysis of the fundraising outcomes for plays based on launch dates.

![Graph of Play Outcomes vs Launch](https://github.com/tarajarell/kickstarter-analysis/blob/master/Play_Outcomes_vs_Launch.png)

Furthermore, to find the most recent analysis, graphs for the outcomes for *only* 2015-2017 data could have been included in the final reporting to Louise. These were the most recent dates found in the Kickstarter data, and may emulate the most recent trends in fundraising as compared with dates from further back. 

![Graph of Theater Outcomes vs Launch 2015 to 2017](https://github.com/tarajarell/kickstarter-analysis/blob/master/Theater_Outcomes_vs_Recent_Launch_2015_to_2017.png)

![Graph of Play Outcomes vs Launch 2015 to 2017]
