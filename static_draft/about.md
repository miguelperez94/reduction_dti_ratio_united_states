# Project Name: An analysis at the US state and county level about the reduction of the debt-to-income ratio between 2007 and 2015 and potential implications

Miguel Pérez Rodríguez



## What is your current goal? Has it changed since the proposal?

My current goal is to analyze the heterogeneity of the reduction in the household 
debt-to-income ratio in the US between 2007 (when it reached a peak of 1.24x) to 2015
(when it reached a level of 0.94x). This reduction is not common in the US (such consistent
reduction at the national level has not been seen for at least 50 years), and there is data
at a county and state level of the household debt-to-income to analyze how heterogeneous
has been this reduction (and its potential correlation with another socioeconomic variables).

The goal hasn't changed since the proposal.



## Are there data challenges you are facing? Are you currently depending on mock data?

I am not depending on mock data.

The major challenge that I am currently facing is that, due to confidentiality, 
the County-Level and State-Level Household Debt-to-Income Ratio database is 
in ranges (not an specific point, but a range between a minimum and a maximum). I am dealing
with this by using the average of the middle point of the range for 12 consecutive quarters
to have a more precise metric, and it is working well in my opinion.

The only issue with this apporach is that for the extreme ranges of values (ratio below 0.4 and 
higher to 3.4) is common that they don't have any variance between 2007 and 2015, so it would 
appear in any scatter plot or heat map that there is an important part of the (in general disperse) 
data concentrated in one point.

To manage this issue, I am excluding the counties with those extremes values from most of the 
county graphs (outliers). It is not the ideal situation, but with this approach I still keep 
most of the data regarding the total US population (the remaining data
representates 85.5% of the US population).



## Describe each of the provided images with 2-3 sentences to give the context and how it relates to your goal.

-First graph: "Evolution of household debt-to-income ratio in the US"

This graph is an initial motivation to study the change in the debt-to-income 
ratio in the US between 2007 and 2015. As this graph shows, after a long period of a 
constant increase in the debt-to-income ratio in the US, following the Great Recession
between 2007 and 2015 (shaded area) the households reduced their debt-to-income ratio importantly,
which generates the question of how was this reduction at a more granulated level.

NOTE: My intention is to add lines and two messages in this graph (taking this link as a reference
https://altair-viz.github.io/gallery/line_chart_with_arrows.html) to add motivation.



-Second graph: "Change in household debt-to-income ratio by state, period 2007-2015"

NOTE: For this graph the brown points refer to the debt-to-income ratio in 2007, while the
bluegreen points refer to that ratio in 2015. This is mentioned in the subtitle, but the legend
for this is yet to be added.

This graph highlights two things: (i) the important difference in initial level of debt by each
state in 2007, and (ii) the important discrepancy of the change in each state between 2007 and 2015,
while some states reduced their ratios by ranges of 0.3-0.5, a few manteined or even increased
their ratios.



- Third and fourth graphs: I will put next to each other the graphs "Household debt-to-income ratio
by county, Year 2007" and "Change in household debt-to-income ratio by county, Period 2007-2015"

The third graph, related to the year 2007, shows that (in general) counties in both coasts started 
with a relatevely large debt-to-income ratio in 2007 (multiple ratios of 2 and even 3), while
counties in the middle of the country started with lower levels of debt.
The fourth graph shows certain geographical correlation between the initial level of debt and its
reduction, with emphasis in counties of the West Coast and Florida.



- Fifth graph: "Counties by debt-to-income ratio and its change"

This heatmap makes more explicit the correlation by county of the reduction of debt and its 
initial level, as it can be seen there is a negative relationship between a higher debt ratio in 
2007 and the debt increase between 2007 and 2015.



- Sixth graph: "Distribution of change in debt-to-income ratio by percentage of counties"

This histogram shows the distribution of the change in the debt-to-income ratio. While the average 
reduction is around -0.21x, this reduction has a notable spread among
counties. Particularly: (i) there are 7% of the counties that had a reduction of debt-to-income 
higher than 0.8x, (ii) 21% of the counties had a reduction between 0.4x and 0.8x, (iii) 26% of
the counties faced an increase in their debt-to-income ratios.

NOTE: The red line refers to the average reduction at the US aggregate level. 
The legend for this is yet to be added.



- Seventh graph: This will be a facetted combination of "Change in debt-to-income ratio by county 
income", "Debt-to-income ratio by county income", and "Reduction in debt by county income"

NOTE: My intention is to mix these three graphs in one facetted vertical bar plot (with this in mind 
as an inspiration https://altair-viz.github.io/gallery/scatter_faceted.html). This is yet to be made.

One question is: this variety in debt-to-income reduction affected some groups more than others?
These three graphs shows that (i) income is directly related to the reduction in debt-to-income ratio
(poorer counties reduced its debt less than wealthier counties), (ii) the initial debt-to-income
ratios were larger in wealthier counties, and (iii) controling by the initial debt, poorer counties
had a smaller reduction in its debt level (as percentage of the initial debt) in comparison to
wealthier counties. In other words, the monetary restrictions imposed by lower debt levels were less
focused on poorer counties, in absolute and in relative levels.

NOTE2: I am thinking on adding another graph, with the same 3 variables, but taking as a 
category for the X-axis "race majority of the county" instead of income.



- Eighth graph: This will be a facetted combination of "Change in debt-to-income ratio and 
unemployment rate", "Change in debt-to-income ratio and household income", and "Change in 
debt-to-income ratio and poverty rate"

NOTE: My intention is to mix these three graphs in one facetted vertical bar plot (with this in mind 
as an inspiration https://altair-viz.github.io/gallery/scatter_faceted.html). This is yet to be made.

In the context of these large variations in debt-to-income ratios, another question is if this
variation has any correlation with other outputs. In this context, the graph shows that (i) counties
with larger reduction in debt-to-income had a smaller increase in unemployment rate in the period, and
(ii) there is no clear correlation between the change in the debt-to-income ratios and poverty change
or income variation in the period. In other words, it seems that important reductions in debt in counties
(with its corresponding monetary restriction) is not correlated negatively with these 3 outputs.



## What form do you envision your final deliverable taking? (An article incorporating the images? A poster? An infographic?)

I am thinking of doing an article incorporating the images.