# Data Wrangling on Santa Clara County Airbnb Listing Data
## Aims
-	Compare the prices in the listings (2020) and the ones in the calendar (2021) 
-	What drives the price changes? Could the number of reviews in recent years (i.e. 2019) be one of the reasons that the host change the price in the following year (2021)? Or the reviews scores have something to do with the price changes as well? 

## Data
http://insideairbnb.com/get-the-data.html
 - `listings` (7891×106), contains the detailed information of the listings. Major attributes include hosts’ information, house/room location, price, availability and ratings.
 - `reviews` (235843×6), mainly includes listing_id, guests’ information and their detailed reviews. 
 - `calendar` (2880215×7), provides booking information for the next year, including variables: listing_id, date, available, and price.

