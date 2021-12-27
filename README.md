# Kickstarting with Excel

## Overview and Purpose 

This exploratory analysis was created at the request of “Louise”. The purpose of the analysis is the determination of how various campaigns fared in relation to their launch dates and funding goals. This analysis was comprised of several files: 

1)	Kickstarter_Challenge.xlsx – an excel file comprised of several sheets containing the following information: 
a.	“Kick_Starter_Challenge_Data” – a sheet containing all data points used in this analysis.  
b.	“Theater Outcomes by Launch Date” – a sheet containing a pivot table depicting outcomes by campaign category “Theater” by month of campaign launch.
c.	“Outcomes Based on Goals” – a sheet depicting outcomes by goal category for campaigns related to the subcategory plays. 

2)	PNG Files – in addition to the Kick_Starter_Challenge_Data excel file and sheets, this analysis utilized two (2) PNG files visualizing data trends:
a.	Theater_Outcomes_vs_Launch - a png file that visualizes outcomes by campaign category “Theater” by month of campaign launch.
b.	Outcomes_vs_Goals.png – a png file that visualizes outcomes by goal category for campaigns related to the subcategory plays. 

## Analysis and challenges: 

limited encumbrances occurred while executing Deliverable Number one (1) for this assignment; however, several challenges occurred during the completion of Deliverable Number two (2). The main issues that I encountered was in the usage of VLOOKUP Functions. An analysis of the issues encountering on this aspect is detailed below: 

1)	Issue One: VLOOKUP using multiple criteria: I experienced some difficulty navigating around the execution of VLOOKUP formulas using multiple criteria. Specifically, I was confused by the usage of >= criteria when there is a lower and upper bound.  It took a while watching videos on the internet and videos contained within the module to figure out how to properly structure the VLOOKUP tables such that they pulled the information from the correct tables accurately. 

2)	Issue Two: Formula Copying: Another issue I encountered was the copying and pasting of VLOOKUP Formulas into neighboring columns. Excel appears to automatically move Formula elements one column over when copying and pasting formulas from one column to the next, such that an original VLOOKUP Table pulling data from column X will pull from column Y when copied. 

## Results

This section contains observations and conclusions regarding the Module 1 Challenge. Observations are detailed below: 

1)	Observations from “Theater Outcomes by Launch Date”: The data shows a greater frequency in the number of successful Theater campaigns during the months of May and June. This may be indicative of increased public interest in Theater related services and products during the tail end of Spring and the beginning of Summer. Another observation is that the month of December appears to show indications of greater volatility between the frequency of successful vs. failed theater campaigns than any other month during the year. This may suggest that the public as a lower level of interest in Theatre during this month; however, more research is required to draw any manner of conclusion. 

2)	Observations from “Outcomes based on Goals”: The data shows that fully 84.91% of all successful and failed campaigns for fundraising subcategory ‘plays’ had targeted fundraising goals of less than $10,000. This indicates that the majority of all fundraising goals for plays have lower bound expectations. These fundraising goals may perhaps be well advised, given that the data also shows that high bound goals of over 50,000 had some of the least successful fundraising campaigns of all goal categories (87.50% failed from this category).

3)	Dataset limitations and future goals: The datasets used in this analysis had several limitations. On the sheet labelled “Theater Outcomes by Launch Date”, it may be advisable to parse out the data by year and month rather than just ‘Month’. By aggregating the information across all years, it is likely that we are missing or overlooking key insights and variance between fundraising goals and fundraising outcomes. Additionally, it may be advisable to collect information on the fundraising tactics that were used for a given campaign. It is possible that it is not so much the type of campaign itself or the date when it was launched, but rather the methods used to advertise for fundraising that caused campaign outcomes. 
