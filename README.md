
# BG-NBD- Gamma-Gamma and CLTV Prediction

1. Introduction about Customer Lifetime Value
2. Business Problem
3. Dataset Story and Variables
4. Tasks


### Introduction
Customer Lifetime Value (CLTV) is the estimated total value of a customer's contribution to a business in the future. This concept helps a business understand the value of its customers and can help the business retain them by providing better service.

CLTV is a metric used to measure the value that a customer brings to a business. This metric estimates the value of a customer to a business by taking into account all the transactions the customer has made with the business and the profit they have generated as a result. This estimate is based on customer behaviors, business performance, and other factors.

Calculating customer lifetime value can help a business guide its customer acquisition strategies, customer loyalty programs, product or service pricing, and other marketing activities. A good CLTV can increase a business's profitability and enable sustainable growth.



### Business Problem

The FLO company's CRM department want to determine roadmap for sales and marketing activities. 
This project aim to making customer lifetime value.


### Dataset Story

The dataset consisted of information from past Omni Channel habits (customers who shop online and offline) at the last purchase in 2020-21

* master_id: Unique client number
* order_channel : Which channel of the shopping platform is used (Android, ios, Desktop, Mobile, Offline)
* last_order_channel : The channel where the last purchase was made
* first_order_date : The date of the customer's first purchase
* last_order_date : The date of the last purchase made by the customer
* last_order_date_online : The date of the last purchase made by the customer on the online platform
* last_order_date_offline : The date of the last purchase made by the customer on the offline platform
* order_num_total_ever_online : The total number of purchases made by the customer on the online platform
* order_num_total_ever_offline : Total number of purchases made by the customer offline
* customer_value_total_ever_offline : The total price paid by the customer for offline purchases
* customer_value_total_ever_online : The total price paid by the customer for their online shopping
* interested_in_categories_12 : List of categories the customer has purchased from in the last 12 months]()

### Tasks
* Task 1:Preparing the data
* Task 2:Creating CLTV Data Structure
* Task 3:Establishing the bg/nbd,gamma-gamma model and calculating Cltv
* Task 4: Creating segment by Cltv
* Task 5: Functionalizing the whole process.