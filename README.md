# Superstore-sales-dashboard

# Super Store Sales Dashboard
 

## Dashboard Link https://app.powerbi.com/links/8o43gIucGE?ctid=9bbc0c7a-2e1d-458e-a996-4b1766a1c1a9&pbi_source=linkShare

# Superstore dataset Link [superstore_dataset.csv](https://github.com/user-attachments/files/15748129/superstore_dataset.csv)

Background
A Superstore operates across multiple regions, selling a diverse range of products including furniture, office supplies, and technology. The store aims to enhance its decision-making process by utilizing data-driven insights to monitor sales performance, manage inventory, and understand customer behavior. Currently, the data is scattered across various sources, making it challenging to get a comprehensive view of the business operations.

Objectives
The primary objective is to develop an interactive sales dashboard for the Superstore that consolidates data from various sources into a single, easy-to-use platform. This dashboard will provide real-time insights into sales metrics, inventory levels, customer demographics, and the effectiveness of promotions. By leveraging this dashboard, the store management can make informed decisions to optimize operations, improve sales, and increase profitability.

Stap 1 Download super store csv file in Desktop.

stap 2 Open jupyter notebook and create file and import numpy or pandas.

stap 3 Key Features
Sales Analytics

## Overall Sales Performance: Track total sales, average order value, and number of transactions over time.
## Sales by Category: Breakdown of sales across different product categories such as furniture, office supplies, and technology.
## Regional Sales: Analyze sales performance across different regions.

stap 4 
Customer Demographics: Information on customer age, gender, location, and purchasing behavior.
stap 5
Data Cleaning:
Remove duplicates.
Handle missing values.
Standardize date formats and units.
stap 6 
Data Transformation:
Aggregate data to the required granularity (e.g., daily, years, monthly).
Segment data by categories like product, region, and customer demographics.

## Deployment

To deploy this project run

```bash
  npm run deploy
```

import numpy as np 
import pandas as pd

data = pd.read_csv("superstore_dataset.csv")
data.info()
data.dtypes
data.isnull().sum()

Data is not null value and no error any row or columns.
Step 7
Open Power Bi and import csv file or Load data.
User Interface (UI) Design:

Design an intuitive and user-friendly interface.
Ensure important metrics are easily accessible.
Use consistent colors, fonts, and chart types.
Create a high-fidelity mockup of the dashboard to visualize the final product.

stap 8 
Create Visualizations:

Build charts and graphs for each key metric.

Examples:
Add KPIs Profit , total unit cost.
Line charts for sales trends.
Bar charts for top-selling products.
Pie charts for customer demographics.
Add maps country and Satat wise sales.


Stap 9
# Screenshort

Profit KPIs
![Capturesu1](https://github.com/Bedeveloperin/Superstore-sales-dashboard/assets/109737267/81ad8ce5-9fd7-4028-99cf-4a8ee941c59a)

Profit Margin
![Capturesu2](https://github.com/Bedeveloperin/Superstore-sales-dashboard/assets/109737267/5bcb6cce-8f9c-483d-be2b-4da7337cb345)

Sales and Profit
![Capturesu3](https://github.com/Bedeveloperin/Superstore-sales-dashboard/assets/109737267/cd0df671-8e47-4e2e-bb9c-73c5a213ccb0)

Complate Create dashboard
![Capturepower1](https://github.com/Bedeveloperin/Superstore-sales-dashboard/assets/109737267/ac76ab7b-b77b-4a8f-bff6-73114cd62af9)


stap 10

Deploy and Share the Dashboard

Publish the Dashboard:

If using a cloud-based tool, publish the dashboard to the cloud.
For on-premise solutions, deploy the dashboard on the company’s server.
Set Up Access Control:

Define user roles and permissions to control who can view and edit the dashboard.
Training and Documentation:

Provide training sessions for end-users to familiarize them with the dashboard.
Create documentation detailing how to use the dashboard and interpret the data.


## Skills
Python , Jupyter notebook , Numpy , Pandas , PowerBI , Data Cleaning , Data Exploration , Data Transformation , Data Visualization , Key Performance Indicators (KPIs) , Reporting and Dashboarding
