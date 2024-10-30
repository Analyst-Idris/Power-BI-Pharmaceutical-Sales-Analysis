# Power-BI-Pharmaceutical-Sales-Analysis

![image](https://github.com/user-attachments/assets/177b9b94-9af7-4630-b3c7-aec1b00ca5b8)

# Introduction

This is a Power BI project focused on sales and distribution analysis for an imaginary organization called Veldrix Pharmaceuticals. The project aims to analyze the effectiveness of Veldrix's distribution network by exploring key factors such as distributor performance, product availability, and sales trends. The goal is to identify insights that can support Veldrix's sales and marketing strategies, ensuring efficient distribution and improved market penetration.

**__Disclaimer__:** All datasets and reports do not represent any company, institution, or entity, but are solely for demonstrating the capabilities of Power BI.


# Problem Statement

Veldrix Pharmaceuticals is currently facing challenges in optimizing its distribution network and achieving sales targets. The company needs to understand which distributors and strategies are most effective in ensuring product availability and boosting sales. The primary objective of this analysis is to identify factors influencing successful distribution and to provide actionable insights that can help develop more effective sales strategies, improve distributor relationships, and drive overall growth.

# Methodology

### Data Preparation and Visualization

**1.	Power Query:** Power Query was utilized for effective data manipulation, including merging multiple tables to create a cohesive dataset ready for analysis.
**2.	Calendar Table:** A Calendar table was created using Data Analysis Expressions (DAX) to enable time intelligence and facilitate date-based analysis.
**3.	Measures and calculations:** Key measures and calculations were implemented through DAX to provide insights and perform in-depth analysis.
**4.	Relationship Establishment:** Relationships were established between the Calendar table and other tables based on related columns, ensuring accurate data analysis and visualization.

   
   
   ![Modelling](https://github.com/user-attachments/assets/e9f9af33-7a50-4372-86e4-7ddfca89f5ee)


   ![KPT's](https://github.com/user-attachments/assets/8d73bdd6-2853-4c03-a226-be55453c5bcd)

   ![Navigation and Slicers](https://github.com/user-attachments/assets/97b5cdbe-8696-4ffc-8c77-210e7d309295)


   ### Visualization Techniques:

To support data-driven decision-making and deliver clear, actionable insights, a variety of visualization techniques were thoughtfully employed in this analysis. Each chart type was chosen specifically to represent the data effectively and highlight key insights. The visualizations include:

**•	Line Charts:** Used to track Actual Revenue on a month-by-month basis. This chart type effectively illustrates revenue trends over time, making it easy to spot seasonal patterns, growth rates, and monthly fluctuations in revenue.

**•	Donut Charts:** Designed to show the proportional distribution of Actual Revenue by Channel. This format provides a quick visual breakdown, making it easy to understand how different channels contribute to total revenue.

**•	Clustered Bar Charts:** Utilized to display revenue across Sub-channels, allowing for easy comparison of performance within each main channel. This approach highlights differences between sub-channels, revealing potential areas for optimization or investment.

**•	Stacked Bar Charts:** Employed to represent Product Class performance, showing the distribution and comparison across classes within the same visual. Stacked bars effectively compare contributions of each class, revealing both individual and cumulative performance.

**•	Maps:** Applied to visualize Actual Revenue by City, enabling a geographic perspective on revenue distribution. This visualization helps to quickly identify high-performing cities and potential areas of focus for market expansion.

**•	Stacked Column Charts:** Used to compare Actual and Target Quantities for different Managers and Product Classes. This chart type provides a direct visual comparison between actual performance and targets, highlighting gaps and overachievements for different segments.

**•	Matrix Tables:** Designed to present a comprehensive overview of Actual & Target Quantities, Actual & Target Revenue, and the percentage change between them for the Top 15 Products. This format is ideal for summarizing multiple performance metrics, facilitating quick comparisons across top products.

**Pharmaceutical Performance Analysis Visual**

![Uploading Performance Analysis.jpg…]()


**Pharmaceutical marketing Analysis Visual**


![Uploading Marketing Analysis.jpg…]()


## SUMMARY OF REVENUE AND OTHER KEY METRICS

The analysis of revenue and performance metrics across different channels, product classes, and managers provides a detailed overview of the business's financial landscape and operational efficiency.

To visualize sub-channel performance, revenue figures for **Retail and Private channels** were analyzed. **Retail Channel** emerged as the leading revenue generator with 8.2 billion, while the **Private channel** followed at 2.3 billion. Further breakdown by channel type highlighted **Pharmacy** as the top revenue contributor with 5.85 billion, accounting for 52.9% of the total revenue, while **Hospitals** contributed 5.2 billion, or 47.1%.

**1. Product class analysis:** This analysis revealed significant revenue distribution among key products. **Analgesics** achieved the highest target and actual revenue, reaching 5.3 million and 5.2 million, respectively. Antiseptics followed with target and actual revenues of 4.2 million and 4 million. In contrast, **Antimalarial products** had the lowest target revenue at 2.05 million, and **Antiseptics** recorded the lowest actual revenue of 3.08 million. For geographic insights, a city-wise quantity analysis indicated that **Butzbach** led with 174.23k, while **Altenburg** reported the lowest with 94.97k.

**2. Manager Performance:** Manager performance was also evaluated to determine target vs. actual quantities. **Brittany Bold** stood out with the highest actual (6.7 million) and target (8.4 million) quantities, whereas **James Goodwill** recorded the lowest actual quantity of 5.7 million, and **Alisha Cardwell** had the lowest target quantity at 4.3 million.

**3. Monthly Insights Accross the years:** Monthly revenue progression was examined to identify peak periods. June 2022, March 2023, and August 2024 emerged as the highest revenue-generating months in their respective years, offering insights for seasonal adjustments in sales strategies.

**4. Summary Other Metrics by Top 15 Products:** An overview of the top 15 products provided a comprehensive summary of actual and target quantities, along with actual and target revenue metrics. **Amavirase** achieved the highest revenue among these top products, while **Zyvance** recorded the lowest.

## RECOMMENDATIONS


**1.	Focus on High-Performing Channels (Pharmacy and Retail):**  Given that the Pharmacy channel contributes the largest portion of revenue (52.9%) and Retail leads among sub-channels with 8.2 billion, efforts should be made to further optimize these channels. Strategies such as targeted marketing, customer loyalty programs, and inventory prioritization for these channels can help sustain and potentially increase their revenue contribution.


**2.	Enhance Marketing for Low-Performing Products (Antimalarial and Antiseptics):** With Antimalarial products having the lowest target revenue and Antiseptics showing the lowest actual revenue, a focused marketing campaign or promotional discounts could improve their sales. Additionally, assessing market demand for these products could help in revising their positioning to better align with customer needs. 


**3.	Maximize Regional Opportunities by Leveraging Top-Performing Cities (Butzbach):** **Butzbach**, with the highest quantity among cities (174.23k), represents a strong regional market. Concentrated sales efforts in this region, such as exclusive promotions or enhanced distribution, could further drive growth. Conversely, for cities like **Altenburg** with lower quantities, a more targeted marketing approach may help increase awareness and demand.


**4.	Allocate Resources Based on Manager Performance Metrics:** Managers like **Brittany Bold**, who achieved high target and actual quantities, could be allocated more resources and responsibilities, such as managing larger territories or leading new campaigns. For managers with lower actual quantities, additional training and performance improvement plans could be implemented to ensure consistent achievement of targets across the board.








