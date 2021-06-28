# The Battle of Neighbouthoods : Segmenting and Clustering in Amsterdem
## Description & Disscusion of the Background
Amsterdam (/ˈæmstərdæm/, UK also /ˌæmstərˈdæm/,[5][6] Dutch: [ˌɑmstərˈdɑm] (About this soundlisten)) is the capital and most populous city of the Netherlands with a population of **872,680** within the city proper, **1,558,755** in the urban area and **2,480,394** in the metropolitan area. Found within the province of North Holland, Amsterdam is colloquially referred to as the "Venice of the North", attributed by the large number of canals which form a UNESCO World Heritage Site.[1]
Amsterdam is divided into seven districts,Each district is divided into neighbourhoods. Amsterdam has 26 neighbourhoods in total, each with its own character.Every neighbourhood has its own characteristics and needs, so independent area plans are made for each area every year.This plan covers relevant issues and local needs. The City cooperates on drawing up and executing these plans, together with residents, the business community and organisations. It is called an ‘area-based approach’.[2]

Amsterdam is a city with a high population and population density and very popular tourist destination . Being such a crowded city leads the owners of shops and social sharing places in the city where the population is dense. When we think of it by the investor, we expect from them to prefer the districts where there is a lower real estate cost and the type of business they want to install is less intense. If we think of the city residents, they may want to choose the regions where real estate values are lower, too. At the same time, they may want to choose the district according to the social places density. 

When we consider all these problems, we can create a map and information chart where the population density is placed on Amsterdam and each district is clustered according to the venues density.


## Data Description
To consider the problem we can list the datas as belows
* I found the Second-level Administrative Divisions of the Turkey from Spatial Data Repository of NYU [2]. The .json file has coordinates of the all city of Turkey. I cleaned the data and reduced it to city of Istanbul ([Here is my .json file](https://github.com/Srcanyildiz/istanbul/blob/master/istanbul_geo_1.json)) where I used it to create **choropleth** map of Housing Sales Price Index of Istanbul.
* I used **Forsquare API** to get the most common venues of given Borough of Istanbul [3].
* There are not too many public datas related to demographic and social parameters for the city of Istanbul. Therefor you must set-up your own data tables in most cases. In this case, I collected latest per square meter Housing Sales Price Averages ([Here is my datas](https://github.com/Srcanyildiz/istanbul/blob/master/istanbul_geo.csv)) for each Borough of Istanbul from housing retail web page [4].
* I used **Google Map**, 'Search Nearby' option to get the center coordinates of the each Borough. ([Here is my datas](https://github.com/Srcanyildiz/istanbul/blob/master/istanbul_geo.csv)) [5].

### References:
* [1] [Amsterdam - Wikipedia](https://en.wikipedia.org/wiki/Amsterdam)
* [2] [City of Amsterdam]https://www.amsterdam.nl/en/districts/)
* [3] [Forsquare API](https://developer.foursquare.com/)
* [4] [Housing Sales Prices of each Borough from "Hurriyet Retail Index for 2018"](https://www.hurriyetemlak.com/Emlak-Endeksi/Detayli-Analiz/Istanbul)
* [5] [Google Map](https://www.google.com/maps/)
