# Data_Cleansing

This project applies data wrangling techniques to a retailer's data set of online orders. These techniques include determining and removing syntactical as well as semantic anomalies, removing outliers and imputing missing values using basic machine learning. Most of the wrangling steps are completed using the Python Pandas library.

The dataset in use contains transactional retail data from an online electronics store (DigiCO) located in Melbourne, Australia. 
It has 12 columns, rangeing from:

- order_id 
- customer_id
- date 
- nearest_warehouse
- customer_lat 
- customer_long 
- coupon_discount
- delivery_charges 
- order_total
- season
- shopping_cart
- order_price
- distance_to_nearest_warehouse
- is_expedited_delivery 
- latest_customer_review 
- is_happy_customer

This order data is contained in three csv files:

- dirty_data.csv : carries rows with at most one anomaly in it.
- missing_data.csv : contains rows with one or more missing values.
- outlier_data.csv : contains data with outliers in them.
