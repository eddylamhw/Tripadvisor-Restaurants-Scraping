# Tripadvisor-Restaurants-Scraping

## 1. Business Question
This project aims to scrape data of restaurants in Hong Kong from Tripadvisor, and determine what kind of restaurants are more popular and highly ranked.


## 2. Data Collection
The restaurants data are scraped from the website of Tripadvisor (https://www.tripadvisor.com/Restaurants-g294217-Hong_Kong.html) using Beautiful Soup and Selenium. In total, there are 13237 restaurants. The restaurants' name, restaurant type, price range,	rank,	rating, total number of reviews, and two customer reviews are also scraped from the website.
<img src = "https://github.com/eddylamhw/Tripadvisor-Restaurants-Scraping/blob/main/images/Screenshot%202021-01-29%20at%204.54.13%20PM.png" width= "800">

## 3. EDA
### Missing Values
<img src = "https://github.com/eddylamhw/Tripadvisor-Restaurants-Scraping/blob/main/images/Screenshot%202021-01-29%20at%204.59.22%20PM.png" width = "500">
There are quite a lot of missing values, especially for rating, total number of reviews, and customer reviews of lower ranked restaurants, which is understandable as these restaurants are less well-known, or are fast food chain restaurants, that no one would leave a rating, or review to these restaurants on Tripadvisor. Also, there are a lot of restaurants having missing values in the "safety" column, which actually indicates that most of them are not fully taking safety measures against Covid-19. For the "genre" column, some restaurants might have no particular food type or restaurant type and thus have missing values.

### Restaurants Taking Safety Measures
<img src = "https://github.com/eddylamhw/Tripadvisor-Restaurants-Scraping/blob/main/images/Screenshot%202021-01-29%20at%205.13.05%20PM.png" width = "500">
According to the Tripadvisor's website, there is only 0.1% of restaurants fully taking safety measures against Covid-19.

### The 10 Most Common Food/Restaurant Types
<img src = "https://github.com/eddylamhw/Tripadvisor-Restaurants-Scraping/blob/main/images/Screenshot%202021-01-29%20at%205.13.26%20PM.png" width = "500">
The three most common food/restaurant types are Chinese (29.3%), Asian (21.6%), and Japanese (14.3%). These are followed by Cafe, Italian, Bar, Seafood, European, Fast Food, American.

### Rating 
<img src = "https://github.com/eddylamhw/Tripadvisor-Restaurants-Scraping/blob/main/images/Screenshot%202021-01-29%20at%205.13.36%20PM.png" width = "500">
The restaurants most commonly get a rating of 4.0 (44.4%), 3.5 (19.9%), and 4.5 (19.8%). Only 6.9% get a rating of 5.0, and 0.1% get a rating of 1.0.

### Total Review
<img src = "https://github.com/eddylamhw/TripAdvisor-Restaurants-Scraping/blob/main/images/Screenshot%202021-01-29%20at%205.13.44%20PM.png" width = "500">
From the distribution plot, most restaurants have a total number of reviews between 0 to 500.

### The Restaurant with the Highest Number of Reviews
<img src = "https://github.com/eddylamhw/Tripadvisor-Restaurants-Scraping/blob/main/images/Screenshot%202021-01-29%20at%205.16.11%20PM.png" width = "1000">

### Price
<img src = "https://github.com/eddylamhw/Tripadvisor-Restaurants-Scraping/blob/main/images/Screenshot%202021-01-29%20at%205.13.53%20PM.png" width = "500">
Among the restaurants that have a price range indicated, most of them are in the "medium" price range, followed by "cheap" and then "expensive".

### Correlation between Rating, Total Review, and Price
<img src = "https://github.com/eddylamhw/Tripadvisor-Restaurants-Scraping/blob/main/images/Screenshot%202021-01-29%20at%205.15.45%20PM.png" width = "500">
<img src = "https://github.com/eddylamhw/Tripadvisor-Restaurants-Scraping/blob/main/images/Screenshot%202021-01-29%20at%205.15.57%20PM.png" width = "500">
It can be seen from the heatmap and pairplot, that there are only weak correlations between rating, total review, and price.

### The 20 Most Common Food Types among the 1000 Highest Ranking Restaurants
<img src = "https://github.com/eddylamhw/Tripadvisor-Restaurants-Scraping/blob/main/images/Screenshot%202021-01-29%20at%205.16.05%20PM.png" width = "500">
It can be seen that the most common food/restaurant types among the 1000 highest ranking restaurants are quite similar to that among all restaurants.

## 4. Self-Created Ranking List, Ordered by Total Review, and then by Rating
<img src = "https://github.com/eddylamhw/Tripadvisor-Restaurants-Scraping/blob/main/images/Screenshot%202021-01-29%20at%205.16.21%20PM.png" width = "1000">

# References
Tripadvisor\
https://www.tripadvisor.com/Restaurants-g294217-Hong_Kong.html








