# Quick Commerce Analytics Platform

## Problem Statement

Quick-commerce businesses such as Blinkit, Zepto, and Instamart rely on efficient delivery operations, inventory management, and customer satisfaction monitoring. Managing these operations manually becomes difficult as order volume increases. Businesses require a centralized analytics solution to monitor performance and make data-driven decisions.

## Objective

The objective of this project is to design and develop a complete analytics platform that provides visibility into revenue, delivery operations, inventory health, and customer satisfaction using MySQL and Power BI.

## Proposed Solution

A relational database was designed in MySQL to simulate a quick-commerce ecosystem operating across multiple dark stores in Coimbatore. Analytical SQL views were created to simplify reporting and dashboard development. Power BI dashboards were developed to provide operational and strategic insights for business stakeholders.

## Technologies Used

* MySQL
* SQL
* Power BI
* DAX

## Database Design

The database includes:

* Areas
* Customers
* Orders
* Order Items
* Products
* Inventory
* Dark Stores
* Delivery Partners
* Deliveries
* Customer Ratings
* Traffic Conditions
* Weather Impact

## SQL Analytics Layer

The following analytical views were developed:

* vw_order_summary
* vw_delivery_performance
* vw_inventory_status
* vw_customer_satisfaction
* vw_store_performance

## Dashboard Modules

### Executive Dashboard

Provides business-level KPIs including:

* Total Revenue
* Total Orders
* Average Order Value
* Customer Rating
* Delivery Performance

### Delivery Operations Dashboard

Provides logistics-focused insights including:

* Average Delivery Time
* Delivery Partner Performance
* Deliveries Completed
* Area-Wise Delivery Analysis
* Delivery Status Distribution

### Inventory Intelligence Dashboard

Provides inventory-related insights including:

* Inventory Health
* Product Availability
* Store-Wise Inventory
* Reorder Risk Analysis
* Critical Stock Monitoring

## Key Outcomes

* Improved visibility into operational performance.
* Identification of delivery bottlenecks.
* Monitoring of customer satisfaction trends.
* Detection of critical inventory situations.
* Support for data-driven decision-making.

## Conclusion

The Quick Commerce Analytics Platform demonstrates how SQL and Power BI can be integrated to build a complete business intelligence solution for modern quick-commerce operations. The platform enables operational monitoring, strategic reporting, and actionable insights through interactive dashboards.
