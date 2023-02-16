# FOODCOUVER: An exploratory data analysis on the food scene in Vancouver, BC, Canada 

## Table of Contents
* [Background](#background)
* [Findings](#findings)
  * [Summary Statistics](#summary-statistics)
  * [Categorical Statistics](#categorical-statistics)
  * [Geographic Statistics](#geographic-statistics)
* [Usage](#usage)
* [Legality](#legality)

## Background
 A person interested in the food culture of a specific location or city may want to gain a deeper understanding of the experience that both locals and tourists have when dining out. The goal may be to validate or challenge existing notions about the best places to eat or to uncover new insights about the food scene in the area. This could involve conducting research and data analysis to gain a better understanding of the dining experience and preferences in the area.


* Is this an expensive city to eat in? 


* On average, where are the highest rated restaurants located? 


* Which genre of cuisine is the most common to find? 


In this exploratory data analysis, I found out answers to these questions and more with my trusty friend; data.

## Findings

### Summary Statistics
![summarystatistics](https://user-images.githubusercontent.com/50093891/79916155-19146700-83dd-11ea-8559-ab08a5d642e9.png)
Here are the general summary statistics for restaurants in Vancouver, BC, according to Yelp data. As we can see in the above graphs, most restaurants have < 500 reviews, most are within a rating of 3.0 - 4.0, and majority are given a double money sign in terms of price ($$).

### Categorical Statistics
![category](https://user-images.githubusercontent.com/50093891/80263801-b2928180-8646-11ea-9e51-1040f3e7592e.png)
Next, we will look at categorical data of the same properties. The graphs above show the top 5 for each property, but you will be able to see more results in the main project notebook. This data suggests that most categories are pretty close in terms of average price, rating, and review count. We have many chinese restaurants in Vancouver, BC.

### Geographic Statistics
Lastly, we have data for the areas of Vancouver, BC for average rating, restaurant density, average price, and review count.

**Average Rating**
![average_rating](https://user-images.githubusercontent.com/50093891/79916236-3cd7ad00-83dd-11ea-8524-81051448bf93.png)<br />
It seems that the average ratings are distributed throughout Vancouver, with Victoria-Fraserview being the worst area to go for food.


**Restaurant Density**
![restaurant_density](https://user-images.githubusercontent.com/50093891/79916255-46611500-83dd-11ea-8d58-d0f3a522621b.png)<br />
It's no surprise that downtown Vancouver has the most restaurants, with the numbers decreasing as the city becomes more residential.


**Average Price**
![average_price](https://user-images.githubusercontent.com/50093891/79916303-5842b800-83dd-11ea-837f-d5e70073cd59.png)<br />
Unfortunately, there was a large amount of data missing (about 25% of total data) for price of restaurants. There isn't enough data in this field to make a hypothesis with. However, it surprises me that the price data for the most dense area of restaurants is missing, which may be an indicator that something is wrong with the investigation.


**Review Count**
![review_count](https://user-images.githubusercontent.com/50093891/79916348-6b558800-83dd-11ea-9438-d92d6b1fc351.png)<br />
It's pretty surprising to see that the area with the highest restaurant reviews are located more in the western side of Vancouver, given that the highest density of restaurants is downtown. The average ratings for that area are not particularly high, either. A possibility is that the western side of Vancouver has a particularly committed customer base, or Yelp is popular within that community.


## Usage

This project is best viewed in a notebook viewer, which can be accessed [here](https://nbviewer.jupyter.org/github/justinmlam/foodcouver/blob/master/foodcouver.ipynb). In this notebook, you will find a walk through of the work done and the respective code.

