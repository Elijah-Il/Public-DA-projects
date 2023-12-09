# E-commerce project

## Searching for useful data insides for e-commerce shop - from basic slicing and time series analysis, to retention rate heat map and RFM segmentation. Conclusions include several potential growth spots.

Full datasets describtion:<br><br>
**olist_customers_datase.csv** - table with unique user IDs<br>
customer_id - custom user ID<br>
customer_unique_id - unique user ID<br>
customer_zip_code_prefix - user zip code<br>
customer_city - users delivery city<br>
customer_state - user's delivery state/region<br><br>

**olist_orders_dataset.csv**<br>
order_id - unique order identifier (receipt number)<br>
customer_id - custom user ID<br>
order_status - order status<br>
order_purchase_timestamp - time of order creation<br>
order_approved_at - order payment confirmation time<br>
order_delivered_carrier_date - time of order transfer to the logistics service<br>
order_delivered_customer_date - order delivery time<br>
order_estimated_delivery_date - promised delivery date<br><br>

**olist_order_items_dataset.csv**<br>
order_id - unique order identifier (receipt number)<br>
order_item_id - product identifier within one order<br>
product_id - product ID<br>
seller_id - ID of the manufacturer of the product<br>
shipping_limit_date - maximum delivery date by the seller for transferring the order to the logistics partner<br>
price - product unit price<br>
freight_value - product weight<br>