# CLTV Prediction with BG-NBD and Gamma-Gamma using FLO's Dataset
The anticipated total worth of a customer's future contributions to a firm is known as customer lifetime value (CLTV). With the aid of this idea, a company may better grasp the worth of its clients and keep them by offering better services.CLTV is a metric used to measure the value that a customer brings to a business. A company's customer acquisition strategy, customer loyalty programs, product or service pricing can all be guided by the customer lifetime value calculation. A good CLTV may boost a company's profitability.

# FLO
Flo is a big Turkish fashion retail company, which has been operating since 2010. It offers various products such as shoes, bags, and clothes for both men and women. Flo has an extensive network of stores across Turkey and has recently expanded its operations to other countries.

![flo](https://user-images.githubusercontent.com/126112467/227967873-481e7bf3-b4f0-4aa7-a6ea-daff872a2de7.png)

# Business Problem
FLO aims to divide its customer base into segments and devise marketing strategies tailored to each of these segments. To achieve this, customer behaviors will be analyzed and used to create clusters of customers with similar behaviors.

# Story of Dataset
The dataset consists of information obtained from the past shopping behaviors of customers who made their last purchases as OmniChannel (both online and offline shopper) in 2020 - 2021.
- master_id: Unique customer number
- order_channel : Which channel of the shopping platform is used (Android, ios, Desktop, Mobile, Offline)
- last_order_channel : The channel where the most recent purchase was made
- first_order_date : Date of the customer's first purchase
- last_order_date : Customer's last purchase date
- last_order_date_online : The date of the last purchase made by the customer on the online platform
- last_order_date_offline : Last shopping date made by the customer on the offline platform
- order_num_total_ever_online : The total number of purchases made by the customer on the online platform
- order_num_total_ever_offline : Total number of purchases made by the customer offline
- customer_value_total_ever_offline : Total fee paid by the customer for offline purchases
- customer_value_total_ever_online : The total fee paid by the customer for their online shopping
- interested_in_categories_12 : List of categories the customer has shopped in the last 12 months
