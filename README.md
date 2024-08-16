# A project performing analysis on a supply chain dataset

# Customer Segment Distribution- Bar Graph
There are 3 customer segments- `Home Office`, `Corporate`, and `Consumer`. The total number of instances of each in the dataset is seen in the bar graph below.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/customer_segment_count.jpeg)

# Customer Segment Distribution- Pie Chart
There are 3 customer segments- `Home Office`, `Corporate`, and `Consumer`. The distribution of each segment in the dataset can be seen in the pie graph below.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/customer_segment_distribution.jpeg)

# Customer Segment- Sales Distribution
There are 3 customer segments- `Home Office`, `Corporate`, and `Consumer`. The distribution is according to `total sales` made possible by each `customer segment`.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/sales_distribution_customer_segement.jpeg)

The pie chart below describes the distribution of `total sales` through different `customer segments`.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/Sales_distribution_by_customer_segment_pie.jpeg)

# Market Analysis- Distribution among markets
There are 5 different markets. The total number of instances of each in the dataset is seen in the bar graph below.

`Europe` and `Pacific Asia` are the top-performing markets in terms of `sales`, `while Latin America`, `Africa` and `USCA (United States & Canada)` lag behind.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/market_counts.jpeg)

The distribution for the same is seen in the pie chart

![Image URL](https://github.com/akshan-main/supplychain/blob/main/market_count_pie.jpeg)

# Top products- Market based
There are 5 different markets. The top 6 products from each market can be seen on the graph along with the count of each product within the market.

The products ` Perfect Fitness Perfect Rip Deck `, ` Nike Men's Free 5.0+ Running Shoe `,` Nike Men's Dri-FIT Victory Golf Polo `,` Field & Stream Sportsman 16 Gun Fire Safe ` are among the top 6 products sold in all markets.

`Smart Watch` is the highest sold of all items in a particular market ie; it's the highest sold item in the `Pacific Asia` market but it is not among the top 6 sold products in any of the other 5 markets.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/top_products_by_market.jpeg)

# Delivery Status- Distribution
There are 4 different delivery statuses and the total number of instances of each in the dataset is seen in the bar graph below.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/delivery_status_distribution.jpeg)

There are 4 different delivery statuses and 4 different shipping modes. The distribution of delivery status filtered by its shipping mode can be seen on the below cross-tabulation chart. 

![Image URL](https://github.com/akshan-main/supplychain/blob/main/delivery_status_by_shipping_mode.jpeg)

A significant portion of deliveries are late, particularly in `First Class` and `Second Class` shipping modes. Late deliveries are the most common delivery status, especially in `First Class` shipping mode. `Standard Class` shows a more balanced distribution across different delivery statuses. It's likely that the customers choosing `First Class` will be disappointed.


# Sales Trends
The graph below denotes the `sales trend` monthly. The lowest number of sales was recorded in November 2017 for all products combined.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/sales_trend.png)

The graph below denotes the `sales trend` monthly for ` Nike Men's Free 5.0+ Running Shoe `. 

The highest amount of sales was recorded for the product during July 2017 and the lowest was during February 2015. The highest ever recorded sale of the product is just over 5000.

The latest recorded sale of this product was in September 2017

![Image URL](https://github.com/akshan-main/supplychain/blob/main/sales_trend_nike5.0.png)


In both cases, the sales are heavily fluctuating.

# Market and Customer Segment Interaction
This is a graph plotted with the help of networkx library. The nodes represent `customer segments` and `markets`. Their color and size are based on their degree.

The `degree of a node` is the total number of nodes connected to a given node. It can also be defined as the number of edges linked to a node.

The higher the `degree of a node`, the bigger the size and the darker the color.

The edges represent the weight, which here is the total amount of sales that have taken place between the two nodes(the `Market` node and the `Customer Segment` node). The edge length is directly proportional to the total sales.

The `Sales` as implied from the dataset is `Product Price` times `Quantity`.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/Market_customer_segment_interaction.png)
