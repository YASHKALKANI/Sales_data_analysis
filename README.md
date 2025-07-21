Sales Analysis Project - README
===============================

Description:
------------
This project analyzes sales data from `all_data.csv` to generate clear, actionable business insights directly using Python and CSV workflows.

Included:
---------
1. all_data.csv (your raw sales data)
2. README.md (this documentation)

Analysis Provided:
------------------
Data Cleaning:
- Removed missing and duplicate rows.
- Converted 'Quantity Ordered' and 'Price Each' to numeric.
- Parsed 'Order Date' into datetime.

Feature Engineering:
- Extracted 'Month', 'Hour', and 'City' from available data.
- Calculated 'Sales' for each transaction.

Insights generated:
- **Sales by Month:** Identified peak sales periods.
- **Sales by City:** Highlighted top-performing locations.
- **Hourly Order Patterns:** Revealed peak demand hours.
- **Top Selling Products:** Showed highest-selling products by quantity.
- **Price vs Quantity Scatter:** Assisted pricing and bundling strategies.

How to Use:
-----------
1. Load `all_data.csv` into your Python environment using pandas

2. Use the provided structured Python scripts to:
- Clean and preprocess the data.
- Generate monthly, hourly, and city-wise sales breakdowns.
- Visualize sales trends with matplotlib or seaborn.
- Analyze product demand to optimize inventory and pricing.

Dependencies:
-----------
- Python
- pandas
- matplotlib
- seaborn
