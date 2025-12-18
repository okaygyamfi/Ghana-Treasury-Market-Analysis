# Ghana Treasury Market Analysis (2021–2025)

## Executive Dashboards
| Market Overview | Trend & Seasonality Analysis |
|---|---|
| ![Market Overview](visualizations/Market_Overview_Dashboard.png) | ![Trend Analysis](visualizations/Trend_Analysis_Dashboard.png) |

## Project Overview
This project provides an end-to-end data analysis of the Bank of Ghana's Treasury Bill (T-Bill) issuances from January 2021 to September 2025. By leveraging **Python** for engineering and **Power BI** for financial modeling, I uncovered critical trends in interest rates, yield spreads, and market volatility during a historic period of economic adjustment in Ghana.

## Tech Stack
- **Data Engineering:** Python (Pandas) in VS Code
- **Visualization:** Power BI Desktop (DAX)
- **Environment:** Jupyter Notebooks
- **Audit:** Automated Monday-tender compliance verification

## Project Structure
- `data/`: Raw and processed CSV datasets.
- `notebooks/`: Python scripts for data transformation and statistical auditing.
- `visualizations/`: Power BI `.pbix` source file and high-resolution dashboard exports.
- `report/`: Formal PDF Executive Summary and Recommendations.

## Key Findings & Insights

> ### 1. The Yield Hierarchy
> * **Dominant Asset:** The **364-Day Bill** emerged as the most lucrative short-term instrument (Avg: **25.1%**).
> * **Risk Premium:** A clear "normal" yield curve is established, with a **3.7% premium** for 1-year commitments over 3-month holdings.

> ### 2. Market Stress & Spread Analysis
> * **Peak Stress (2023):** The yield spread reached a massive **4.5** peak in 2023, indicating extreme liquidity pressure.
> * **Stabilization:** As of 2025, the spread has cooled to **1.8**, suggesting a return to macroeconomic normalcy.

> ### 3. The "December Effect" (Seasonality)
> * **Optimal Entry:** **December** historically offers the highest average rates (**27.40%**).
> * **Fiscal Cycle:** Yields consistently ramp up in **Q4 (Oct–Dec)**, likely due to end-of-year government budgetary pressures.

## Data Quality & Engineering
During the Python engineering phase, I conducted a **Monday-tender audit**. The audit confirmed **100% alignment** with the Bank of Ghana's weekly issuance cycle across all 248 records. 

**Custom Features Engineered:**
- **Asset Class Mapping:** Categorized securities into 'Bills' and 'Bonds' for portfolio-level aggregation.
- **Time Intelligence:** Extracted chronological features to identify the "December Effect."
- **Spread Metrics:** Calculated the "Wait Bonus" (364-Day vs 91-Day) to track investor risk appetite.

## How to Use
1. **Clone** this repository.
2. **Review** the `notebooks/` folder to see the data audit and transformation logic.
3. **Interact** with the dashboard by opening the `.pbix` file in the `visualizations/` folder.
4. **Read** the full analysis in the `report/` folder.

