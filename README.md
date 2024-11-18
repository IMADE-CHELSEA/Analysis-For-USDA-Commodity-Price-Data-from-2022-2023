# Analysis-For-USDA-Commodity-Price-Data-from-2022-2023
SALES TREND ANALYSIS
PROJECT INTRODUCTION

The task  involves analyzing pricing data for various USDA commodities from 2022 and 2023. This data is provided in an Excel file containing key pricing metrics, such as high, low, and average prices for different commodities across multiple U.S. markets. As a data analyst, our goal is to ingest, clean, transform, and visualize this data using Power BI to uncover insights that can help guide business decisions regarding procurement, pricing strategies, and supply chain management.
Data Overview
The dataset consists of pricing information across 156,617 rows and 15 columns. Key variables include commodity type, pricing data, market location, and product specifics such as origin, variety, and grade. This dataset covers multiple U.S. markets, including Los Angeles, Philadelphia, and Chicago, providing insights into market-specific price variations and commodity-specific trends.
Project Instructions & Approach
1.	Data Quality Assessment:
The first step is to examine the data for cleanliness and usability. This involves checking for missing values, duplicates, or any inconsistencies in the pricing data. We will evaluate whether the data is ready for analysis or if any additional cleaning is required. Key techniques for identifying recurring issues or discrepancies include inspecting for blank fields, verifying the consistency of date formats, and cross-referencing pricing entries across different tables.
2.	Data Transformation:
Once the data quality is confirmed, I merge the two datasets into a single unified table containing all pricing data. This step ensures that all relevant pricing information is consolidated, making it easier to perform analysis and build visualizations.
3.	Key Questions for Stakeholders:
Before proceeding with the creation of the report, we would ask stakeholders the following key questions to ensure the final dashboard addresses the business's priorities:
o	What specific commodities are of the highest interest for decision-making?
o	Are there any market-specific price trends or fluctuations that need to be highlighted?
o	How should seasonality and quarterly trends be incorporated into the analysis?
o	Is there a need for predictive analytics or price forecasting for the upcoming year?

Data Visualizations and Analysis
In this project, we will build visualizations that provide valuable insights into commodity price trends and their fluctuations over time. The following tasks are critical to the success of the report:
1.	Price Change Analysis:
We will create an interactive feature that allows users to specify a date range and see how prices for specific commodities have changed within that timeframe. This will help users identify significant price shifts and better understand price behavior over time.
2.	Year-on-Year (YoY) Price Change:
One of the key analyses will focus on the YoY change in the average market price for tomatoes. This insight will help identify whether tomato prices are trending upwards or downwards, as well as the factors contributing to such changes.
3.	Market-Specific Pricing:
Another visualization will display the sum of the high price for each commodity, broken down by the market. This will give stakeholders a clear understanding of where certain commodities are performing the best in terms of pricing.
4.	Key Performance Indicators (KPIs):
To further guide business decision-making, we will generate additional KPIs, such as average price trends, price volatility, and market share analysis, to provide a more comprehensive view of the market dynamics.

OBJECTIVES
By the end of the analysis, the Power BI report will offer actionable insights into market pricing trends, allowing stakeholders to make informed decisions on procurement, pricing strategies, and inventory management. This project will also highlight areas where improvements can be made, ensuring that the business stays competitive in an ever-changing commodity market.
- Market Analysis: Identify pricing trends and seasonal fluctuations.
- Commodity-Specific Insights: Understand pricing behavior by variety, grade, and organic status.
- Supply Chain Recommendations: Suggest ways to optimize sourcing and reduce costs.
- Future Market Projections: Forecast potential price trends for the upcoming fiscal year.


KEY INSIGHTS AND OBSERVATIONS

