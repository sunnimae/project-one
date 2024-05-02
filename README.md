# project-one
A shared repo for first project

## Crime Data Analysis over the 5 major cities in Texas

## Description
  This repo contains five seperate jupyter notebooks, each labled accordingly that provide the data found for each individual city. Other resources include .csv files containing the raw crime rate data used for each city. (All data was pulled from: https://www.dps.texas.gov/section/crime-records/crime-texas)

# Visuals
  Each jupyter notebook should contain roughly the same visuals. Below are some examples from the Houston branch that should give an idea of shared visualizations:
  
![Screenshot 2024-05-01 185700](https://github.com/sunnimae/project-one/assets/162613584/6faaa715-6e89-467e-b27f-01456f2591c0)
![Screenshot 2024-05-01 185715](https://github.com/sunnimae/project-one/assets/162613584/b3ad530e-7fdd-4a4f-a464-78da2bbdd318)
![Screenshot 2024-05-01 185726](https://github.com/sunnimae/project-one/assets/162613584/70b45a99-3d7a-4a2e-873c-66347781e6a6)
![Screenshot 2024-05-01 185738](https://github.com/sunnimae/project-one/assets/162613584/06b5634e-2585-40c1-9810-7f1f93c10772)
![Screenshot 2024-05-01 190330](https://github.com/sunnimae/project-one/assets/162613584/07a1afe1-1c70-45d3-a9cf-3a7ae90cbdcc)

## Individual Cities 
Austin

Total population and crime rate experienced a decline in 2017. The population and crime rate climbs back up in 2018.
When comparing the data from covid years (2012-2019) and after the covid years (2020 to 2022), T-stats of -1.78 and P-value 0.128 indicate that there is no significant difference between the means of the two groups being compared.
As the trend of population continues to increase, we can assume that crime rate will continue to increase and law enforcement will require more funding.

Dallas

Dallas's population grew continuously from 2013 to 2022, with the exception of 2021. The crime rate (per 100,000) also declined during the same period, except in 2020 and 2022. Year by year, the population increase was significantly above the national growth rate. Regression analysis showed almost no correlation between changes in the crime rate and population, with an r-value of 0.031.
When running the t-test on the two dataframes for the crime rate (per 100,000), the outcomes indicate that it is statistically significant enough to reject the null hypothesis with a confidence level of 95% or higher. This means that the crime rate during the COVID years (2020 and 2021) was lower than in non-COVID years

El Paso

El Paso’s crime data has exhibited multiple characteristics: that the total numbers of crime and crime rate have both experienced a decline from 2013-2022, and that the total population, total numbers of crime, and the crime rate all experienced an increase in 2022. 
A T-test performed on the difference between years experiencing Covid (2020-2021)  vs. years not experiencing Covid (2013-2020: 2022) produced a p-value of 0.00120, indicating that there is statistically significant difference between the two sets of years. This could be attributed to the population influx spike as seen in the graph of “Total Number of Offenses Over Years, which is seen in 2022, as 2022 also exhibits an increase in both the total number of offenses per year and the crime rate percentage per year.

Houston

Houston has seen a decline in criminal activity from years 2013-22, with spikes in 2019 and 2022. The population has increased at a positive rate throughout those 10 years, averaging much higher than the U.S. average of .3-.4%. The population change percentage and the crime rate change percentage have a correlation ‘r’ value is -0.477 which indicates a moderate negative relationship. After running a correlation t-test between covid years and non-covid years, there is significant evidence with a P-value of 0.0258 which leads to rejecting the null hypothesis that there was no correlation.

San Antonio

Over the ten years from 2013 to 2022, San Antonio saw its highest total crime in 2016 and highest crime rate in 2022. The city’s lowest total crime and lowest crime rate both occurred in 2020. 
With a Pearson correlation coefficient of -0.79 there is a negative correlation between population and the crime rate, however, the t test and p-value indicate a significant difference between the two. This leads me to believe that there are other significant factors impacting the crime rate other than the population. 
Covid greatly impacted crime in San Antonio. The drop in crime in 2020 was most likely due to the lockdown, and the drastic spike in crime in 2022 is likely influenced by vaccines being widely available and restrictions being lifted. The t test and p-values for covid and non covid years are -4.82 and 0.0051 respectively, indicating statistical significance of the impact of covid on crime in San Antonio.

## Authors and acknowledgement
  The contributors on this project were Blake Bartlett (Houston), Hannah McPherson (San Antonio), Thomas Tobolka (El Paso), Beatrik Arimbi (Austin), and Victor Doan (Dallas).
