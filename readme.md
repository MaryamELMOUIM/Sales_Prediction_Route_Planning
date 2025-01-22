# Holdingo Sales Prediction and Route Suggestion

## Overview

The **Holdingo Sales Prediction and Route Suggestion** project is a comprehensive solution for optimizing sales strategies and forecasting. This project integrates predictive analytics for sales forecasting, as well as route optimization to improve the efficiency of salespeople. By analyzing historical sales data, the system provides sales predictions, customer insights, and optimized travel routes to help sales teams boost their performance.

## Key Features

1. **Sales Prediction**: 
   - Predicts daily sales for client-product combinations using historical data.
   - Provides actionable insights for decision-making in sales strategies.

2. **Route Optimization**:
   - Suggests optimal routes for salespeople based on customer locations and volume goals.
   - Helps reduce travel time and increase productivity.

3. **Database Integration**:
   - Utilizes PostgreSQL to store and retrieve sales and customer data.
   - Connects to the database using `SQLAlchemy` and retrieves data via `pandas` DataFrames.

4. **Interactive Dashboard**:
   - Built in **Power BI** to visualize and monitor key performance indicators (KPIs), such as sales trends, customer behaviors, and seller performance.
     you can find it in the following link: [link](https://app.powerbi.com/view?r=eyJrIjoiYjdjOGUxY2MtNWVkNi00NGI0LThmMTAtYzA2M2U5ZWM5N2FkIiwidCI6IjhiYjA1YjAwLTdmNDgtNDc4NS05NjgwLTkzYjgwYTM0NTVhNSJ9)
     ![image](https://github.com/user-attachments/assets/ce0601a8-5fc8-4f16-9246-38a5a9cca510)


## Prerequisites

Before running the system, ensure you have the following libraries installed:

```bash
pip install psycopg2-binary sqlalchemy pandas

