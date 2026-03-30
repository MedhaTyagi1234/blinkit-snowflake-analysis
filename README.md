## 📂 Project Structure

blinkit-snowflake-analysis/
│
├── data/
│   └── blinkit_data.csv
├── sql/
│   └── blinkit_queries.docx
├── dashboards/
│   ├── blinkit_overview_analysis.png
│   ├── order_delivery_analysis.png
│   └── marketing_performance.png
├── README.md
└── insights/
    └── key_findings.txt

# Blinkit Sales & Operations Analysis using Snowflake & Cortex AI

This project focuses on analyzing Blinkit sales, delivery, and marketing data using Snowflake. 
The data was structured by creating database, schema, and tables, and further analyzed using SQL.

Snowflake Cortex AI was used to generate structured dashboards and accelerate insight discovery.

## Project Overview

This project is divided into three main parts:

1. Blinkit Overview Analysis  
2. Order & Delivery Performance Analysis  
3. Marketing Performance Analysis  

Each section focuses on solving real business problems using data.

## 1. Blinkit Overview Analysis

### Objective
To understand overall business performance and customer activity.

### Key Metrics
- Total Orders  
- Unique Customers  
- Total Products Sold  
- Average Delivery Time  

### Insights
- Order trends show how demand changes over time  
- A small number of products contribute significantly to total sales  
- Customer activity remains consistent across the dataset  

## 2. Order & Delivery Performance Analysis

### Objective
To evaluate delivery efficiency and identify operational issues.

### Key Metrics
- On-Time Delivery %  
- Average Delivery Time  
- Delayed Orders %  

### Insights
- Delivery delays increase with distance  
- Certain delay reasons occur more frequently  
- Delivery partner performance varies, showing improvement opportunities  

## 3. Marketing Performance Analysis

### Objective
To measure marketing effectiveness and return on investment.

### Key Metrics
- Total Spend  
- Revenue Generated  
- ROAS (Return on Ad Spend)  
- Conversion Rate  

### Insights
- Some channels generate higher revenue with lower spend  
- High traffic channels do not always convert well  
- A few campaigns contribute most of the revenue  

## Conclusion

This project shows how data can be used to understand business performance across multiple areas.

- Overview analysis helps track growth and demand  
- Delivery analysis highlights operational challenges  
- Marketing analysis identifies opportunities to improve ROI  

Using Snowflake and Cortex AI helped speed up the analysis process while keeping the focus on meaningful business insights.

## Tech Stack
- Snowflake  
- SQL  
- Snowflake Cortex AI  

## How to Use
1. Create database, schema, and tables in Snowflake  
2. Load the dataset  
3. Run SQL queries  
4. Use Cortex AI to generate dashboards  
