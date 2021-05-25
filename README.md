# Module 2 Final Project

# House Sale Prices Prediction

## The Project

From the sales data in King County, I will do the data analysis and select influence factors for making a prediction model. Then, the following questions will be answered:

1. How does the location affect the price?
2. Can we predict the price from a condition?
3. Do building and renovation times affect the price?
4. Does selling time affect the price?

## The Dataset

King County House Sales dataset

## Working File

* <b>student.ipynb</b>

## Result File

* presentation.pdf 

## Summary

1. The location data are zip code, latitude, longitude, and waterfront. Zipcode should not be the influence of selling since it is a number and does not reflect any meaning. Also, the graph is scattering. Latitude and longitude seem to influence. However, after plotting them as a map, it seems that the high selling is in a specific area, for example, near the sea or lake. This data matches with the data from the waterfront. The mean and median of the waterfront shows that the house on the waterfront area has a higher selling price. The additional information about location needs to be added in order to predict the selling price from a location.

2. From mean and median data of built year, the houses that built during 1900-1939 have a higher selling price. From data, the renovation increase the selling price of the house. The price definitely increases after renovation. However, the price still cannot be predicted by only the renovation year.

3. After observing the data, it seems that there is no effect on selling price from selling time. The mean and median of year, month, and day seem to be the same.

4. After observing the data, factors, that could be used for the prediction model, are the square footage of the home, square footage of house apart from the basement, square footage of the basement, square footage of interior housing living space for the nearest 15 neighbors, number of bedrooms and bathrooms, grade, house condition and number of floors.


## Future Plan

For the future, I should include more detail about location, such as downtown, shopping mall, supermarket or public transportation, to increase the accuracy of prediction.

