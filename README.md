# 1. Project Overview
This project performs a deep-dive analysis into three years of sales data for International Breweries across various regions in Africa. The goal was to evaluate profitability, brand performance, and regional market share to provide data-driven recommendations for supply chain and marketing optimization.

Tools Used: Python (Pandas, Matplotlib, Seaborn), Jupyter Notebooks.

# 2. Key Objectives
Profitability Tracking: Analyze profit trends from 2017 to 2019 to identify peak growth periods.

Brand Portfolio Analysis: Identify the most and least profitable brands within the product line.

Regional Market Intelligence: Determine which territories (Anglophone vs. Francophone) and specific countries drive the highest revenue.

Operational Insights: Evaluate the performance of sales personnel and logistics (plant costs) to improve operational efficiency.

# 3. Step-by-Step Technical Approach
**Phase I:** Data Wrangling & Cleaning
Data Consolidation: Integrated multi-year sales records into a unified DataFrame for longitudinal analysis.

Feature Engineering: Created new calculated columns for Gross Profit and Profit Margin to better assess financial health.

Quality Assurance: Handled missing values and ensured data type consistency for temporal analysis.

**Phase II:** Exploratory Data Analysis (EDA)
Time-Series Analysis: Aggregated data by year and month to visualize seasonal trends and annual growth rates.

Categorical Aggregation: Used "Group By" operations to compare performance across different brands (e.g., Trophy, Castle Lite, Hero) and countries.

**Phase III:** Data Visualization
Comparative Charts: Leveraged Seaborn and Matplotlib to create bar charts comparing regional profits and pie charts for market share distribution.

Heatmaps/Statistical Plots: Identified correlations between quantity sold and unit costs to determine price elasticity.

# 4. High-Value Insights & Business Impact
Territory Dominance: Identified whether the Francophone or Anglophone regions generated higher profit, allowing for targeted regional budget allocation.

Product Optimization: Found the top 3 selling brands and recommended a "Sunset Strategy" for the lowest-performing products to reduce inventory costs.

Peak Sales Identification: Pinpointed specific months and years with significant sales spikes, enabling better inventory forecasting for the following fiscal year.
