# Power BI Course Project
<br><br>
Source of Data:
https://www.udemy.com/course/microsoft-power-bi-up-running-with-power-bi-desktop/?couponCode=OF83024C
<br><br>
### Steps Before Starting Dashboard Creation:

    1. Check the sources of the data (in this case, Excel files).

    2. Load data into Power BI.

    3. Follow a standardized naming convention for objects like tables, measures, etc.

    4. Check the column types in each table and profile them.

    5. Develop various measures and calculated columns within the tables using DAX.

    6. Merge and append queries to join and combine them.

    7. Standardize data formats, especially in date columns.

    8. Create a comprehensive date table containing various granularities (e.g., day, week, month).

    9. Connect fact and dimension tables to create accurate data models.
<br><br>
This dashboard consists of four tabs: **Exec Dashboard**, **Map**, **Product Detail**, and **Customer Detail**. Additionally, there is a hidden tab used to create a **Tooltip** page, which is referenced in the other tabs. Below is a brief explanation of each tab:
<br><br>
#### 1- Exec Dashboard:

This tab displays multiple overall KPIs to monitor the company's performance. Additionally, monthly KPIs are provided to compare the current state with the previous month. A line chart shows revenue growth, while a bar chart displays orders by category. 

A matrix is used to list the top 10 products based on total orders. Two cards highlight the most ordered product type and the most returned product type.

![image](https://github.com/user-attachments/assets/e980e241-888b-4eb7-931b-e4057f9091ed)

Hovering over the bar chart reveals a tooltip with more detailed information for each specific category.

![image](https://github.com/user-attachments/assets/6ee4adc8-83af-4c60-9c94-da692beee88d)

On the far left of the tab, a navigation bar—visible on all dashboard tabs—facilitates easy tab navigation. It includes a reset button to clear all applied filters and a button to display a filter panel with year and continent filters.

![image](https://github.com/user-attachments/assets/7f5fed36-8217-454b-9803-61764b791821)
<br><br>
#### 2- Map:

This tab displays a map showing all countries, with bubble sizes representing total orders—countries with more orders have larger bubbles. Additionally, a slicer allows users to focus on specific continents.

![image](https://github.com/user-attachments/assets/2e8cffa8-db09-449a-a14f-e823277eaf7d)
<br><br>
#### 3- Product Detail:

This tab is used to monitor the status of a specific product. Using the Drill Through feature, users can navigate to this tab from other tabs to view details of the selected product. An area chart displays different metrics, which can be chosen from the slicer on the left side.

Additionally, a price adjustment percentage can be set to see its impact on total profit for the selected product, shown in a line chart. Multiple gauge widgets display the status of the product in comparison to set targets.

![image](https://github.com/user-attachments/assets/b2f59e62-5313-42cc-bb6b-aead072ea295)
<br><br>
#### 4- Customer Detail:

This tab uses similar visualizations to provide managers with detailed insights about customers. It includes information such as the top customer and top 100 customers by revenue. Donut charts display customer proportions based on **occupation** and **income level**. Additionally, it shows changes in **total customers** and **revenue per customer** over time.

![image](https://github.com/user-attachments/assets/9776d845-52c9-4521-94f9-07d222a4b5c1)
