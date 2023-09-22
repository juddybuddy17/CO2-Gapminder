# Skin Cancer Origin using CO2, Global Population and Life Expectancy

### Problem Statement

Researchers are investigating the origins of skin cancer and they have to track when the ozone layer started to deteriorate. Carbon dioxide emissions are known to be harmful to the earth's atmosphere and usually spoken of regarding climate change, life expectancy and population fluctations. The objective of this project are to find out which countries were the highest emitters of carbon dioxide at the earliest stages when carbon emissions came about. According to Gapminder's data, the earliest records of carbon dioxide emissions is 1800. 


# Data Dictionary

| emissions_clean | float | http://gapm.io/dco2_consumption_historic | Carbon dioxide consumed in mertric tonnes per capita. Based off of the Global Carbon Project 2021 |

| pop_clean | float | http://gapm.io/dpop | The total population counts in country listed |

|life_expect_clean |float | http://gapm.io/dlex | The number of years a person from birth would live, given the mortality rates per age would stay the same throughout their life. |

#Help from Rowan and Gapminder


# Executive Summary

In this project I used three data frames from Gapminder which include Life Expectancy, Population, and Carbon Dioxide Emissions per capita. I have reviewed , manipulated and organized these data frames and created diagrams to show which countries were the leading carbon dioxide emitters during the early 1800s. According to the data given, from 1800 to 1820 Qatar had the highest carbon dioxide emissions even though they are one the countries with the fewest population. Another interesting find is that the next two leading countries of carbon dioxide emissions were 10 to 12.5 milliion tonnes less than Qatar and the population of those countries were very similar. My reasoning behind this theory is I took the averages of each data frame by the column year and created a bar graph which included every country as the x axis and the y axis is the known variable. The data from Gapminder, being it was recorded in the 1800s, may need some refining for there were some missing data and some of the dataframes had big outliers.

Just to check if there was already a events happening, I put graphed a scatter plot to compare CO2 emissions with population, and CO2 emissions with life expectancy and there was no correlation. This means that the origin of skin cancer was most likely after the time frame of 1800 and 1820. So how could we find a timeframe of possibly when sin cancer became prevalent? A way to find out when skin cancer started is to broaden our time using the same functions and see when CO2 emissions begins to correlate with life expectancy. We could also then cross examine the data to see which countries in the respectable time frame had the most carbon dioxide emissions and that could be a prime location to investigate skin cancer origination.