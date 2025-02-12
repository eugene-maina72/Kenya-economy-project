<img src = "images\Nairobi's_Central_Business_District_Landmark_Skyscrapers..jpg" width="700" >

## Investigating the growth of the Kenyan Economy since the year 2000

**Author:** : Eugene Maina
***

## Overview

This project is undertaken to assess whether the economic policies employed by the Kenyan Government since the turn of the millennium have led to the economic growth of the country. Has it led to an improved quality of life for its residents and boosted foreign investor confidence?
***

## Business Problem

To enable foreign investors, politicians, and economic policymakers to make wise economic decisions, it is essential to understand the key indicators behind Kenya's economic progress over the previous 25 years.
 In order to provide insights that help guide plans for equitable and sustainable growth, this project will examine historical economic data to find trends, correlations, and contributing variables to Kenya's economic performance.

 Who are the target audience/key beneficiaries  for this data?

* Foreign Investors looking to invest in the economy through T-Bills and Bonds

* Economic policyholders trying to assess the overall trend of the economy

* The general public trying to assess the state of the economy
***
## Data
The data that will be used to answer these questions can be attained from websites of national and global statistical institutions such as the Kenyan Bureau of Statistics, The World Bank, and the  United Nations- World Population Prospects. However since it would be time-consuming to attain .csv files from all these websites, I opted to use [www.macrotrends.net](https://www.macrotrends.net/global-metrics/countries/KEN/kenya/population) since they do have ready-made csv files. 

The `data` we shall be using is from the year 2000-2023 because the data is yet to be updated for the year 2024 and 2025(the current year of this repo)


## Methods

Exploratory Data Analysis was carried out to determine the relationships between some key economic indicators and visualizations were derived to understand the performance of the economy since the turn of the century.


## Results

<img src = "images\gdp_vs_fdi.png" width="600">

* Although it doesn't affect the GDP growth, the level of foreign direct investment has been volatile over the years with its peak being in 2011 which aligns with the launch of the "Vision 2030" development plan by the Kenyan Government and its lowest being in the year 2006 before the election year of 2007. Interestingly, The country seems to enjoy its peaks in investment around most election periods. Maybe perhaps this is due to changes in policies by different regimes.

<img src = "images\Trade_deficit_vs_manufacturing_output.png" width="600">

* The strong negative correlation between the Manufacturing Output and the Trade deficit suggests that there seems to be a reduced reliance of imports due to the overall production of the Manufacturing industry increasing. This could implicate a great opportunity for exports which is a strong incentive for foreign investors to come set up industries in the country. This in turn leads to job creation, increased tax revenue for government spending, and better overall economic prosperity due to the terms of trade improving our foreign currency exchange.
You can find more visualizations and analyses on the jupyter notebook 
***
## Conclusions
#### Recommendations:
* Overall, in conclusion, the data suggests that Kenya is on the right path in terms of economic prosperity and it would be lucrative for foreign direct investment either through infrastructure bonds or treasury bill and bonds.

* The Economic policymakers should strive to incentivize the growth of the manufacturing sector through introduction of Taarifs, Industry tax reliefs, and Subsidies.

*  The government should strive to create sustainable, development plans to stabilize the level of foreign direct investment over longer periods.

#### Limitations to the study.

* The data collected does not take into account the poverty gaps in the country thus the GNI per Capita may be misleading.

* The data collected is only limited to the year 2023 and thus is not real-time and does not accurately describe the state of the economy currently. (in the year 2025).

* It is difficult to assess whether Kenya is the best Foreign investment destination because this project has not compared the Kenyan economy to other countries.

* The correlation between  manufacturing output and trade balance deficit does not imply causation and may be as a result of of external factors.


## For more information
Please take a look at the [Jupyter Notebook](kenya_economic_analysis.ipynb) and the [Presentation](kenya_economic_analysis.pdf)

For any queries, you can email Eugene Maina on [my email](eugenemaina72@gmail.com) 

Tableu link [here](https://public.tableau.com/app/profile/eugene.maina/viz/KenyanEconomyWorkbook/Dashboard1?publish=yes)

``` 
The contents of this repository are as follows:
  -data
  -images
  -.gitignore
  -kenya_economic_analysis.ipynb
  -kenya_economic_analysis.pdf
  -README.md
```
