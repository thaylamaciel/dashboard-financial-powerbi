# Financial Dashboard | Power BI

## Project Overview
This project features an interactive financial dashboard built to give a clear, high-level view of company performance. It shows key metrics like revenue, costs, net results, and profit margins over time. The goal was to take raw transaction logs and turn them into simple, visual insights that help monitor business health and identify spending trends.

"C:\Users\49419718840\Pictures\Screenshots\project_photo.png"

## Tools and Workflow
* **Power BI Desktop:** Built the visual layout, designed the data model, and configured interactive report elements.
* **Power Query (M):** Handled the data preparation steps:
  * Cleaned up raw dataset fields and fixed formatting issues.
  * Added a custom date reference structure.
  * Standardized month names to English while mapping them to numerical values to keep everything in chronological order.
* **DAX:** Wrote key performance measures:
  * **Revenue:** Total incoming cash flow across all recorded transactions.
  * **Costs:** Combined total of operational and direct business expenses.
  * **Results:** Net profit or loss calculated as total revenue minus costs.
  * **Profit Margin:** Efficiency ratio showing net results as a percentage of overall revenue.

## Main Visuals

**Revenue vs. Costs**
A stacked column chart comparing total monthly earnings directly against monthly spending. It gives a quick look at cash flow balance throughout the year.

**Results By Month**
A waterfall chart showing monthly net gain or loss. Green bars highlight profitable months, while red bars clearly point out months where expenses exceeded revenue.

**Cost Breakdown**
* **By Criteria:** A donut chart dividing costs into recurring, fixed, variable, and one-time payments.
* **By Category:** A horizontal bar chart ranking total expenses across departments like Production, Direct Costs, Administration, and Indirect Costs.
