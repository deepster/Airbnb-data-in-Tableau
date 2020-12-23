# Tableau-Test-Run
Experimenting using Tableau for exploratory data analysis (EDA)
## About the Dataset
This dataset, "New York City Airbnb Open Data", was taken from kaggle.com. The features from the dataset that were the main focus during EDA were Price, Location, Room Type, Number of Reviews, Availability, and Minimum Nights.

###### Breakdown of each Feature
| Feature                | Description/Notes |
| -------------          | -------------     |
| Price                  | Price of room listed                                  |
| Location               | Location of room listed                               |
| Room Type              | Type of room being listed <br> (private/single room, shared room, entire house)     |
| Number of Reviews      | Number of reviews room listed has <br> I used this as a rough estimate of populatrity <br> (i.e. more reviews a room has = more popular)        |
| Availability           | How many days a year the room is available to rent    |
| Minimum Nights         | Minimum nights a person must stay in order to rent room <br> (i.e may only rent room A if you are will to rent for 3 or more days   |

## Goals of EDA
To understand the makeup of the Airbnb market in NYC. 

###### Questions asked during EDA

1. How do renting prices compare in different locations in NYC?
2. Which locations are more popular to stay at and how does this effect the price?
3. What are some features that contribute to the price of a room?

## Breakdown of Tableau Dashboard
<img src="https://github.com/deepster/Tableau-Test-Run/blob/main/images/dashboard_overview.jpg" width="700" height="475"/>

###### Overview of Dashboard
Each graph sector is designed to provide some insights into the questions posed above:

1. The NYC map displays the location of each room along with its price in comparison to others
2. (Bottom Left) Displays the average avaliability, minimum night requirement, and number of reviews of the points selected
3. (Bottom Middle) Displays the number of each type of room in the selected data
4. (Bottom Right) Displays the average price breakdown for each room type present in the selected data
5. (Top Left) The three filters help filter by Price, Borough, Number of Reviews 

###### How do renting prices compare in different locations in NYC?


