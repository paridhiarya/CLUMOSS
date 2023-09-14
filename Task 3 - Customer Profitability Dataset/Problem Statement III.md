# Power BI Task III

### Dataset
This week’s challenge uses the ‘Customer Profitability Sample’ provided by the Power BI team. The
model is already made (no Power Query requirements), but you’ll need to do a bit of DAX work to
complete the challenge.

### Problem Description:
- Add a text box to populate a page title dynamically. The title should include the selected metric and
the number of top products selected.
- Allow the user to choose the number of top products to be included in the report (1 – 5).
- Allow the user to choose the metric to be used for the report visuals. The options should include:
  1. '# of Customers'
  2. Gross Margin
  3. Gross Margin % ([GM%] in the model)
  4. Total COGS
  5. Total Revenue
- Add a table that shows the selected metric by-product for the top N products
- Add a line chart that shows the selected metric for the top N products by month
- Add a bar chart that shows the selected metric for the top N products by industry
- Add a map (your choice of map type) that shows the selected metric for the top N products by state
- Populate the title of all 4 main visuals by using DAX to contain the number of products and metric selected dynamically by the user
