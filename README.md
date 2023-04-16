Migration and weather, is there a relation?

I wanted to tackle a question that sparked my curiosity, is there a relation between the weather of certain departments in Colombia and the amount of immigrants there?

To solve said question, I searched for datasets relating weather (temperature and rain precipitation) and the amount of Venezuelan immigrants in each municipality of Colombia.

I came across with not that many datasets, when it came to the weather topic, I found a lot of information in the IDEAM (Environmental, Hydrology, and Meteorology studies institute) colombian website, but most of that information was PDF's graphs and not datasets per se, what i was able to find was a website where the user could download specific datasets for an specific month of the year, so i chose february 2022 to download the weather info containing data about rain precipitation and mean temperature for municipalities where IDEAM had the sensor (at least one for each one of the 32 departments).

While looking for the migrants information, it was easier to find, i found a dataset where I found a very complete information about migrants in each municipality of Colombia for the month February 2022 as well (a very strong reason to choose that month for the weather data).

I started by doing some pre-processing of the data, cleaning it and renaming the columns so I could merge it later. I used Geopandas because I thought it was a very efficient and visually appealing way to portray the information about the departments and the inmigration phenomena ocurring in Colombia in recent years.

This code might be updated later.

This code was made by Juan Camilo Muñoz - https://www.linkedin.com/in/jucmunozar/
