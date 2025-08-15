#  📌 Problem Statement

The goal of this dashboard is to provide a comprehensive view of production performance across different categories, managers, and time periods.
It helps management to:\
Identify cost-heavy production types.

- Track managerial performance.
- Monitor monthly production trends.
- Compare average production costs for each product type.

By consolidating these KPIs into a single view, decision-makers can optimize production planning and improve cost efficiency.

## DashBoard Preview
<img width="1096" height="792" alt="Image" src="https://github.com/user-attachments/assets/ba7e37a6-58b5-4239-93b6-fb3c58df2204" />


#  🛠 Steps Followed
Step 1 : Imported production, cost, and managerial task data into  Excel.\
Step 2 : Cleaned and standardized the dataset — corrected category names, formatted dates, removed nulls.

Step 3 : Created Pivot Tables for:

- Total cost by production type
- Tasks done by each manager
- Units produced over time (monthly)
- Average production cost by product type

Step 4 : Added Slicers for interactive filtering by:

- Region
- Gender
- Quarter
- Age Group

Step 5 : Built the following visualizations:

- 3D Column Chart for Total Cost by Production Type
- Horizontal Bar Chart for Managerial Task Count
- Line Chart for Monthly Units Produced

Pie Chart for Average Production Cost by Product Type

Step 6 : Designed a one-page dashboard with an interactive layout linking slicers to all visuals.


   # 📈 Insights from the Dashboard
[1] Cost Analysis
Automobiles incur the highest cost at over $1.2M.

Electronics are the least expensive production type.

[2] Managerial Performance
Nancy Grey leads with 37 tasks completed, far ahead of peers.

Several managers completed fewer than 10 tasks, indicating a possible productivity gap.

[3] Monthly Production Trends
Production peaked in October 2023 with 4,803 units.

Lowest production recorded in September 2023 (771 units) and May 2024 (1,528 units).

[4] Cost Efficiency
Furniture has the highest average production cost at 180.4 per unit.

Machinery is the most cost-efficient at 109.0 per unit.


  #  📂 Tools & Techniques Used


Microsoft Excel: Pivot Tables, Slicers, Conditional Formatting, 3D and 2D Charting.\
Data Visualization: Column, Bar, Line, and Pie charts.\
Business Intelligence: KPI tracking, interactive slicers, performance benchmarking.

   # 📌 Business Impact

Time Efficiency: Automated reporting reduced preparation time from hours to minutes.\
Better Decision-Making: Real-time filtering allows quick identification of key issues.\
Cost Control: Clear visibility into cost-heavy categories aids in budget optimization.


  # 🚀 How to Use

Download the Excel file from this repository.\
Open the Dashboard sheet.\
Use slicers to filter by Region, Gender, Quarter, or Age Group.\
Watch all charts update instantly to reflect the selected filters.

#  Following inferences can be drawn from the dashboard:

## [1] Total Cost by Production Type
Automobiles ≈ 1.2M (highest)\
Machinery ≈ 1.0M\
Furniture ≈ 0.8M\
Electronics ≈ 0.7M

### Thus, focus cost-optimization efforts on Automobiles first.

## [2] Tasks Done by Managers (Counts) :
Nancy Grey = 37\
Jane Smith = 18\
John Doe = 13\
Mike Brown = 11\
Andrew Blue = 10\
Laura Black = 8\
Emily Davis = 6, Chris Green = 6, David White = 6\
Sarah Lee = 5

### Thus, there is a visible productivity gap, rebalance workload and review processes for low-outliers.

## [3] Total Units Produced (Monthly Trend) :
Peak: Oct 2023 = 4803 units\
Other high months: Nov 2023 = 3103, Jun 2024 = 3537\
Dips: Sep 2023 = 771, May 2024 = 1528, Jul 2024 = 1536, Sep 2024 = 1379

### Seasonal planning, maintenance windows, and staffing should account for these highs and lows.

## [4] Average Production Cost by Product Type
Furniture = 180.4 (highest)\
Automobiles = 140.9\
Machinery = 109.0\
Electronics = 108.4 (lowest)

### Prioritize process/ sourcing improvements for Furniture to reduce per-unit cost.
