**Problem Statement**

The task in this project was to predict the number of food orders for an online food delivery business at each of their branches on a particular week in the future.
Solving this problem is useful for planning just-in-time procurement of ingredients to improve supply chain management, and reduce wastage and costs.

## About the Dataset
Here’s the training data we were asked to work with.

Column	Description
id	 Unique transaction id
week	 Week number; training data had weeks 1 through 145
center_id	 Unique identifier for the branch of the online food delivery business
meal_id	Unique identifier for the meal
checkout_price	Price of the meal after discounts, coupons, etc
base_price	Base price of the meal
emailer_for_promotion	Boolean indicating whether the meal was promoted via email
homepage_featured	Boolean indicating whether the meal was featured on the website’s homepage
num_orders	The target (or dependent) variable we were asked to predict


There was also the following information about the branch of the food delivery business.

Column	Description
center_id	Unique identifier for the branch of the online food delivery business
city_code	Unique identifier for the city in which the branch operates
region_code	Unique identifier for the region in which the branch operates
center_type	Categorical variable for the branch type
op_area	Operating area of the branch


Then, there was some information about the meal’s themselves.

Column	Description
meal_id	Unique identifier for the meal
category	The meal category
cuisine	The meal cuisine (categorical variable)


