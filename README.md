# Late Versus On-Time Food Deliveries Analysis

## Content

## Business Understanding
In the food industry, delivery service plays critical role, serving  two sides of same coin alongsides sales.
Delivery performance indisputably has strong correlation with customer satisfaction rate.
Utilizing late versus on-time delivery  trend analysis, as well as two-factor and multi-factor  correlation, 
allows us to uncover specific conditions that lead to optimal high quality delivery performance.

## About The Dataset

#### Data Descriptions
This dataset incorporated  traffic levels, area, weather , hour, and days to analyze delivery times.
These factors drives analysis to dive in how they are associated with delivery performance.
Furthermore, the analysis aims to mitigate existing gaps to optimize delivery time.

#### Column Informations
1.	order_id  : ID of Order
2.	customer_id : ID  of Customer
3.	restaurant_id : ID of Restaurant
4.	driver_id : ID of Driver
5.	order_timestamp : Completed order date with time
6.	order_date : Order date
7.	order_hour : Hour of Order
8.	day_of_week : Days in a week
9.	is_weekend : Binary column , Indicating the days are (0 for weekdays , 1 for weekend)
10.	city : CITY A-D
11.	delivery_area : CITY A-D WITH AREA 1-10
12.	customer_age : Customer age
13.	customer_type : Consists of 3 types: new, regular, and premium
14.	restaurant_type : Consists of 6 categorys : Asian, Burger, Dessert, Healthy, Local, and Pizza
15.	restaurant_primary_category : Consists of 6 categories : Asian, Burger, Dessert, Healthy, Local, and Pizza
16.	restaurant_rating : Rating for restaurant
17.	items_count : Number of items
18.	subtotal: Total price before tax,service fee, delivery fee
19.	discount_percent : Discount of the sub total 
20.	tax_amount : Tax of subtotal
21.	service_fee : restaurant service fee
22.	delivery_fee : Delivery fee
23.	order_total : Total price after tax,service fee, delivery fee
24.	payment_method : Consists of 3 types : Cash, Credit card, Digital wallet
25.	tip_amount : Amount of tip from customers
26.	distance_km : Delivery distance in Kilometre
27.	weather : Consists of 4 types, Clean, Rain, Cloudy,and Storm
28.	traffic_level : Level 0f traffic consists of  high, low,and  medium
29.	delivery_partner_experience_months : How many months  the delivery partners experience
30.	delivery_partner_rating : Rating of the delivery partner
31.	restaurant_preparation_time_minutes : Time period that the restaurant has to prepare the menu for
32.	estimated_delivery_time_minutes : Time period that the delivery has estimated for
33.	actual_delivery_time_minutes : Actual time that delivery has taken for in minutes
34.	late_delivery : Binary column , Indicating  the late and On-time arrivals (0 for no late delivery , 1  for lateness)
35.	order_status : Order status that consists of completed and cancelled
36.	cancellation_reason : A reason for cancelled order
37.	customer_rating : Rating for customers 

[Back to content](https://github.com/ainunjry/Portfolio_2_Food_Deliveries/blob/main/README.md#content)


#### Data Sources


#### Tools

- Google-Colab
  [Download here ](https://github.com/ainunjry/Tools_Project-2_Delivery-Analysis/blob/main/Delivery.ipynb)
- XAMPP PhpMyAdmin - Data analysis
- Tableau - Visualization

#### Business Questions
1. What drives actual delivery time ?
2. What drives late deliveries ?
3. How accurate are delivery estimates ?
4. Which ones are the operational bottlenecks ?
5. How does delivery performance relate to customer experience ?

## Data Cleaning
####**Python Pandas























