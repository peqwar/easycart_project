# Case Study of EasyCart, Inc. 🛒🛍️
**Author:** Andrés Guerrero <br />
**Email:** peqwar@gmail.com <br />
**LinkedIn:** <a href="https://www.linkedin.com/in/peqwar/" target="_blank">https://www.linkedin.com/in/peqwar/</a>

**Published:** April 22, 2024

## Introduction

EasyCart, Inc. is an e-commerce company based in Quito, Ecuador. It offers an online platform where users can purchase a variety of products, from technology to home and fashion items. The company has stood out for its focus on customer experience and convenience in the online purchasing process.

With just 4 years since its creation, EasyCart has managed to revolutionize the online shopping experience for thousands of its users and ensure sustainable growth year after year. By January 2025, the company aims to reach $7 million in sales, for which investments have been made in technology and the expansion of its distribution and logistics network. 

## Problem Statement

To understand the company's status on its path towards the goal, an analysis of transactional and operational data from the company has been requested, with specific requirements from each area of the company:

- **Marketing**: They want a clear understanding of our customers based on their transactional behavior. 

- **Operations**: They want to know how demand is moving in each of the retailers to be able to plan team schedules and take actions to avoid a clash between demand and capacity. Additionally, they want to understand the rate of delivered or cancelled orders and the different incidents they are experiencing at an operational level.

- **C level**: Finally, from the company's leaders and managers, they want to know if, with the sales pace obtained to date, they will be able to reach the sales target by the end of the month.

## Dataset info

| Column              | Description                                                | Data Type     |
|---------------------|------------------------------------------------------------|---------------|
| `order_id`          | Unique transaction identifier.                              | int64         |
| `order_status`      | Current status of the order.                               | object        |
| `order_date`        | Date the order was generated.                              | datetime64[ns]|
| `estimated_delivery_date` | Scheduled delivery date.                                 | datetime64[ns]|
| `delivery_date`     | Date the order was delivered.                              | datetime64[ns]|
| `client_id`         | Unique identifier of the client.                           | int64         |
| `final_items`       | Number of final items delivered to the client.             | int64         |
| `initial_items`     | Number of items initially demanded by the client.           | int64         |
| `final_income`      | Final amount charged to the client.                        | float64       |
| `initial_income`    | Initial amount demanded by the client.                     | float64       |
| `city`              | City associated with the order.                            | object        |
| `retailer`          | Type of retailer associated with the order.                | object        |

## Case Study
[Case Study - EasyCart Project Notebook](./easycart_project.ipynb)