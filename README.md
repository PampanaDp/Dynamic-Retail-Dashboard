# Dynamic-Retail-Dashboard
The primary goal of this project is to develop a comprehensive and dynamic dashboard for analyzing retail data. By leveraging various KPIs and visualizations, the dashboard aims to provide insights into sales performance, profitability, product trends, and return analysis. This project is designed to facilitate better decision-making.

## Significance
- **Tracking KPIs**: Monitor crucial metrics like total sales, total profit, order count, and profit margin.
- **Understanding Sales Trends**: Analyze sales trends over time, identify top-performing regions, and assess the effectiveness of different segments.
- **Product Analysis**: Evaluate which product categories and subcategories drive the most sales and profit.
- **Customer Analysis**: Identify top and bottom customers to tailor strategies and optimize engagement.

  ## Data Sources
The dashboard integrates data from three tables:

1. **Orders**: Contains detailed order information, including sales, profit, quantity, category, and market data.
2. **People**: Contains information about individuals and their assigned regions.
3. **Return**: Tracks returned orders along with the corresponding markets.

### Sample Data
**Orders Table:**
| Order ID | Order Date | Ship Date | Ship Mode | Customer ID | Customer Name | Segment | Country | Market | Sales | Quantity | Discount | Profit | Order Priority |
|----------|------------|-----------|-----------|-------------|---------------|---------|---------|--------|-------|----------|----------|--------|----------------|
| CA-2012-124891 | 31-07-2020 | 31-07-2020 | Same Day | RH-19495 | Rick Hansen | Consumer | United States | US | 2309.65 | 7 | 0 | 762.18 | Critical |

**People Table:**
| Person         | Region   |
|----------------|----------|
| Anna Andreadi  | Central  |
| Chuck Magee    | South    |

**Return Table:**
| Returned | Order ID | Market        |
|----------|----------|---------------|
| Yes      | MX-2013-168137 | LATAM |

## Problem Statements Addressed
The dashboard solves the following problem statements:

1. **KPI Calculation**: Calculates total sales, total profit, total quantity, number of orders, and profit margin.

