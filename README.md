# Sales and Ranking Dashboard

## Overview
This project is a comprehensive sales and ranking dashboard created using **Power BI**. It captures key metrics such as Revenue, Orders, and Average Transaction Price (ATP) while providing detailed insights into product performance, sales channels, and individual salesperson rankings.

## Key Features
- **Revenue by Product Group**: Breakdown of total revenue generated by different product groups such as Wheat Flour, Oil, Yeasts, and more.
- **Revenue by Channel**: Highlights revenue contributions across various sales channels (Retail, Distributor, and Online).
- **Orders by Product Category**: Presents a summary of order counts segmented into categories like Food and Drink.
- **Top Salespersons Ranking**: Identifies the top-performing salespeople by revenue and orders.
- **Revenue and Budget by Year**: Visualizes revenue trends compared to budget over the years (2019, 2020, 2021).

## Data Sources
The dashboard integrates data from the following sources:

1. **SalesData.xlsx**: Contains sales records, including Order Number, Product ID, Salesperson ID, Team, Quantity of Items Sold, and Unit Price.
   - File: [SalesData.xlsx](./mnt/data/SalesData.xlsx)

2. **Budget.xlsx**: Provides the revenue and budget data by year, allowing comparison between actual and projected values.
   - File: [Budget.xlsx](./mnt/data/Budget.xlsx)

3. **Product.xlsx**: Offers product details, including Product ID, Group, Category, Supplier, and Unit Cost.
   - File: [Product.xlsx](./mnt/data/Product.xlsx)

4. **Photos.xlsx**: Contains data linking salesperson photos and other visual attributes.
   - File: [Photos.xlsx](./mnt/data/Photos.xlsx)

## Dashboard Elements

### Sales Dashboard (Light Mode)
This dashboard displays a summary of total **Revenue**, **Orders**, and **ATP** (Average Transaction Price). It allows filtering data by manager, supervisor, and salesperson. You can analyze product group performance and sales trends over the years.
![Sales Dashboard Light Mode](./mnt/data/Light_Mode.png)

### Filters Section
A filter pane that allows users to toggle between different years (2019, 2020, 2021) and explore data by manager, supervisor, and salesperson.
![Filtered Dashboard](./mnt/data/Filtered_1.jpg)

### Sales Rankings
Displays the top salespeople in terms of revenue and orders. Carla Ferreira holds the top position with **$4,707,403** in revenue and **9570 orders**.
![Ranking](./mnt/data/Ranking.jpg)

### Detailed Tooltip Insights
Interactive tooltips provide quick access to additional information about the selected metrics. For example, you can view detailed revenue and ATP for specific products like Wheat Flour.
![Tooltip](./mnt/data/Tooltip.png)
![Tooltip 2](./mnt/data/Tooltip_2.png)

## How to Use
1. **Download the Power BI file**: Access the `.pbix` file from this repository.
2. **Open in Power BI Desktop**: Install Power BI Desktop if you don't have it already.
3. **Refresh the Data Sources**: Use the provided `.xlsx` files (SalesData, Budget, Product, Photos) to refresh the data in Power BI.
4. **Interact with the dashboard**: Use the filters and interactive visuals to explore the data.

## Limitations
- The current dashboard is based on **historical data** from 2019 to 2021. For real-time analysis, data sources need to be connected to live systems.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries or support, feel free to reach out to:
- **Email**: your.email@example.com
