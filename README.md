# baltimore-baskingridge-income-and-same-tract 
## Background Information
I am interested in comparing Baltimore city, MD to my hometown of Basking Ridge, NJ. All data comes from [https://www.opportunityatlas.org/](Opportunity Atlas), which uses anonymous data that follows 20 million Americans from their childhood to their mid-30s in 2015. In this project, I am looking at __Household Income__ and __Percentage of Adults who Stayed in the Same Tract (SST)__. Household income refers to the average household income that a person (who grew up in this area) has in 2014-15. The SST metric refers to the percentage of people who still live in the same Census tract that they grew up in. 

I thought that the SST metric was intruiguing - I hadn't seen it as often as I had seen metrics like incarceration rate, high school graduation rate, etc. I wondered if it had any relation to the household income that people would later have as adults.

### Business Question 
How does one's annual household income affect if they, as adults, remain in the same Census tract in which they grew up? 

## Data Sources
[Baltimore Income Data](https://github.com/viv-sun/baltimore-baskingridge-income-and-same-tract/blob/master/Baltimore_Income%20Data.xlsx) shows the raw data for the Household Income metric in the general Baltimore, MD area. It also has a separate worksheet that shows filtered data that refers to Baltimore city only. 

[Baltimore Same Tract Data](https://github.com/viv-sun/baltimore-baskingridge-income-and-same-tract/blob/master/Baltimore_Same%20Tract%20Data.xlsx) shows the raw data for the SST metric in the general Baltimore, MD area. It also has a separate worksheet that shows filtered data that refers to Baltimore city only. 

[Basking Ridge Income Data](https://github.com/viv-sun/baltimore-baskingridge-income-and-same-tract/blob/master/Basking%20Ridge_Income%20Data.xlsx) shows the raw data for the Household Income metric in the 07920 Bernards Township area. It also has a separate worksheet that shows filtered data that refers to Basking Ridge only. 

[Basking Ridge Same Tract Data](https://github.com/viv-sun/baltimore-baskingridge-income-and-same-tract/blob/master/Basking%20Ridge_Same%20Tract%20Data.xlsx) shows the raw data for the SST metric in the 07920 Bernards Township area. It also has a separate worksheet that shows filtered data that refers to Basking Ridge only. 

[Instructions for Data Analysis](https://github.com/viv-sun/baltimore-baskingridge-income-and-same-tract/blob/master/Instructions%20for%20Data%20Analysis.docx) contains instructions on how I gathered the raw data, filtered it, and analyzed it.

## Data Analysis/Metrics 
I compared the Household Income metric against the SST metric for Baltimore, and again for Basking Ridge. 

### Graph for Baltimore Comparisons 
![alt text](https://github.com/viv-sun/baltimore-baskingridge-income-and-same-tract/blob/master/Baltimore_Same%20Tract%20vs%20Income%20Graph.jpg) 

I sorted the household income from low to high to make it easier to see the relationship (if any) between the two metrics. For the most part, it seems that there is not a clear relationship between household income and the percentage of adults who stayed in the same Census tract. However, towards the right side of the graph, household income shoots up and the percentage of adults who stayed in the same tract falls - it looks as if there is an inverse relationship for the two. 

### Graph for Basking Ridge Comparisons 
![alt text](https://github.com/viv-sun/baltimore-baskingridge-income-and-same-tract/blob/master/Basking%20Ridge_Same%20Tract%20vs%20Income%20Graph.jpg)

We do need to keep in mind that this sample size is limited and the range on both Y axes is small. However, it does show (what appears to be) an inverse relationship between the two metrics.  

## Summary 
Overall, the graphs (especially that of Baltimore) seem a bit inconclusive. There appears to be a weak inverse relationship between household income and the percentage of adults who stayed in the same Census tract that they grew up in, but I believe that the lack of a clear/strong relationship is an answer in and of itself. It indicates that there could be a plethora of other factors (in addition to household income) that may also play a part in determining if someone were to stay or leave the Census tract in which they grew up. 

These additional factors include: if people married and left the tract they grew up in; if they pursued higher education, and especially if their universities were within a commuting distance; if there is a brain drain from the area; if people have the income/resources to afford to stay in their childhood Census tracts, assuming if housing prices went up; or if people have the income/resources to leave their childhood Census tracts, assuming they want to leave. By no means is this an exhaustive list, but this illustrates the variety of reasons that may play a role in determining this, beyond just household income. 

Moving forward, I am interested in looking at a larger sample size of data for the Basking Ridge/surrounding area to see if there would be a repeat of the weak relationship that appeared in the Baltimore graph. I would also be interested in looking at how the percentage of people who stayed in the same Census tract relates to other metrics like high school graduation rate (or other available metrics from the Opportunity Atlas data). 

Perhaps the additional data would help identify some of the reasons why people may choose to stay vs leave, but we do need to keep in mind that metrics do not provide any insight into intentions. The decision to stay vs leave a tract is a nuanced and deeply personal one; it may not be properly reflected in just one or two metrics. 
