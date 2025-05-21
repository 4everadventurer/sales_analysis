🛍️ Sales Data Analysis

This project analyzes a sales dataset (`sales_data.csv`) using Python and pandas. It provides monthly sales summaries and identifies the top-selling product categories.

📊 Features

- Calculates total amount per transaction
- Extracts month information from dates
- Summarizes monthly sales and order counts
- Identifies top-selling categories based on quantity

🗂️ Dataset

The input file should be named `sales_data.csv` and include at least the following columns:

- `OrderID`: Unique identifier for each order
- `Date`: Date of the order (e.g., 2025-03-15)
- `Quantity`: Number of units sold
- `Price`: Price per unit
- `Category`: Category of the product

Example:

| OrderID | Date       | Quantity | Price | Category     |
|---------|------------|----------|-------|--------------|
| 1001    | 2025-03-15 | 2        | 15.99 | Electronics  |
| 1002    | 2025-03-16 | 1        | 39.99 | Home & Living|

🚀 How to Run

1. Make sure you have Python installed (version 3.7 or higher recommended).
2. Install the required library:

   ```bash
   pip install pandas
