# RFM Customer Segmentation

## Project Overview

This project focuses on performing **RFM (Recency, Frequency, Monetary)** analysis for **FLO**, Turkey's leading footwear retailer. The goal is to segment customers based on their purchase behaviors using RFM metrics, helping FLO develop targeted marketing strategies.

## Business Problem

FLO seeks to enhance its marketing efforts by understanding customer value and behavior. Using RFM analysis, customers will be segmented based on how recently and frequently they made purchases, and the total monetary value they have contributed to the company. This analysis will enable FLO to create personalized marketing campaigns.

## Dataset

The dataset includes shopping behaviors of customers who made purchases in 2020-2021 via OmniChannel (online and offline).

### Key Features:
- **master_id**: Unique customer identifier
- **order_channel**: Shopping channel (Android, iOS, Desktop, Mobile, Offline)
- **last_order_date**: Date of the customer's last purchase
- **order_num_total_ever_online**: Total number of online purchases
- **order_num_total_ever_offline**: Total number of offline purchases
- **customer_value_total_ever_online**: Total amount spent online
- **customer_value_total_ever_offline**: Total amount spent offline

## RFM Metrics

1. **Recency**: How recently a customer made a purchase.
2. **Frequency**: How often a customer makes a purchase.
3. **Monetary**: How much money the customer has spent.

## Methods Used

- **RFM Scoring**: Customers are scored on each RFM metric (Recency, Frequency, and Monetary) and grouped into segments for analysis.
- **Customer Segmentation**: Based on RFM scores, customers are classified into various segments like VIP, High Potential, At Risk, etc.

## Objective

The primary goal of this analysis is to segment customers and provide FLO with actionable insights to create effective marketing campaigns tailored to each customer group. By focusing on customer lifetime value, FLO can improve retention and optimize its marketing strategy.

## Conclusion

RFM analysis helps FLO identify high-value customers, create targeted marketing strategies, and enhance customer loyalty.

