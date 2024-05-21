---
title: "Beamlytics Lens"
date: 2024-05-19
weight: 1
show_call_box: true
---

# Beamlytics Lens
In today's competitive retail landscape, omnichannel success hinges on real-time insights. Beamlytics Lens is a new streaming data analytics platform designed specifically for omnichannel retailers. It empowers you to analyze transactional and clickstream events in real-time, gaining the knowledge you need to optimize inventory, sales, and customer experiences.

## What Beamlytics Lens Offers

The MVP release of Beamlytics Lens boasts a powerful suite of features to transform your retail operations:

**Real-time Omnichannel Inventory Visibility**: Gain a holistic view of inventory levels across your entire network, including individual stores and custom location groups.

**Low-Stock and Out-of-Stock Alerts**: Receive real-time alerts during live ecommerce sessions to proactively address stock issues and prevent cart abandonment. These metrics are available through APIs for integration into your checkout or cart pages.

**Sold-in-Cart Signals**: Enhance your ecommerce platform by displaying dynamic "X Sold in Past Y Hours" indicators on product listing pages (PLPs) and product detail pages (PDPs). Additionally, showcase real-time cart counts on PLPs and PDPs to give customers a sense of urgency and encourage purchases. These metrics are also available via APIs for seamless integration.

**Machine Learning-powered Forecasting**: Beamlytics Lens leverages pre-built machine learning models to generate sales forecasts, demand forecasts, and revenue forecasts. These forecasts are based on your connected event sources and become operational upon integrating your active inventory data. Access forecast results through APIs or in BQML syntax for further analysis.
>Following ML models will be completely operationalized when data sources are connected and data is loaded in our platform-
- Customer Churn Prediction
- Sales Forecasting
- Demand Forecasting
- ECommerce conversion rate prediction
- Stockout Prediction

**Advanced Customer Insights**: Predict customer churn, stockouts, and ecommerce conversion rates using Beamlytics Lens's built-in, sophisticated ML models. API access and BQML integration provide flexibility in utilizing these insights.

**Composable KPI Dashboards**: Create personalized dashboards using a library of reusable KPI cards. Each card displays a selected KPI for a chosen timeframe, along with a trend graph for the past N periods. Drill down from overall store or item level metrics for granular analysis. 
>KPIs include:
- Total Revenue (including predicted revenue from the ML model)
- Total Customers (including predicted customer churn)
- Total Visitors
- Total Revenue by Segment (customer, item category, geographic region)
- GMROI (Gross Margin Return on Investment)
- Top Items Sold
- Top Items Out of Stock
- Conversion Rates (including predicted customer churn)
- Sell-Through Rates

## Why Choose Beamlytics Lens?

1. **Simplified data pipelines instead of integrated systems**: Traditionally, omnichannel retailers face the challenge of integrating separate systems for omnichannel inventory and ecommerce stream analytics. Furthermore, deriving inventory-related intelligence from ecommerce clickstream data often requires additional integrations between website, clickstream analytics tools, omnichannel inventory systems, and data warehouse/BI systems. These integrations can be expensive and complex, costing millions of dollars to implement.
>Beamlytics Lens offers a single, cost-effective SaaS solution that eliminates this complexity. In its initial version, it combines clickstream analytics, omnichannel inventory management, pre-built ML models for inventory forecasting, and operational and analytics reporting dashboards encompassing all your inventory KPIs. Seamlessly integrate omnichannel inventory events (store transactions, receipts, transfers, adjustments) and clickstream events for a unified view of your operations.

2. **Beamlytics Lens is committed to open-source principles**.
>The code is free and will remain so, allowing anyone to download and run the pipeline wherever needed.

3. **Beamlytics Lens will evolve as a generic data processing system for retail**:

	>The MVP focuses on the functionalities mentioned above. However, the roadmap envisions Beamlytics Lens evolving into a generic stream data processing engine with a no-code platform for pipeline development. 

4. **Efficient and cost-effective cloud platform**: 
>Beamlytics is dedicated to maintaining efficient, secure, and highly scalable cloud operations to minimize costs for its customers.
