# A project performing analysis on a supply chain dataset

# Customer Segment Distribution- Bar Graph
There are 3 customer segments- Home Office, Corporate, and Consumer. The total number of instances of each in the dataset is seen in the bar graph below.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/customer_segment_count.jpeg)

# Customer Segment Distribution- Pie Chart
There are 3 customer segments- Home Office, Corporate, and Consumer. The distribution of each segment in the dataset can be seen in the pie graph below.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/customer_segment_distribution.jpeg)

# Market Analysis- Distribution among markets
There are 5 different markets. The total number of instances of each in the dataset is seen in the bar graph below.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/market_counts.jpeg)

The distribution for the same is seen in the pie chart

![Image URL](https://github.com/akshan-main/supplychain/blob/main/market_count_pie.jpeg)

# Top products- Market based
There are 5 different markets. The top 5 products from each market can be seen on the graph along with the count of each product within the market.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/top_products_by_market.jpeg)

# Delivery Status- Distribution
There are 4 different delivery statuses and the total number of instances of each in the dataset is seen in the bar graph below.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/delivery_status_distribution.jpeg)

There are 4 different delivery statuses and 4 different shipping modes. The distribution of delivery status filtered by its shipping mode can be seen on the below cross-tabulation chart.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/delivery_status_by_shipping_mode.jpeg)

# Market and Customer Segment Interaction
This is a graph plotted with the help of networkx library. The nodes represent customer segments and markets. Their color and size are based on their degree.

The degree of a node is the total number of nodes connected to a given node. It can also be defined as the number of edges linked to a node.

The higher the degree of a node, the bigger the size and the darker the color.

The edges represent the weight, which here is the total amount of sales that have taken place between the two nodes( Market node and Customer Segment node).

The Sales as implied from the dataset is Product Price times Quantity.

![Image URL](https://github.com/akshan-main/supplychain/blob/main/Market_customer_segment_interaction.png)
