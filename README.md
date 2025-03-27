# Analyzing the reduction of the debt-to-income ratio in the United States between 2007 and 2015 at the state and county level

![](/scratch/embedded_screenshot_static_project.png?raw=true "")

Author: Miguel Pérez

## Description of the project

This document analyses the generalized reduction in the household debt-to-income 
ratio that happened in the United States after the Great Recession between 2007 
and 2015 by using data at the state and county level.

While the data shows a huge disparity in the level and in the change of the
debt-to-income ratio among states and even more among counties, these
changes in debt-to-income ratios were handled more by richer counties,
and at least in a preliminary analysis don't show a correlation between 
these changes and socioeconomic impacts such as unemployment, income,
and poverty.

## Repository Structure

The code (graphs.ipynb) and the image outputs of the code (svg files) are available at the [src](https://github.com/miguelperez94/reduction_dti_ratio_united_states/tree/main/src) folder.

The data, both procesed and raw, are available at the [data](https://github.com/miguelperez94/reduction_dti_ratio_united_states/tree/main/data) folder.

The final analysis document is available at the [static_final](https://github.com/miguelperez94/reduction_dti_ratio_united_states/tree/main/static_final) folder.

## Data Sources

The main data source for this project comes from the data on household debt-to-income
ratios at the state and county level provided by the Enhanced Financial Accounts project
(EFA). That data was obtained from https://www.federalreserve.gov/ and is used in all the
data analysis through the project.

The secondary sources for this project are:

* The aggregated household debt-to-income ratios at the national level, from the 
Financial accounts of the United States. Data obtained from https://www.federalreserve.gov/
and used for the first graph ("Hosehold debt-to-income ratio in the US").
* Data about population and socioeconomic characteristics such as income, unemployment, 
and poverty by county was obtained from OpenIntro, particularly https://www.openintro.org/data/?data=county_complete.
This website has combined data from http://census.gov, the tidycensus R package, the Bureau of 
Labor Statistics, the Census Bureau, and USDA, among others. The data from this website is used
in the process of generating data for the first graph ("Household debt-to-income ratio in the US"),
for the data cleaning process, and for the analysis related to median household income,
unemployment, and poverty.
* I acknowledge inspiration in the format of part of the layout of this project from the document 
"An examination of food insecurity in the United States, and the case for food rescue",
by John Greer.
