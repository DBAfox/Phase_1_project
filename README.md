# Risk Analysis For Jelly Bean Airlines

Navigation through our repo is as follows

**Jelly_Bean_Airlines.ipynb**

   Our jupyter notebook in which we applied our filters for data analysis and resulting plots. 
   Includes findings and recommendations

**Jelly_Bean_Airlines_Presentation.pdf**

   Powerpoint Presentation for this project in pdf format

**.gitignore**

**README.md**

**Data Folder**

   Contains the following data used for analysis 

   * Aviation_data.csv
   * Aviation_data_Cleaned.csv

**Plots Folder**

   Folder containing plots
   
   * Level_1.png
   * Level_2.png
   * Level_2_A.png 
   * Level_3.png
   


## BLUF

Investing in a BEECH or AERO made plane can reduce fatalities **up to 86%**

Focusing more on Private Flights reduces risk of fatality by **27%**

Servicing the contiguous US reduces risk of fatality **as much as 53%**
compared to flying to US territories


## Business Problems

Jelly Bean Airlines is at a crossroads. The problem they face is what airplanes are the safest to invest in? 

That said, we decided to base our recommendations primarily on Fatality Rate.


## Data Filtering and Cleaning

We were provided the Avaition_data.csv dataset by our project manager and
upon inital exploration, The team realized the data had come from the NTSB
and most definitions were provided on their website. We also learned that
the data was incomplete for years prior to 1993 so that was filtered immediatley. 
We filtered out thousands of values and dropped several columns that we deemed unnesscesary
by using several sources listed in Sources at the bottom of this file
However out data is limited by several other factors. There is little to no
data on international flights and we dont have any data on successful flights.
Our reccomendation will have to based on Domestic Flights. 


## Visualizations

From here, the team split up to focus on each of the the following visualizations

First Danny looked at the rates of fatalities in Commercial vs Private Flights illustrated below

![Level_1_Plot](plots/Level_1.png)

Here we can see a clear trend towards Private Flights having a much lower fatality percentage


Travis took our analysis a step further by looking at safer Private Flights by Make

![Level_2_Plot](plots/Level_2.png)

We have a bit clearer of a picture starting to form but what if we include the weather as variable?

![Level_2_A_Plot](plots/Level_2_A.png)

Now we can see that some makes are much more reliable than others even in bad weather


Sam then asked maybe some regions in the US would be safe to avoid?

![Level_3_Plot](plots/Level_3.png)

Yes indeed! Stay over dry land!! 



## Takeaways

We have concluded that Jelly Bean Airlines should invest in planes made by BEECH or AERO with a focus on Private Flights servicing the contiguous US

## Future Steps

We would like a more complete dataset to expand our analysis to flights that did not have any incidents or accidents.
While we are comfortable with our analysis, it is limited in that we have no metrics for total flights or international.
We would like to run another analysis for Jelly Bean Airlines usung more complete data.

## Sources and Links

[What some of the Purpose of flights mean](https://www.ntsb.gov/safety/safety-studies/Documents/SS0101.pdf) 

[or](https://www.faa.gov/sites/faa.gov/files/2022GASurvey-Appendix-B-Documents_04DEC2023V1.pdf) 

[or](https://ia903102.us.archive.org/17/items/6560171-Survival-Flight-Accident-Report/6560171-Survival-Flight-Accident-Report.pdf)

[List of FAA Acronyms](https://www.proairpilot.com/faa-acronyms-list.html)

[FAR Description](https://www.ecfr.gov/current/title-14/chapter-I/subchapter-G)

[Tableau Dashboard](https://public.tableau.com/shared/FCCHZQHFZ?:display_count=n&:origin=viz_share_link)