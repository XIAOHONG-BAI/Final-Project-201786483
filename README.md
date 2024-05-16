Student ID: 201786483

Background and Aim
I have found that in the UK, many shopping malls, supermarkets, banks and other public places have free wi-fi, and even trains have wi-fi, but the speed is not very good, so I am thinking that it may be due to too many users, so I want to study the relationship between population and wi-fi. And considering that more population may also lead to more crime, I want to combine these factors together to research.
So, in this project I want to find the relationship with population, free wi-fi areas and crime data. I want to find in Leeds in 2021 that whether the places with more free-wi-fi have a larger population, and may have more crime happened in these places.
In the project, I used four datasets: resident number, population density, the location of wi-fi data and crime data, and these four datasets are all about Leeds in 2021.
The residents and population density dataset I downloaded from census 2021 dataset. (https://www.nomisweb.co.uk/sources/census_2021) 
The wi-fi data came from Data Mill North (https://datamillnorth.org/) and including a CSV file and a JSON file 
The crime data came from POLICE.UK (https://www.police.uk/pu/your-area/west-yorkshire-police/leeds-city?tab=CrimeMap) 

Non-spatial outputs: 
Using graph and chart to explain the relationship between population density, wi-fi areas and crime.
After joined the four CSV file together and cleaning data, I used the charts and Spearman Correlation to found their relationship.
From the charts, in Leeds in 2021, the higher population density, the more free-wi-fi areas and more crime happened.
Then using Spearman correlation. The Spearman correlation coefficient is between -1 and 1. If the coefficient more than 0, it means a positive correlation between the two variables. If the value less than 0, it means a negative correlation, and the closer to -1 and 1, the correlation is stronger. If they are equal to 0, there are no correlation between the two variables. 
In this report, from the Spearman correlation and heat map, all these four factors have a positive correlation with each other,
	First, the correlation between residents and population density is 0.11, the more residents here, the population density will be higher. 
	Secondly, the correlation between wi-fi and residents and wi-fi and population density are 0.17 and 0.05. These means the more free-wi-fi areas here, the more residents and population density will be higher.
	Then, the correlation between residents and crime is 0.37, the correlation between population density and crime is 0.25, the more residents here, the higher population density, the more crime may happen here.
	Finally, the correlation between wi-fi and crime is 0.28, the more free-wi-fi areas here, the more crime happen. 

Spatial outputs: 
Using map to find the relationship between population, wi-fi and crime.
In this part, we can use maps to show the spatial pattern of these four factors. And I add the Leeds.json and wifi.json to find the spatial pattern.
From the maps, the residents, high population density areas are all concentrated in the central and most of the southwest areas of Leeds. And the crime data is less, and most of crime areas concentrated in some southwest areas of Leeds. 
Then, we can add wifi.json to analysis, from the maps, the free wi-fi areas are concentrated in city center and some southwest areas of Leeds. And after I set a 500m buffer, the free wi-fi areas are concentrated in the areas which has more people, higher population density and more crime areas.
In conclusion, in Leeds in 2021, the more residents, the higher population density, and the free wi-fi areas will be more and may have more crime happened in these areas.
