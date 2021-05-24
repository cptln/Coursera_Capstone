
### Research Question
In Module 3, we explored New York City and the city of Toronto and segmented and clustered their neighborhoods. Both cities are very diverse and are the financial capitals of their respective countries. One interesting idea would be to compare the neighborhoods of the two cities and determine how similar or dissimilar they are. Is New York City more like Toronto or Paris or some other multicultural city? I will leave it to you to refine this idea.

### Introduction: Business Problem 
In this project we will compare New York City and the city of Toronto in terms of **their density and neighborhood clustering of Asian restaurants. Specifically, Asian restaurants refers to both east Asian (Chinese, Japanese or Korean) and southeast Asian (Thai, Vietnam, Indian, Indonesian) flavors** contained in their business, middle-eastern items excluded.

We will try to detect locations in scale of neighborhood that are having Asian restaurants. We are also particularly interested in **numbers and distance of Asian restaurants in each area**. We would also find **whether the selected locations are close to city center**.
We suggest the more Asian restaurants the city have, the more Asian immigrants in the city. This comparison may determine the immigration level of these two cities and their dissimilar as multicultural cities. 

The target audience would be thouse who care about urban planning, social science and those who would be potential immigrants in considering about chooseing a city to live. 


### Data Description
Based on definition of our problem, factors that will influence our comparison are:

* number of existing restaurants in the neighborhood (East Asian, Southeast Asian, and other types in total)
* numbers and any distance of Asian restaurants in the neighborhood, absolute and common-share forms required
* distance of neighborhood from city center

We decided to use regularly spaced grid of locations, centered around city center, to define our neighborhoods.
Following data sources will be needed to extract/generate the required information:
* centers of candidate areas will be generated algorithmically and approximate addresses of centers of those areas will be obtained using Google Maps API reverse geocoding
* number of restaurants and their type and location in every neighborhood will be obtained using Foursquare API
* coordinate of NYC & Toronto center will be obtained using Google Maps API geocoding of well known location
