# The Battle of Neighbouthoods : Segmenting and Clustering in Amsterdem
## Description & Disscusion of the Background
Amsterdam (/ˈæmstərdæm/, UK also /ˌæmstərˈdæm/,[5][6] Dutch: [ˌɑmstərˈdɑm] (About this soundlisten)) is the capital and most populous city of the Netherlands with a population of **872,680** within the city proper, **1,558,755** in the urban area and **2,480,394** in the metropolitan area. Found within the province of North Holland, Amsterdam is colloquially referred to as the "Venice of the North", attributed by the large number of canals which form a UNESCO World Heritage Site.[1]
Amsterdam is divided into seven districts,Each district is divided into neighbourhoods, each with its own character.Every neighbourhood has its own characteristics and needs, so independent area plans are made for each area every year.This plan covers relevant issues and local needs. The City cooperates on drawing up and executing these plans, together with residents, the business community and organisations. It is called an ‘area-based approach’.[2]

Amsterdam is a city with a high population and population density and very popular tourist destination . Being such a crowded city leads the owners of shops and social sharing places in the city where the population is dense. When we think of it by the investor, we expect from them to prefer the districts where there is a lower real estate cost and the type of business they want to install is less intense. If we think of the city residents, they may want to choose the regions where real estate values are lower, too. At the same time, they may want to choose the district according to the social places density. 

When we consider all these problems, we can create a map and information chart where the population density is placed on Amsterdam and each district is clustered according to the venues density.


## Data Description
To consider the problem we can list the datas as belows
* Detailed overview of the 578 neighborhoods and boroughs in the municipality of Amsterdam can be found at (https://allcharts.info/the-netherlands/overview-municipality-amsterdam/) . details(Regionname, Regiontype, Zip code, #Inhabitants, #Addresses, #Houses) for each neighbourhoods were webscrapped to create initial dataframe .
* I used ARCGIS library to get the latitude and longitude values of different neighbourhoods of Amsterdam on the bases of their pincodes and added back to main dataframe.
* I used **Forsquare API** to get the most common venues of given Borough of Amsterdam [3].


### References:
* [1] [Amsterdam - Wikipedia](https://en.wikipedia.org/wiki/Amsterdam)
* [2] [City of Amsterdam](https://www.amsterdam.nl/en/districts/)
* [3] [Forsquare API](https://developer.foursquare.com/)