1. Overall Price Trends by Commodity
   -  Comparative analysis of average prices for commodities (e.g., avocados, tomatoes) across 2022 and 2023. This chart will highlight the price increases or decreases, helping stakeholders quickly identify trends and focus areas that require improvements.
     ![image](https://github.com/user-attachments/assets/bd2bb1dd-0b44-4c5a-a841-5303f07baea5)


2. Market-Specific Price Variations
   -  Price differences across major U.S. markets like Los Angeles, Philadelphia, and San Francisco. This shows that Chicago is the best-performing market with an average total sale of $721,000 over both years.
 ![image](https://github.com/user-attachments/assets/c1b5b675-cdfc-404b-9d45-370dc898a640)


The Chicago market generated a total $416,000 in the year 2022, It was however noticed that there was a shift in 2023.
![image](https://github.com/user-attachments/assets/2034b9e6-9ade-4593-913f-c9eaa7d95880)

 
This shift represented San Francisco as the highest for the year 2023 with a total average income of $363,000 with Chicago coming second with a revenue of $305,000.The Miami market ranked the lowest in both years with a total revenue of $105,000 in 2022 and a 16% dip with a total of $88,000 in 2023.

 4. Organic vs. Non-Organic Pricing Differences
   - Comparison of organic vs. non-organic product pricing across the dataset. Over the past two years, non-organic produce has consistently generated more income than organic options, driven by its affordability and broad appeal. This highlights non-organic as a stable revenue stream, which we should continue prioritizing. To grow the organic segment, I recommend targeted marketing that emphasizes health and environmental benefits, as well as selective promotions to attract cost-sensitive customers. Additionally, bundling organic with non-organic items can introduce organic products to a wider audience. 
 

5. Price Trends and Quarterly Comparison

The analysis focuses on average prices by commodity across quarters to identify seasonal patterns and price fluctuations.
	•	Q3 Trends (2022 vs. 2023): Certain commodities, such as Brussels sprouts (+43.6%) and celery (+41.0%), saw significant price increases from 2022 to 2023. This trend suggests potential supply or seasonal demand factors driving prices up.
	•	Q4 Trends (2022 vs. 2023): Q4 saw some of the most substantial price swings, notably:
	•	Blueberries: A notable 114.8% increase YoY in Q4, indicating high demand or supply constraints.
	•	Lettuce Varieties: Iceberg, Green Leaf, and Romaine lettuces experienced significant price drops (>60%), possibly due to market oversupply or other external factors impacting lettuce prices.

6. Year-over-Year (YoY) Price Changes

	•	Price Increases: Commodities with significant YoY price increases (e.g., blueberries, Brussels sprouts, celery) may indicate growth in consumer demand or reduced supply availability.
	•	Price Decreases: Notable decreases, especially in Q4 for various lettuce types, highlight items that may have experienced market saturation or increased competition. A comparison of the YoY changes in tomato prices showed a decline of --8.45 % showing a decrease in tomatoes prices in the year 2023 compared to the previous year
<img width="194" alt="image" src="https://github.com/user-attachments/assets/969e064b-f093-4f34-be2b-4e64dee3f795">

![image](https://github.com/user-attachments/assets/e7025289-a5ed-4ebe-93c1-8983b209168a)



  

8. High Volatility Commodities

	•	High-Volatility Items: Lettuce varieties, potatoes, and other seasonal produce showed extreme volatility, particularly in Q4 2023, where prices dropped significantly. This volatility may impact inventory costs and should be closely monitored.

Key Performance Indicators (KPIs)

• Average Price Change: Averages highlight general market trends and help detect abnormal shifts.
• Price Volatility: Commodities with high variability suggest potential risks in sourcing and inventory cost stability.
• Yearly and Quarterly Comparisons: Comparing quarterly trends helps in planning around seasonal fluctuations.



RECOMMENDATIONS
1.	Strategic Sourcing:
	•	High Demand Items: For items like blueberries and Brussels sprouts that saw large price increases, consider securing contracts or exploring alternative suppliers to stabilize costs.
	•	Low-Volatility Items: Focus sourcing efforts on low-volatility commodities to mitigate potential cost fluctuations.
2.	Inventory Planning:
	•	Seasonal Planning: If similar trends are expected for high-demand commodities in Q3 (e.g., celery, Brussels sprouts), pre-emptive purchasing strategies could be beneficial.
	•High-Volatility Commodities: Avoid highly volatile commodities like lettuce, which may impact cost predictability. Stockpiling during low-price periods could reduce costs.
3.	Market and Supplier Diversification
	• Diversifying suppliers for high-volatility or high-demand commodities could help stabilize pricing and reduce dependency on single-source markets.

	4.  Procurement Strategy
•	Optimize Bulk Purchasing: For high-demand commodities, prioritize bulk packaging to save on per-unit costs.
•	Prioritize Local Markets: Leverage local sourcing options to reduce transportation costs.


Conclusion: Analysis of USDA Commodity Price Data (2022-2023)
The USDA commodity price data analysis for 2022 and 2023 provides significant insights into the pricing trends, market fluctuations, and commodity-specific behaviors that shape the agricultural market. Using Power BI, we have transformed the raw data into meaningful visualizations that offer high-level trends and granular insights into the dynamics of various commodities. The data reveals significant seasonal and market-driven fluctuations in commodity pricing, particularly in high-demand products. Implementing targeted sourcing and inventory strategies based on these insights can help manage costs more effectively and ensure supply chain stability. 
![image](https://github.com/user-attachments/assets/524973e4-208a-4707-81cc-32f0eea08b19)

<img width="524" alt="image" src="https://github.com/user-attachments/assets/75dd05a8-4e39-4870-9d53-7309c8e2f548">


 

