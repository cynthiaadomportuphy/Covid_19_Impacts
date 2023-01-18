Race, Income, and Age 65+ on Covid in NJ Counties
================

01-17-2023



<img width="500" alt="COVID19 DNA" src="https://user-images.githubusercontent.com/121705109/213087473-4c1ea1f6-ba7f-4188-b9ad-b58195944d79.jpg">




## 1. SUMMARY

The Covid-19 pandemic affected different people, and geographies differently. Covid hit its highest records in 2020. New Jersey was one of the states heavily affected by the virus, especially at the beginning stages, in 2020. Considering the metropolitan and diverse nature of the state, coupled with the fact that my family lives here, I was inspired to explore the way covid affected the state. 

I wanted to know the extent to which death from covid-19 was similar or different from death from other causes across counties, and if there were major differences between the two, I wanted to further explore the effect of three demographic and socio-economic variables on covid-19 incidences. Based on the goal for this study: 
Research Questions: 

* Does the rate of death from covid-19 differ from the rate of death from other causes in New Jersey?
* To what expect do income, race and age 65+ affect covid-19 death rates?
* Are race and income the strongest factors that affect covid-19 death rates? 
   
Hypothesis:
* Yes, the rate of death resulting from other diseases is different from the rate of covid-19 related deaths across New Jersey counties. 
* Yes, counties with a higher percentage of non-white population, lower per capita income and a higher percentage of the population 65+ will have higher incidences and rates of covid-19 deaths. 
* Yes, income and race have a stronger effect on the rate and incidence of covid-19 thank age 65+.




## 2. DATA AND PREPROCESSING 
I downloaded the data from these sources:
* [NJ Demographic data (2019 and 2020)](https://rutgers.app.box.com/s/wonyb2q2rriocqo0o628f8vdtpw8ha6d)
* [Covid-19 Data (2020)](https://data.cdc.gov/NCHS/Provisional-COVID-19-Death-Counts-in-the-United-St/kn79-hsxy/data)

 

For the demographic data, I compiled them into one single sheet and cleaned the data, formatted the cells, and cleaned the data using excel.
For the covid-19 data, I cleaned and formatted the cells and remove unnecessary columns from it. I then imported the dataset into bigquery for SQL analysis.




## 2. ANALYSIS AND FINDINGS

I was interested in knowing how the rate of the Covid-19 pandemic differed across the counties in New Jersey, and how that compared with death from other causes. After the analysis, this is what I found:  

* Yes, the rate of death resulting from other diseases is different from the rate of covid-19 related deaths across New Jersey counties. 

    1. I found that indeed, there are differences between death from covid-19 and death from all other sources, however this was true for only some counties. For               the other counties, the differences were subtle. Specifically, counties such as Bergen, Essex. Passaic, Hudson, Morris and Union are the counties with notably         higher covid deaths than death from other causes. Cape May and Salem had lower covid death rates than death from other causes.




![Dashboard 1 (5) (1)](https://user-images.githubusercontent.com/121705109/213210640-8bab01b6-ea1a-4260-89b2-55cc118af27c.png)




* Yes, counties with a higher percentage of non-white population, lower income and a higher percentage of the population 65+ will have higher incidences and rates of covid-19 deaths. 

     1. I found that for age 65+, most of the counties with high covid-19 deaths actually had slightly higher proportion of the aged population. The only exception was         Ocean County; which had higher covid death and also had a high proportion of aged population. Interestingly, Cape May County with the highest proportion of             aged population recorded one of the lowest covid-19 death rates. With regards to income, again, there was no direct relationship between income levels and             covid-19 incidences. Counties like Bergen and Morris with the some of the highest covid deaths have high incomes, but we also have counties like Essex and             Cumberland with relatively lower per capita income and having some of the highest covid-19 deaths. 

        Unlike age 65+ and per capita income, race was a more interesting indicator. I found that Counties such as Essex, Passaic and Union with relatively higher             covid deaths have the highest proportion of non-white population. 





![Dashboard 1 (4) (2)](https://user-images.githubusercontent.com/121705109/213219309-1922f64f-75cd-442c-a7b6-32e6a9d34f76.png)






![Dashboard 1 (3) (1)](https://user-images.githubusercontent.com/121705109/213228161-831a48b7-e2c6-4e5b-a505-7ec50a154837.png)





![Dashboard 1 (2) (2)](https://user-images.githubusercontent.com/121705109/213233612-0520f97a-866b-4ff2-b3c0-7d5b8814fc2b.png)


* Yes, income and race have a stronger effect on the rate and incidence of covid-19 than age 65+.
     1. So, summing it all together, let’s look at the chart that shows relative impacts of race, income and age 65+. All the counties have almost the same                     distribution of age 65+ income, though there is a slight difference for age 65+ for counties that had higher covid deaths versus those with a lower rate.               For race (%non-white), the counties with higher proportion of non-white population are almost twice more likely to have higher covid deaths. Race therefore is         the most important determinant of covid deaths in New Jersey at the county level. Unlike previousLY predicted, income play a less important role in covid               deaths in New Jersey counties. 




## 4. RECOMMENDATIONS AND CONCLUSIONS
* The more vulnerable population is minorities, in this case, Blacks and Hispanics; this narrative is similar to the general trend of covid-19 deaths.

* Counties that are rich are not necessarily less vulnerable to covid-19. Race plays a huge role to the extent that even counties which fall within the highest income category, but have very high proportion of non-white population have very high covid deaths. Policy must therefore focus on providing the needed resources targeting racial lines, more so than socio-economic lines. 

* Overall, Cape May with the highest proportion of age 65+ had one of the lowest covid deaths. On the other hand, it had the highest death from all causes. Focus on a place like Cape May should be on what is causing higher death among the aging population, different from respiratory diseases such as covid-19.





![Dashboard 1 (5) (1)](https://user-images.githubusercontent.com/121705109/213089258-32ff589b-95eb-4bc7-950c-688b3eb37831.png)


![Dashboard 1 (4) (2)](https://user-images.githubusercontent.com/121705109/213089349-06c16e7d-cd63-45be-8fb7-c5dc342650a1.png)


![Dashboard 1 (3) (1)](https://user-images.githubusercontent.com/121705109/213089375-96deeb41-49c8-4602-9e14-d3b1cbda4fc7.png)


Thank you!

I would appreciate your comments. 


