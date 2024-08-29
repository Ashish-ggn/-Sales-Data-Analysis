
# Sales Analysis-Dashboard

### Problem Statement

This dashboard is designed to provide deep insights into the Sales Analysis. It helps businesses identify bottlenecks, optimize inventory, and streamline operations by analyzing various metrics like shipment efficiency, Average Order Value, and inventory management etc. By understanding these aspects, businesses can enhance their Sales strategies, reduce costs, and improve overall performance.

### Steps Followed

#### Step 1: Data Preparation in SQL Server

* Utilized SQL DDL (Data Definition Language) to create the necessary tables: Orders, Shipments, Inventory, Routes, and Customers, the data refrence was taken from multiple data set avilable on https://www.kaggle.com/ 

* Applied DML (Data Manipulation Language) operations to populate these tables with synthetic data reflecting various aspects of the supply chain, such as order details, shipment records, and inventory statuses.

####  Step 2: Feature Engineering

* Performed Feature Engineering by creating additional columns to derive new insights. For example, calculated columns like 'Shipment Days' and 'Profit Margin' were added to enhance analysis capabilities.
* Multiple bucket columns/calculated columns were created in SQl Such as delivery type to identification of late,early and on time delivery .
* This step also involved data transformation and cleansing using SQL to ensure the quality and reliability of the data before connecting it to Power BI.


####  Step 3: Connecting Power BI to SQL Server

* Connected Power BI directly to the SQL Server database, ensuring a seamless flow of data for real-time analysis.
* Established relationships between different tables using primary and foreign keys, forming a star schema to facilitate efficient querying and reporting.

#### Step 4: Data Visualization in Power BI

* The Dashboard is designed in such a way that  without applying  any filter or slicer affecting  the dashboard, all the nessary KPIs and graphs showing the visuals will work according to the latest finacial year so that the figures of current financial year 
are clearly visible and insights can be gained .

* Designed the dashboard with various visualizations, including bar charts, line graphs, and KPIs, to represent key metrics like Average order Value, Average shipping Days, and customer life time Value.

* Implemented slicers and filters to allow users to drill down into specific areas, such as viewing shipment performance by route or analyzing inventory levels by product category.


#### KPIs Used:-
(All the calculations can be viwed in the attached dashboard)
* Customer Life time Value.
* Customer Life Span.
* Net Sales comparing it PY year .
* Discount % comparing it PY year .
* Average order Value comparing it PY year .
* Profit Growth 
* No. of Orders comparing it PY year .
* Best Performed Product based on total sales.
* Worst Performed Product based on total sales.
* Fright comparing it PY year .
* Average Shipping Cycle comparing it PY year .
* Average Profit/Unit comparing it PY year .
* Average Revenue/Customer comparing it PY year .


#### Charts:-

* Multiple Charts are created for better analysis and predict the sales such as yearly trend for parameters such as Netprofit,Netsales,Discount% Etc, Orders Segementation as per Route,SKU etc.

#### SnapShots Of Dashboard
![image](https://github.com/user-attachments/assets/2788fe13-f6e4-437b-aaca-54557025495c)
![image](https://github.com/user-attachments/assets/acd418c3-4560-492f-b7e9-44e4b808e0e0)
![image](https://github.com/user-attachments/assets/3642fde4-53bc-4a92-97a6-4c37e85ae4cb)
![image](https://github.com/user-attachments/assets/c80b7640-f5a1-462e-a765-c5a43d852589)
![image](https://github.com/user-attachments/assets/adabb094-a913-4461-82f0-3af6a1466bdb)






