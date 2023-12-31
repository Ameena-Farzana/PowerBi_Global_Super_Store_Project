# PowerBi_Global_Super_Store_Project

The "Global Superstore" dataset is a fictional dataset commonly used for learning data analysis, data visualization, and business intelligence tool, Power BI. It's often used as a sample dataset to showcase various analysis and reporting techniques.

The dataset simulates sales data for a global retail company with multiple branches or stores worldwide. It typically includes information about customers, orders, products, shipping, and various other related attributes.

Dataset contains 3 tables:

1. Orders Table: This table contains information about individual orders placed by customers. It includes details such as Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Sales, Quantity, Discount, Profit, Shipping Cost, and Order Priority.

2. People Table: This table holds demographic information about customers, such as Customer Name, Segment (e.g., Consumer, Corporate), City, State, Country, and Region.

3. Returns Table: This table tracks returned items and includes information about whether an item was returned (Returned column), the Order ID, and the Market.


Table contents: 
1) Orders table:

* Order ID: A unique identifier for each order.
* Order Date: The date when the order was placed.
* Ship Date: The date when the order was shipped.
* Ship Mode: The shipping method for the order (e.g., standard, express, etc.).
* Customer ID: A unique identifier for each customer.
* Customer Name: The name of the customer who placed the order.
* Segment: The market segment to which the customer belongs (e.g., consumer, corporate).
* City, State, Country: The geographical location of the customer.
* Postal Code: The postal code of the customer's address.
* Market: The market region (e.g., Americas, Europe, Asia-Pacific, Africa).
* Region: The specific region where the market is located.
* Product ID: A unique identifier for each product.
* Category, Sub-Category: Product categorization (e.g., technology, furniture, office supplies).
* Product Name: The name of the product.
* Sales: The total sales revenue for the order.
* Quantity: The quantity of products ordered.
* Discount: The discount applied to the order.
* Profit: The profit generated from the order.
* Shipping Cost: The cost of shipping for the order.
* Order Priority: The priority of the order (e.g., high, medium, low).
* Returned: Indicates whether the order was returned.

2) Returns Table:

* Returned: Indicates whether an order was returned.
* Order ID: The unique identifier of the returned order.
* Market: The market region where the return occurred.

3) People Table:

* Person: The name of the person or employee.
* Region: The region where the person is located.

## Visualization include:

Creating an interactive sales report involves multiple steps, including data cleaning, visualization, and creating interactive elements. Given the complexity and detail required for each step, I'll provide a high-level overview of how to approach this project:

1. Data Cleaning:

+ Remove duplicate records, if any.
+ Handle missing values by imputing or removing them based on the specific context.
+ Standardize formats of dates, numbers, and text fields.

2. Segment Visuals using Country, Region, Market:

+ Use slicers or filters to allow users to segment data based on country, region, and market.
+ Create visuals such as bar charts, line charts, and maps that respond dynamically to slicer selections.

3. Analyze Percentage of Shipping by Ship Mode:

+ Create a measure for total shipments and shipping percentage.
+ Use pie charts or stacked column charts to display the percentage of shipping modes.

4. Visualize Sales by City, States, Region, and Market:

+ Create tables or charts to display sales metrics based on the desired segmentation (city, state, region, market).
+ Utilize drill-through functionality to provide detailed information when users interact with data points.

5. Create Tables for Visualizations:

Create separate tables for each visualization, displaying key metrics based on different segments.



#### Result

![Powerbi_Result_](https://github.com/Ameena-Farzana/PowerBi_Global_Super_Store_Project/assets/121862099/c2a2e5a5-2eca-4a33-b14e-75ed9fa0becf)



![Powerbi_dataview](https://github.com/Ameena-Farzana/PowerBi_Global_Super_Store_Project/assets/121862099/5b69b724-9143-4579-a363-aa1341d460a0)
