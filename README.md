# HW5_Bradley_Ritchie
Shiny app link: https://ritchiebradley.shinyapps.io/HW5_Bradley_Ritchie/ 
While it can be accessed from the link, I would recommend running the file locally.
Purpose and functionality:
This Shiny dashboard allows you to filter median income and rent for all fifty states and Puerto Rico and Washington D.C. from the year 2019. Data from the us_rent_income package was used. In the future, I would like to add data from each census and enable plots by state for more than one year.

**In order to filter by state or territory, you must use the full state name with proper capitalization.** Close misspellings and lowercase names are being worked on for the future.

There is also functionality for examining the annual Consumer Price Index from 1912-2022 (although there was obviously not an annual value for 2022 in March of 2022, so data for February was used instead). CPI measures changes in the prices paid by consumers for a basket of goods or services. With this shiny app, you can slide the range slider to examine certain different time frames. https://data.bls.gov/timeseries/CUUR0000SA0?years_option=all_years 

Motivation:
I was motivated to make this dashboard as a start to further analysis I would like to do on inflation, income, and the US economy. It is still rather unfinished, but I hope to polish it more and include more useful comparisons in the future. 
I would have liked to have displayed monthly rent and income side-by-side, but I encountered severe issues when trying to do so. I am still looking into this and may be able to resolve it. I would also have liked to have more than one state display on the plotly for income and rent but was unable to work on that due to the issue with displaying rent and income side by side. 
Consumer price index for other countries would have been nice to add, but the data is not as well collected (from what I could find). The US Bureau of Labor Statistics only has data from 1999-2013. 

