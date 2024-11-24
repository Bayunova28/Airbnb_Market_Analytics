## Airbnb Market Analytics
<img src="https://github.com/Bayunova28/Airbnb_Market_Analytics/blob/main/image-airbnb.jpg" height="600" width="1100">
<p align="justify"><b>Airbnb</b> is a community marketplace where guests can book living accommodations from a list of verified hosts. Membership to the site is completely free and there is no cost to post a listing. Using a targeted user interface designed to narrow down traveling preferences, Airbnb offers an attractive, cost-saving alternative to traditional hotel bookings and vacation home rentals. Upon finding a desired listing, guests are prompted to sign up for membership, which provides access to contact the host directly as well as provide payment information for a request. For all the lone wanderers or people just searching for a “home away from home,” Airbnb has created the perfect solution for renters and providers worldwide. Since its inception in 2008, Airbnb started an innovative community marketplace for people to list, discover, and book a wide variety of accommodations around the world. Airbnb has pioneered a new industry of “collaborative consumption” and peer-to-peer accommodation rentals, which leaves room for the company’s potential growth and worldwide adoption</p>

## Data Attribute
```
root
 |-- id: string (nullable = true)
 |-- name: string (nullable = true)
 |-- host_id: string (nullable = true)
 |-- host_name: string (nullable = true)
 |-- neighbourhood_group: string (nullable = true)
 |-- neighbourhood: string (nullable = true)
 |-- latitude: string (nullable = true)
 |-- longitude: string (nullable = true)
 |-- room_type: string (nullable = true)
 |-- price: string (nullable = true)
 |-- minimum_nights: string (nullable = true)
 |-- number_of_reviews: string (nullable = true)
 |-- last_review: string (nullable = true)
 |-- reviews_per_month: string (nullable = true)
 |-- calculated_host_listings_count: string (nullable = true)
 |-- availability_365: integer (nullable = true)
```

## Inspiration
* How many avg. price by room type
* How many total reviews by room type
* How many avg. price by neighbourhood group & room type
* How many total reviews by neighbourhood group & room type
* How many total reviews by last review year & room type

## References
* [The evolution of Airbnb research: A systematic literature review using structural topic modeling](https://www.sciencedirect.com/science/article/pii/S2405844023042986)
* [Analyzing big AirBnB data using Spark](https://bjornkhansen95.medium.com/spark-for-big-data-af1cf5318e1e)
* [New York City Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)
