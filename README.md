# King-County-Real-Estate-Analysis

This study was conducted to explore the relationship between the price of homes in
King County, Washington and their location and various property attributes. For this real estate
analysis, I used the dataset “House Sales in King County, USA” found on Kaggle, which
contained real estate data for over 21,000 homes sold between May 2014 and May 2015 in
King County, Washington. The dataset provided numerous characteristics for each home,
including but not limited to the number of bedrooms, bathrooms, and stories, the square footage
of the property’s interior living space and square footage of the property’s lot, waterfront status,
a qualitative score for the quality of view from the property, and a qualitative score for the
condition of the home. In this report, the methods and approaches used to
analyze and assess the relationships existing between the selling price of homes and their
various property characteristics will be discussed along with any statistical findings. 

# Introduction to data

King County, WA realty market dataset from Kaggle.com

21K+ observations, 21 variables including price, property characteristics

Variables:

Price: price of each house sold

Bedrooms: number of bedrooms

Bathrooms: Number of bathrooms, where 0.5 accounts for a room with a toilet but no shower

Sqt_living: Square footage of the apartment's interior living space

Sqft_basement: The square footage of the interior housing space that is below ground level

Sqft_lot: Square footage of the land space

Sfqt_above: The square footage of the interior housing space that is above ground level

Floors: number of floors

View: An index from 0 to 4 of how good the view of the property was

Condition: An index from 1 to 5 on the condition of the home 

Waterfront:  A dummy variable (binary) for whether the apartment was overlooking the waterfront or not

Grade: An index from 1 to 13, where 1-3 falls short of building construction and design, 7 has an average level of construction and design, and 11-13 have a high quality level of construction and design

# Preliminary analysis

![image](https://github.com/ambroso0/King-County-Real-Estate-Analysis/assets/38117605/027dd318-6db7-465c-9b44-14edf27637ce)

The target of this analysis is the price of the houses so we will explore how different house features can influence that. 

- Strong positive correlation between variables price and sqft_living, sqft_above, sqft_living15 and grade; 

- Positive correlation between price and latitude suggesting that price may be related to the location;

- Positive correlation between price and sqft_basement, view and waterfront;

- Variables bathrooms and bedrooms are also correlated with price;

- The sqft variables are correlated to each other as their sum give the total surface of the house.   

![image](https://github.com/ambroso0/King-County-Real-Estate-Analysis/assets/38117605/76fe70c0-665a-4585-965e-5a315b3a0bc1)

The figure above shows the relationship between the geographic location of the house and the relative price. We observed that houses with a lower price are located in the southern part of the map and the majority of these properties are not directly located by the water. On the other hand, we observed that higher prices are located in the middle part of the study area with the highest prices observed right by the water. We concluded that the spatial location of the house is a factor that directly affects its price. 

*Full report and code can be provided upon request.
