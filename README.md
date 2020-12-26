# Explore Airbnb data from New York City using Tableau

Tableau Dashboard can be found at: https://public.tableau.com/profile/deepster#!/
## About the Dataset
"New York City Airbnb Open Data" was downloaded from https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data. Exploratory Data Analysis {EDA) was performed using Price, Location, Room Type, Number of Reviews, Availability, and Minimum Nights.

###### Breakdown of each Feature
| Feature                | Description/Notes |
| -------------          | -------------     |
| Price                  | Price of the listed room                                  |
| Location               | Location of the listed room                              |
| Room Type              | Room type: private/single room, shared room, entire house    |
| Number of Reviews      | Number of reviews on the listed room listed<br> I used this as a rough estimate of populatrity <br> (i.e. more reviews a room has = more popular)        |
| Availability           | How many days per year the room is available to the rent    |
| Minimum Nights         | Minimum nights a person must stay in order to rent room <br> (i.e may only rent room A if you are will to rent for 3 or more days   |

## Goals of EDA
Use Tableau to allow exploration of Airbnb market in NYC. 

###### EDA allows you to find answers to the following question

1. How do renting prices compare in different locations in NYC?
2. Which locations are more popular to stay at and how does this affect the price?
3. What are some features that contribute to the price of a room?

## Breakdown of Tableau Dashboard
<img src="https://github.com/deepster/Tableau-Test-Run/blob/main/images/dashboard_overview.jpg" width="700" height="475"/>

###### Overview of Dashboard
The interactive graph provides insights to the above questions

1. Filter: filters by price, borough, and number of reviews (Top Right)
2. NYC map: displays the location of the listing along with its price & range at the location
3. Sideway bar chart: Displays the average avaliability, minimum night requirement, and the number of reviews at the listed location (Bottom left)
4. Pie chart: Displays the total amount of each room types in the selected location (Bottom Middle)
5. Bar chart: Displays the average price breakdown for each room type in the selected location (Bottom Right)
 
<img src="https://github.com/deepster/Tableau-Test-Run/blob/main/images/dashborad_overview_gif.gif"/>

Hovering over any point gives you information on the location of the listing, its price, and updates the graphs below to show more information about that listing.

## Insights from exploring Airbnb data from New York City

###### Manhattan is the most expensive locations in NYC
<img src="https://github.com/deepster/Tableau-Test-Run/blob/main/images/price_by_location.jpg" width="700" height="475"/>

Adjusting the price filter, we can see where the more expensive listing are located.
- In general the more expensive listings are located in Manhattan. However, most of these listing are for rental houses and not rooms.
 - future analysis/next steps: Create more filters to filter the data by other features, such as room types to visualize if there are trends in price vs location given a room type
 
###### There are popular rental hot spots in each borough

<img src="https://github.com/deepster/Tableau-Test-Run/blob/main/images/Popularity_by_location.jpg" width="750" height="350"/>

Filtering by the "Number of Reviews" you can identify the area where the rooms with the most reviews on average are located. Using the average number of reviews as an approximate measure of popuarity, I found favorable hot spots in different boroughs  

Future enhancement: enable multiple filters to visualize & reason for the effect of price & availability on the selection of the popular location and comparison between the popular locations  
  
###### What are some features that contribute to the price of a room?
<img src="https://github.com/deepster/Tableau-Test-Run/blob/main/images/price_factors.jpg" width="700" height="475"/>

-Looking at the minimum night requirement and avaliability, it seems they don't have much affect on price (comparing this snapshot with the snapshot obtained to answer "How do renting prices compare in different locations in NYC?")
- Room type does affect the price of the rooms.

 ###### Future Analysis/Next Steps
 - keep room type constant to look at trends between location vs. price and popularity vs. price
 - create more appropriate displays to further determine trends such as the graph displayed below
 <img src="https://github.com/deepster/Airbnb-data-in-Tableau/blob/main/images/Trellis_graph.jpg" width="700" height="475"/>



