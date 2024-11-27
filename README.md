# US_Candy_Distributor


![candy_factory_workers](https://github.com/user-attachments/assets/5df03a0c-0090-4918-9237-b921cdd262cf)
-------------------------------------------------------------------------------------------------------------------------------------------------------
**Welcome to the US Candy Distributor repository! 🍬 This project is a comprehensive analysis of sales and geospatial shipment data for a national candy distributor in the United States. It provides insights into the intricate logistics of moving delicious treats from factories to customers across the country,profit and product moved in the United States  and across all regions in it.** 

_Disclaimer_: _All datasets and reports do not represent any company, institution or country, but just a sample dataset to demonstrate capabilities of excel_

## Explanatory Data Analysis (EDA):
1. Which regions contribute the most to total sales?
2. Who are the 5  top customers by sales value, and how frequently do they place orders?
3. How does year-over-year sales growth vary by product?
4. How do different factories compare in terms of total sales, units shipped, and profitability?  Which factories experience the most delays?
5. What are the buying patterns of customers in terms of  shipping methods?
   
## Skills/ concepts demonstrated:
- Data Cleaning & Preparation
- Creating Pivot Tables to summarize data 
- Applying Pivot Charts for visual representation.
- Advanced Data Modeling (Using Power Pivot to manage large datasets across multiple sheets)
- Data Visualization (Creating interactive dashboards using Pivot Charts and Tables and adding Slicers  for interactivity).

 ## Data Source & Modeling
 
The dataset  **[US CANDY DISTRIBUTOR](https://maven-datasets.s3.amazonaws.com/US+Candy+Distributor/US+Candy+Distributor.zip)**  used in this project was sourced from Maven Analytics and downloaded as multiple CSV files. 
To prepare the data for analysis:   
- **Compilation**: The CSV files were compiled into a single Excel file for efficient data organization and management.
- **Table Creation**: Each dataset was converted into structured tables within Excel, enabling better referencing and integration.
- **PowerPivot Integration**: The structured tables were then imported into PowerPivot, where relationships between datasets were defined to create a robust data model. This allowed for efficient querying, merging, and advanced analytics.

 ## RESULTS AND FINDINGS
 
![candy_dashboard](https://github.com/user-attachments/assets/557bbe1b-a7a5-479b-9abb-ba0883ae1d56)

During this analysis, I sought to uncover valuable insights by addressing critical business questions using the dataset and dashboard I created. Here’s a summary of the key findings and the methodologies applied:

## 1. Which regions contribute the most to total sales?
   
 **Insights**: From the dashboard regional sales analysis, I identified that the top-performing regions were the Pacific and Atlantic regions with $30,486 and $26,974 gross profit also  contributing the highest sales volumes. The dashboard visualizes regional sales contributions through a  bar charts, making it easy to pinpoint geographical trends.
 
**Methodology**: Sales data was grouped by regions using pivot tables, and visualizations were created to highlight areas with the most significant contributions using gross profit.

## 2. Who are the top 5 customers by sales value, and how frequently do they place orders?

**Insights:** The Customer Rankings panel identified the top 5 customers by sales value, along with their order frequencies displayed on a timeline. These customers consistently contributed a significant portion of the revenue.  

**Methodolody**: Customer data was sorted into top 5 by sales values because of the large number of customers in the dataset and visualized through bar charts. 

 ## 3. How does year-over-year sales growth vary by product?
 
**Insights**: The Product Performance section visualized year-over-year growth trends, revealing that  in 2027 saw the highest growth in product level  while in 2030 there is a  tremendous decline in the sales growth rate.  

**Methodology**: Using calculated measures, sales data was segmented by year and product name was merged with candy_sales using power pivot , with growth trends visualized in bar  charts for quick comparisons.

## 4.How do different factories compare in terms of total sales, units shipped, and profitability?

**Insights**: Factory-level performance was displayed in the Factory Metrics panel, showing factory Lot’s O Nut’s as the leader in profitability, unit shipped and  total cost followed by Wicked Choccy‘s and the rest.

**Methodology**: Metrics like sales, units shipped, and profit margins were aggregated by factory and visualized through comparative bar charts.

## 5. Which factories experience the most delays?

**Insights**: The dashboard’s AVERAGE SHIPMENT DELAY BY FACTORIES section provided a clear comparison, flagging sugar shack  as the most delayed and the other factoey as the most punctual.
**Methodology**: Shipment timelines were analyzed against expected delivery dates, with delays visualized through trendlines and status indicators.

## 6.What are the buying patterns of customers in terms of shipping methods?

**Insights**: Customer preferences for shipping methods were displayed in the Shipping Analysis panel. It revealed that **standard class** was most popular and correlated with larger order sizes.

**Methodology**: Shipping method data was segmented by order size and visualized with pie charts .

**This unified dashboard provided a holistic view of the data, enabling seamless exploration and immediate access to insights through interactive filters and dynamic visualizations. By integrating all answers into one place, stakeholders could easily uncover actionable insights to guide strategic decisions.**

[You can interact with the dashoard here](https://1drv.ms/x/c/ea7bfe9a359fa0e0/EfZT_7F5je9Bh2huFe_1cq8BtM4qeLzY7_be06OJe0iv3w?e=uw6Bb2) 😄

## Recommendations 
**- Enrich Data with Additional Context:**
Include data on external factors such as weather conditions, transportation disruptions, or regional events that could influence sales and delays. This would provide a more comprehensive understanding of the challenges faced by each factory.

**- Include Customer Demographics:**
  Adding demographic data such as customer age, income level, or purchasing behavior could help identify patterns and tailor marketing efforts to specific customer segments.
  
**- Detailed Shipping Information:**
Include details on carriers, shipping routes, and costs to analyze the efficiency of logistics operations more accurately.

**- Regular Updates:**
Ensure the dataset is updated regularly to capture evolving trends and enable real-time decision-making.

## LIMITATIONS 
**-Static Dataset:**
Since the dataset was static, real-time changes in sales or shipment statuses could not be analyzed, making the insights less actionable in dynamic scenarios.

**-Data Incompleteness:**
Some essential field, such as reasons for shipment delays is missing, limiting the depth of analysis.

**-Lack of Historical Data:**
While year-over-year sales growth was analyzed, a longer historical dataset would have provided better trend analysis and forecasting capabilities.

**-Ambiguity in Some Fields:**
Certain columns lacked clear definitions or had inconsistent formats, requiring additional time for data cleaning and interpretation.

![thanks](https://github.com/user-attachments/assets/65959665-0cb0-4a73-8175-96623527249f)








