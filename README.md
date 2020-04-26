# 0421-Covid19_Sanny-YE

# Crisis Management with Covid-19 Data
## Background 
In this project, we will analyze data from the US Census, American Community Survey, New York Times, and US Hospital data to gain more insights into how different counties might need to implement social distancing and work from home policies or to better manage supply needs based on the county population demographics and available hospital beds in the counties.

### Business Question
1) Which counties are most vulnerable based on population demographics and hospital bed availability?
2) How should different counties adjust their policies to limit the spread of the virus and ensure that enough resources are prepared for the patients?

### Data Question 
1) Which counties are most populated in the U.S.?
2) Is there a correlation between hospital resources and population make-up?

## Data Analysis
Based on the analysis, we can summarize our findings:
1) Hospital count and hospital bed count are closely related to the population of male and female over 60 years old and under 18 years old. 
2) Generally, most counties have around 20%-25% of its population under 18 and around 17%-25% of its population over 60 and those counties have the highest per-capita count for hospitals and hospital beds. 
3) The number of cases is hardly related to the population make-up of counties. As a result, the per capita statistic for cases is also hardly related to the population make-up of counties.
4) The number of deaths is also hardly related to the population make-up of counties and the same for deaths per 1000.
![](Heatmap.png)


## Conclusion
Based on the cluster analysis, we can summarize our findings as the following points: 1) students who attend large-scale community colleges tend to come from families with lower household income, but the social mobility rate of those schools tend to be the highest; whereas small colleges with relatively high parent income and more parents in the top 1% have the lowest mobility rate; 2) medium-size colleges/universities with average parent income has an average social mobility rate; 3) Although the mobility rate of larger universities and medium-size elite universities are the same, universities with higher rankings have a higher upper-tail mobility rate, which means that the percentage of students who have parents in the Bottom 20% of the income distribution and reach the Top 1% of the income distribution is the highest of all.

## Additional Links
1) Data Source: https://github.com/jhu-business-analytics/covid-19-case-python-data-analysis
2) Tutorial: https://melanieshimano.gitbook.io/merging-data-and-plotly-visualizations/
