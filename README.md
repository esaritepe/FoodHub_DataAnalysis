# FoodHub Data Analysis

<p align="center">
  <img src="https://assets.rebelmouse.io/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpbWFnZSI6Imh0dHBzOi8vYXNzZXRzLnJibC5tcy8yMjg5OTY5NS9vcmlnaW4uanBnIiwiZXhwaXJlc19hdCI6MTc1MTMyMzk3M30.LVgqjpTVjtEZQ_ZZT2ZAJs47PFU_C3RXw53tsjidr08/img.jpg?width=1200&height=630&coordinates=107%2C0%2C107%2C0"/>
</p>

Background
---------------
* The number of restaurants in New York City is increasing by the day, being used by students and professionals due to their hectic lifestyles.
* A food aggregator company called FoodHub is offering access to multiple restaurants through their delivery app. This app receives orders from customers and assigns a delivery person from FoodHub to pick up the order from the restaurant. Once the food is delivered, customers can rate the order in the app.
* FoodHub earns money by collecting fixed margins from the delivery orders.

Project Goal
--------------
* FoodHub has stored data of different orders from registered customers in their online portal. The company wants to analyze the data to better understand the demand of different restaurants. This will help the company enhance the customer experience in the app.
* As a Data Scientist on the team, I need to perform data analysis to answer key questions that will help the company improve its business.

File Structure
----------------
* An ipynb file that contains Python code used to load the dataset and run exploratory data analysis (EDA). This file also includes several charts and data visualizations used for univariate and multivariate analyses. Markdown comments are also included which detail observations of the results and business recommendations for FoodHub.
* A CSV file that contains data on order ID, customer ID, restaurant name, cuisine type, cost of order, day of the week (weekday or weekend), customer rating, food preparation time, and delivery time.

Results
---------
The Jupyter Notebook file contains several data visualizations used for this project. Here are some of the most important charts:

<p align="center">
  <img src="https://github.com/esaritepe/FoodHub_DataAnalysis/blob/main/screenshots/Most%20Popular%20Cuisines.png"/>
</p>

* According to the count plot above, American is the most popular cuisine type. Japanese, Italian, and Chinese are also popular cuisine types among FoodHub users.

<p align="center">
  <img src="https://github.com/esaritepe/FoodHub_DataAnalysis/blob/main/screenshots/Delivery%20Time%20vs%20Rating.png"/>
</p>

* Based on the point plot above, orders with 3/5 ratings have higher delivery times than the other rating types. The extended delivery time could be a factor for the 3/5 ratings. Orders with 4/5 ratings have the lowest delivery times.
* It's important to note that orders with 5/5 ratings have reasonable delivery times, almost on par with the delivery time for orders with no ratings.

<p align="center">
  <img src="https://github.com/esaritepe/FoodHub_DataAnalysis/blob/main/screenshots/Popular%20Restaurants%20by%20Average%20Rating.png"/>
</p>

* After filtering the data, the restaurants that meet the criteria of having more than 50 ratings and an average rating greater than 4 are The Meatball Shop, Blue Ribbon Fried Chicken, Shake Shack, and Blue Ribbon Sushi.
* The Meatball Shop is the highest-ranked restaurant name with an average rating of 4.511905. The lowest-ranked restaurant name of the four is Blue Ribbon Sushi, with an average rating of 4.219178.

Conclusions 
------------
* Four restaurant names stand out in popularity, both in the number of ratings and average ratings. Those four restaurants are Shake Shack, The Meatball Shop, Blue Ribbon Fried Chicken, and Blue Ribbon Sushi.
* American cuisine is the most popular among the users of FoodHub. However, other cuisine types are also popular among FoodHub users like Japanese, Italian, and Chinese.
* The mean delivery time on weekdays is greater than the mean delivery time on weekends at a 5% significance level. This makes sense as there is likely a higher demand for food delivery during the weekdays. The amount of people working from home and street traffic in New York are likely factors.

Recommendations
----------------
* The app algorithm should be modified to place the most in-demand restaurants at the top of the app (Shake Shack, The Meatball Shop, Blue Ribbon Fried Chicken, and Blue Ribbon Sushi). That way, the customer can access the restaurant they want much more quickly and make an order.
* Likewise, restaurants with more 5-star ratings should be promoted more in the FoodHub algorithm. Orders with 5-star ratings have reasonable total delivery times and the cost of the order is generally higher. This change can achieve improvements in both customer satisfaction and company net revenue.
* The four most popular cuisine types (American, Japanese, Italian, and Chinese) should also be promoted more in the FoodHub app. This will enhance the customer experience by giving more exposure to high-demand cuisine types, possibly leading to more user spending.
