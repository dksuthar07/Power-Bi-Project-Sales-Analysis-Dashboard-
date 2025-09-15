# Sales Analysis Dashboard using Power BI

## Overview

This repository contains a comprehensive sales analysis project I built using Microsoft Power BI. The goal of this assignment was to transform raw sales data into an interactive, multi-page dashboard. I focused on analyzing key performance indicators (KPIs) across various dimensions like product performance, customer geography, and time-based trends to provide actionable insights for a business.

The report includes 11 distinct pages, each designed to answer specific business questions, from a high-level overview to granular details about product attributes and sales flow.

---

## Dashboard Pages

The Power BI report is structured into the following analytical pages:

**Page 1: Overview Dashboard**
* **Question:** What is the overall performance of orders in terms of total revenue, order quantity, and stock availability?
* **Visuals:** Cards for Total Revenue ($147.8K), Total Orders (48), Order Quantity (78), and Stock (1066); a Donut Chart for order status breakdown; and a KPI visual comparing revenue against a target.

**Page 2: Sales Performance by Product Category**
* **Question:** Which product categories are generating the highest revenue and order quantities?
* **Visuals:** A Stacked Bar Chart for revenue by product category/subcategory, a Clustered Column Chart for order quantity by category, and a detailed Table visual.

**Page 3: Customer Location Analysis**
* **Question:** How do sales and customer behavior vary across different locations?
* **Visuals:** A Map visual plotting order totals by location and a Bar Chart for order quantity by location.

**Page 4: Order Trends Over Time**
* **Question:** How have orders and revenue trended, and which days of the week see the most orders?
* **Visuals:** A Line Chart for revenue over time and an Area Chart showing order quantity by day of the week.

**Page 5: Shipping and Delivery Performance**
* **Question:** How efficient is the shipping process, and how does it impact delivery timelines?
* **Visuals:** A Scatter Chart plotting shipping time against order status and a Funnel Chart showing the count of orders by status.

**Page 6: Payment Method Preferences**
* **Question:** Which payment methods are most popular, and how do they impact order totals?
* **Visuals:** A Pie Chart for payment method distribution and a Clustered Bar Chart for order total by payment method.

**Page 7: Product Stock and Inventory Analysis**
* **Question:** Which products are at risk of stockouts, and how does stock correlate with order quantity?
* **Visuals:** A Table with conditional formatting for stock levels and a Scatter Plot comparing stock vs. order quantity.

**Page 8: Product Attribute Analysis**
* **Question:** How do product attributes like color, size, and weight influence sales?
* **Visuals:** A Treemap for order totals by product color/size and a Line Chart for product weight vs. order quantity.

**Page 9: Customer Feedback and Order Status**
* **Question:** How does customer feedback correlate with order status and delivery performance?
* **Visuals:** A Stacked Column Chart showing customer feedback by order status.

**Page 10: Price and Revenue Analysis**
* **Question:** How does pricing affect order quantities and overall revenue?
* **Visuals:** A Scatter Chart plotting price against order total and a Line Chart for average order total over time.

**Page 11: Sales Flow and Contribution Analysis**
* **Question:** What contributes to revenue changes, and how do categories perform over time?
* **Visuals:** A Waterfall Chart to break down revenue contributions and a Ribbon Chart to show how category rankings change over time.

  ## Interactive Features

To enhance the user experience, I have implemented several interactive features:
* **Slicers & Filters:** Dynamic slicers for `Month`, `Product Category`, and `Customer Location` are available to filter the data across the report.
* **Drillthrough:** I have configured drillthrough capabilities allowing users to navigate from a high-level summary to a detailed page. For example, right-clicking the Donut Chart on the Overview page allows a drillthrough to the Shipping Performance or Customer Feedback pages.
* **Page Navigation:** I designed a user-friendly navigation system with `Next`, `Previous`, and `Home` buttons on each page. The homepage also features a table of contents for direct navigation to any report page.
* **Bookmarks:** Bookmarks are used with a `Reset` button to allow users to easily clear all filters and return to the default view of the page.

---
