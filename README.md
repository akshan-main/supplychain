# A project performing analysis on a supply chain dataset

Link to the dataset
[here](https://data.mendeley.com/datasets/8gx2fvg2k6/5)

# Customer Segment Distribution- Bar Graph
There are 3 customer segments- `Home Office`, `Corporate`, and `Consumer`. The total number of instances of each in the dataset is seen in the bar graph below.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/Customer_segment_count.jpg)

# Customer Segment Distribution- Pie Chart
There are 3 customer segments- `Home Office`, `Corporate`, and `Consumer`. The distribution of each segment in the dataset can be seen in the pie graph below.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/Customer_segment_distribution.jpg)

# Customer Segment- Sales Distribution
There are 3 customer segments- `Home Office`, `Corporate`, and `Consumer`. The distribution is according to `total sales` made possible by each `customer segment`.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/Sales_distribution_customer_segment.jpg)

The pie chart below describes the distribution of `total sales` through different `customer segments`.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/sales_distribution_by_customer_segment.jpeg)

# Distribution among Markets
There are 5 different markets. The total number of instances of each in the dataset is seen in the bar graph below.

`Europe` and `Latin America` are the most observable in the dataset whereas `Pacific Asia`, `Africa` and `USCA (United States & Canada)` arent comparably much.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/market_counts.jpeg)

The distribution for the same is seen in the pie chart

![Image URL](https://github.com/akshan-main/supplychain/blob/main/market_counts_pie.jpeg)

# Product Popularity in Different Markets
There are 5 different markets. The top 6 products from each market can be seen on the graph along with the count of each product within the market.

Same 6 products dominate all markets. The ordinal position of the top 4 products remains the same across markets. There is a difference in order only in the 5th and 6th popular product

` Field & Stream Sportsman 16 Gun Fire Safe ` is the most popular product.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/top_products_by_market.jpeg)

# Delivery Status- Distribution
There are 4 different delivery statuses and the total number of instances of each in the dataset is seen in the bar graph below.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/delivery_status_distribution.jpeg%20.png)

There are 4 different delivery statuses and 4 different shipping modes. The distribution of delivery status filtered by its shipping mode can be seen on the below cross-tabulation chart. 

![Image URL](https://github.com/akshan-main/supplychain/blob/main/delivery_status_by_shipping_mode.jpeg)

A significant portion of deliveries are late, particularly in `First Class` and `Second Class` shipping modes. Late deliveries are the most common delivery status, especially in `First Class` shipping mode. `Standard Class` shows a more balanced distribution across different delivery statuses. It's likely that the customers choosing `First Class` will be disappointed.


# Sales Trends
The graph below denotes the `sales trend` monthly. The lowest number of sales were recorded towards start of 2018 for all products combined.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/sales_trend.jpeg)

The graph below denotes the `sales trend` monthly for ` Nike Men's Free 5.0+ Running Shoe `. 

The highest amount of sales was recorded for the product during May 2015 and the lowest were towards start of 2018. The highest ever recorded sale of the product is just below 140000.

The latest recorded sale of this product was in October 2017

![Image URL](https://github.com/akshan-main/supplychain/blob/main/sales_trend_nike5.0.jpeg)


In both cases, the sales are heavily fluctuating.

# Market and Customer Segment Interaction
This is a graph plotted with the help of networkx library. The nodes represent `customer segments` and `markets`. Their color and size are based on their degree.

The `degree of a node` is the total number of nodes connected to a given node. It can also be defined as the number of edges linked to a node.

The higher the `degree of a node`, the bigger the size and the darker the color.

The edges represent the weight, which here is the total amount of sales that have taken place between the two nodes(the `Market` node and the `Customer Segment` node).

The `Sales` as implied from the dataset is `Product Price` times `Quantity`.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/Market_customer_segment_interaction.jpeg)


# Shipping Mode Preferences
Below is the pie chart of the distribution of shipping modes preferred by customers.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/shipping_mode_distribution.jpeg)

Most people prefer Standard Class


# Orders from Each Category
Here, total orders from each category are present. The subsequent graph also provides information on the number of different product orders based on their shipping mode.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/number_of_orders_product_categories.jpeg)


# Sales Performance

The below graph denotes sales performance for each product category. Computer and related products seem to be the most profitable.


![Image URL](https://github.com/akshan-main/supplychain/blob/main/sales_performance.jpeg)


# Cities with Most Sales

The visualization helps identify which cities contribute the most to the overall sales, the cities can then be focused on for further business strategy planning and analysis.


![Image URL](https://github.com/akshan-main/supplychain/blob/main/cities_with_highest_sales.jpeg)


# Product Cancellation Analysis 
The graph helps analyze which product categories are prone to most order cancellations. Products falling under these categories can be set for later dispatch.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/product_cancellation.jpeg)


# Time Taken for Delivery based on Shipping Mode 
Average shipping time for each shipping mode is denoted here

![Image URL](https://github.com/akshan-main/supplychain/blob/main/shipping_performance.jpeg)


# Prediction Model 

Also made it possible to Predict for new values if the order has a late delivery risk using model trained on the dataset, using Random Forest Classifier.
It has accuracy of about 98%















