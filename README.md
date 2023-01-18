Race, Income, and Age 65+ on Covid in NJ Counties
================

01-17-2023



## 1. SUMMARY

The Covid-19 pandemic affected different people, and geographies differently. Covid hit its highest records in 2020. New Jersey was one of the states heavily affected by the virus, especially at the beginning stages, in 2020. Considering the metropolitan and diverse nature of the state, coupled with the fact that my family lives here, I was inspired to explore the way covid affected the state. 

I wanted to know the extent to which death from covid-19 was similar or different from death from other causes across counties, and if there were major differences between the two, I wanted to further explore the effect of three demographic and socio-economic variables on covid-19 incidences. Based on the goal for this study: 
Research Questions: 

* Does the rate of death from covid-19 differ from the rate of death from other causes in New Jersey?
*Does income, race and age 65+ affect the rate of covid-19 rates?
*Are race and income the strongest factors that affect covid-19 rates and incidences? 
   
Hypothesis:
* Yes, the rate of death resulting from other diseases is different from the rate of covid-19 related deaths across New Jersey counties. 
* Yes, counties with a higher percentage of non-white population, lower per capita income and a higher percentage of the population 65+ will have higher incidences and rates of covid-19 deaths. 
3* Yes, income and race have a stronger effect on the rate and incidence of covid-19 thank age 65+.


## 2. DATA AND PREPROCESSING 
I downloaded the data from these sources:
* [NJ Demographic data (2019 and 2020)](https://rutgers.app.box.com/s/wonyb2q2rriocqo0o628f8vdtpw8ha6d)
* [Covid-19 Data (2020)](https://data.cdc.gov/NCHS/Provisional-COVID-19-Death-Counts-in-the-United-St/kn79-hsxy/data)

 

For the demographic data, I compiled them in one single sheet and cleaned the data, formatted the cells, and cleaned the data using excel.
For the covid-19 data, I cleaned and formatted the cells and remove unnecessary columns from it. I then imported the dataset into bigquery for SQL analysis (See analysis section for script).

##3. ANALYSIS AND FINDINGS

I was interested in knowing how the rate of the Covid-19 pandemic differed across the counties in New Jersey, and how that compared with death from other causes. 

* Yes, the rate of death resulting from other diseases is different from the rate of covid-19 related deaths across New Jersey counties. 

..* I found that indeed, there is differences between death from covid-19 and death from all other sources, however this was true for only some counties. For the other counties, the differences were subtle.

* Yes, counties with a higher percentage of non-white population, lower income and a higher percentage of the population 65+ will have higher incidences and rates of covid-19 deaths. 
..* All three indicators – race, income and age 65+ impacted covid-19 incidences across the counties.I found that for age 65+ most of the counties with high covid-19 deaths actually had average percentage of the aged population. The only exception is Ocean County. Interestingly, Cape May County with the highest proportion of aged population recorded one of the lowest covid-19 death rates. 
With regards to income, again, there was no direct relationship between income levels and covid-19 incidences. Counties like Bergen and Morris with the some of the highest covid deaths have high incomes, but we also have counties like Essex and Cumberland with relatively lower per capita income and having some of the highest covid-19 deaths. 
Unlike age 65+ and per capita income, race was a more interesting indicator. I found that Counties such as Essex, Passaic and Union with relatively high covid deaths have the highest proportion of non-white population. 

* Yes, income and race have a stronger effect on the rate and incidence of covid-19 thank age 65+.
..* So, summing it all together, let’s look at the chart that shows relative impacts of race, income and age 65+. Counties with high and low covid death rates have almost the same distribution of income and age 65+, though there is a slight difference for age 65+. Counties with lower covid deaths, have a slightly more chance of having less people 65+. For race (%non-white), the counties with higher proportion of non-white population are almost trice more likely to have higher covid deaths.  Race therefore is the most important determinant of covid deaths in New Jersey at the county level. However, unlike previously anticipated, income play a less important role. 

## 4. RECOMMENDATIONS AND CONCLUSIONS
* The more vulnerable population is minorities, in this case, Blacks and Hispanics; this narrative is similar to the general trend of covid-19 deaths.

* Counties that are rich are not necessarily less vulnerable to covid-19. Race plays a huge role to the extent that even counties which fall within the highest income category, but have very high proportion of non-white population have very high covid deaths. Policy must therefore focus on providing the needed resources targeting racial lines, more so than socio-economic lines. 

* Overall, Cape May with the highest proportion of age 65+ had one of the lowest covid deaths. On the other hand, it had the highest death from all causes. Focus on a place like Cape May should be on what is causing higher death among the aging population, different from respiratory diseases such as covid-19.


![Dashboard](https://user-images.githubusercontent.com/121705109/213087256-f6f9eb9b-7d58-4a72-aba0-7d756d3a72b3.png)


Thank you!

I would appreciate your comments. 


