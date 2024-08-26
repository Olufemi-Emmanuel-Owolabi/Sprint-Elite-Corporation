# Sprint Elite Corporation
Analyzing Adidas dataset

## Table of Contents
- [Introduction](#Introduction)
- [Problem Statement](#Problem-Statement)
- [Data Analytics Framework](#Data-Analytics-Framework)
- [Ifeoluwa](#Ifeoluwa)
- [Justification of Dashboard and Analysis](#Justification-of-Dashboard-and-Analysis)
   - [Data Source](#Data-Source)
   - [Data Preparation](#Data-Preparation)
   - [Model Planning and Building](Model-Planning-and-Building)
   - [Communicate Results and Operationalise](#Communicate-Results-and-Operationalise)
- [Justification of Dashboard](#Justification-of-Dashboard)
- [Recommendation](#Recommendation)


### Introduction

![KPIs](https://github.com/user-attachments/assets/fe5081b9-d884-4449-ba02-bc207d3dfec5)

Sprint Elite Corporation has emerged as a prominent global brand in the dynamic and highly competitive realm of sportswear and athletic apparel. The company offers various goods and services, such as Men's Street Footwear, Men's Athletic Footwear, Women's Street Footwear, Women's Athletic Footwear, Men's Apparel, and Women's Apparel. Sprint Elite Corporation experienced an increase in its total units sold, reaching $2 million.

### Problem Statement

The problem statement describes Sprint Elite Corporation, a prominent global brand in the sportswear and athletic apparel industry, focusing on various product categories such as men's and women's footwear and apparel. Despite achieving substantial total sales of $899.90 million and an operating profit of $332.1 million between 2020 and 2021, the company faces challenges in specific product categories and regions.

The key issues include poor sales and operating profits in men's apparel and women's athletic footwear and weak sales performance in the Midwest and South regions. Alternately, women's apparel and men's street footwear have shown significant profitability, and the West region has performed well, indicating potential growth areas.

The company also needs to enhance its in-store sales strategy and optimize its e-commerce platform for better revenue generation. With operations currently limited to the United States, there is an opportunity for the company to expand internationally and diversify its offerings.

The report will analyze various aspects of Sprint Elite Corporation's performance, including profitability, regional reach, product/service performance, and time-based trends. The insights will help the company make informed strategic decisions, optimize resources, and remain competitive in the sportswear market.

## Data Analytics Framework

This data analytics project will leverage a Business Intelligence (BI) framework to empower Sprint Elite Corporation in the competitive sportswear and athletic footwear industry. In the highly competitive sportswear and athletic footwear industry, leveraging Business Intelligence (BI) is crucial for strategic success. BI enables companies to analyze customer behaviour, market trends, and operational efficiency, leading to informed decisions in areas like pricing, inventory management, and marketing strategies. It offers numerous advantages, including in-depth customer insights, improved operational visibility, real-time data access, enhanced efficiency, and revenue growth.

BI encompasses various tools, databases, and analytical methods that help businesses interact with customers effectively and control costs. By analyzing data from multiple sources, sportswear companies can identify market trends, consumer preferences, and optimal sales channels. In the data analytics project, Sprint Elite Corporation will use BI to tailor products to customer needs, optimize resource allocation, and boost sales across different channels, whether in physical stores or online. BI systems also help track product performance, identify best-sellers, and understand customer preferences, enabling companies to maximize opportunities and minimize risks.


### Justification of Dashboard and Analysis
### Data Source

The dataset contains information about Sprint Elite Corporation and includes company-specific sales data. The data was collected using the Kaggle platform and the data is known as the Adidas Sales Dataset. 

### Data Preparation

The dataset acquired from Kaggle was accessed and loaded into Microsoft Excel for further analysis. During this stage, several columns were removed, including the columns containing information on Price per Unit and Retailer ID. New columns were added, such as Cost of Sales (created using Excel), Invoice Date by Year, Invoice Date by Quarter, and Year (created using PowerBi). 

  - Formulas

      - Cost of Sales =[@[Total Sales]]-[@[Operating Profit]]. Calculated using Excel.
      - Year = YEAR('Sprint Elite Corporation Sales Dataset'[Invoice Date]). Measured the year from invoice date using DAX on PowerBi.

### Model Planning and Building

Upon importing the dataset into Power BI, it underwent a series of transformations in the Power BI Query Editor. Subsequently, a comprehensive review was carried out to identify and rectify any errors present in the loaded datasets, ensuring data integrity and accuracy.

### Communicate Results and Operationalise

Various charts were generated to summarize and visually represent the sales data, facilitating the identification of trends and patterns, and enhancing comprehension. A PowerBI dashboard has been developed, featuring slicers that enable users to engage with the data and analyze it through various visualizations. These visualizations include the operating margin by sales method, total sales by product, total sales by year, total sales by region, total sales and operating profit by region, total sales by retailer, sum of total sales by retailers, and total sales by year.

### Justification of Dashboard

![Sprint Elite Corporation Dashboard](https://github.com/user-attachments/assets/e4bdebeb-4200-4aa5-abe3-01a7e4d1b299)

The dashboard titled "Sprint Elite Corporation Sales Analysis" provides a comprehensive overview of the company's performance across various dimensions for the year. The dashboard includes KPI cards for total sales, units sold, and operating profit; a pie chart for operating margin by sales method; bar charts for total sales by region, product, and retailer; a combined bar and line chart for total sales and operating profit by region; and a line chart for monthly sales trends over the years 2020 and 2021.

- Sprint Elite Corporation Dashboard Slicer

![Slicer](https://github.com/user-attachments/assets/965261c9-440e-4c2b-898c-e9ad09d0f083)

The slicer is classified into Year, Product, and Region. Sprint Elite Corporation may easily analyze sales performance by category with this dashboard slicer.

- Sprint Elite Corporation Operating Margin by Sales Method

![Operating Margin by Sales Method](https://github.com/user-attachments/assets/f482c308-6c49-43a7-8a7b-aa6e15d06a75)

Online sales had the largest operating margin, at 55.6%, followed by outlet sales at 29.21% and in-store sales at 15.18%, according to the operating margin by sales technique visualization. This insight emphasizes the necessity for Sprint Elite Corporation to provide its online sales channel with top priority and funding to maximize its profitability. The business can boost overall organizational performance and increase profitability by enhancing the e-commerce platform and employing targeted marketing. Further expansion and increased market competitiveness can be attained through optimizing Outlet sales, in-store efficiency, and cross-channel initiatives.

- Sprint Elite Corporation Total Sales by Region

![Total Sales by Region](https://github.com/user-attachments/assets/d5e949f9-ab68-45ab-8a46-597d0aed0a65)

This shows Sprint Elite Corporation sales data by region. West Region sales total $269.9 million, followed by Northeast with $186.3 million, Southeast with $163.2 million, South with $144.7 million, and Midwest with $135.8 million. Sprint Elite can improve sales, target growth regions, adapt marketing, and make data-driven decisions by using these insights.

- Sprint Elite Corporation Sales by Product

![Sales by Product](https://github.com/user-attachments/assets/f2c857e6-a6dd-4d10-947a-6976977e1506)

The Total Sales by Product visualization provides valuable insights into the sales performance of different product categories for Sprint Elite Corporation. The data reveals that Men's Street Footwear leads with total sales of $208.83 million, followed by Woman's Apparel with $179.04 million, Men's Athletic Footwear with $153.67 million, Women's Street Footwear with $128 million, Men's Apparel with $123.73 million, and Women's Athletic with $106.63 million in total sales. The analysis helps identify top-performing products for a competitive advantage, understand customer preferences for targeted marketing and loyalty, optimize resource allocation for increased revenue and profitability, address challenges in underperforming categories for sales improvement.

- Sprint Elite Corporation Total Sales by Retailer

![Total Sales by Retailer](https://github.com/user-attachments/assets/2f828cf5-1e32-47c8-b661-fb61781d5839)

The Total Sales by Retailer visualization provides valuable insights into the sales performance of Sprint Elite Corporation's products across different retailers. This visualization reveals that West Gear leads with total sales of $242.96 million, followed by Foot Locker with $220.09 million, Sports Direct with $182.47 million, Kohl's with $102.11 million, Amazon with $77.7 million, and Walmart with $74.56 million in total sales. Sprint Elite may improve sales, profitability, and market competitiveness with these insights. This visualization will help Sprint Elite identify difficulties in retail channels with lower sales, such as Amazon and Walmart, and adopt specific tactics to boost sales and performance.

- Sprint Elite Corporation Total Sales and Operating Profit by Region

![Total Sales and Operating Profit by Region](https://github.com/user-attachments/assets/21f039f8-310f-4c4b-a269-afc8e12bd219)

Sprint Elite Corporation's regional sales and operating profitability are shown in the Total Sales and Sum of Operating Profit by Region visualization. This shows the total sales and operating profit for each region: West, $269.94 million, $89.61 million, Northeast, $186.32 million, $68.02 million, Southeast, $163.17 million, $60.56 million, South, $144.66 million, $61.14 million, Midwest, $135.8 million, $52.81 million. The Total Sales and Sum of Operating Profit by Region visualization shows Sprint Elite Corporation's regional sales and operating profitability. It shows the West's success and the Northeast and Southeast's growth potential.

- Sprint Elite Corporation Total Sales by Month and Year

![Total Sales by Month and Year](https://github.com/user-attachments/assets/922108b3-064a-4ced-b08c-264b603d34d1)

Sprint Elite Corporation's 2020–2021 sales performance is seen in the Total Sales by Month and Year visualization. Figure 9 displays monthly sales for both years, showing sales trends and performance variances.

   - High Performance: Sprint Elite sold more in November and December (2021) than in 2020 (59.24M and 77.8M). Holiday ads, discounts, and new product launches may have contributed to this. Summer sales are high, which the corporation can optimise for next season.
   - Low Performance: Sprint Elite sold 15M in February 2020, compared to the preceding months. After the holidays, consumers may have been more frugal with their spending. The graphic also illustrates that sales drop every year after the holiday in the first quarter.


### Recommendation

The recommendation for Sprint Elite Corporation emphasizes the need for Business Intelligence (BI) to remain competitive in the dynamic sportswear and athletic footwear market.

 Key recommendations include:

   - Product Innovation: Invest in research, development, and innovative designs for high-demand products, particularly Men's Street Footwear and Women's Apparel, to align with customer preferences and boost revenue.
   - Targeted Marketing: Implement marketing strategies tailored to specific regions, focusing on addressing sales underperformance in the Midwest and South regions through sales promotions and customer engagement.
   - E-commerce Enhancement: Invest in the e-commerce platform to improve user experience and implement focused digital marketing to maximize online sales profits.
   - In-Store Sales Improvement: Investigate the causes of poor in-store sales and develop strategies to enhance customer experience and sales efficiency in physical stores.
   - International Expansion: Diversify the product portfolio by expanding internationally.
   - Seasonal Marketing Strategies: Develop a comprehensive marketing and promotional strategy for seasonal peaks, such as holidays and summer, to capitalize on increased consumer spending.





