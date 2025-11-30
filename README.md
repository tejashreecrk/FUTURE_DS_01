# FUTURE_DS_01
Future Interns – Internship Task 1
QUESTION

Analyze e-commerce data to identify best-selling products, sales trends, and high-revenue categories using Power BI.

PROJECT OBJECTIVE
    The main objective of this project is to use Power BI to analyze e-commerce sales data and uncover key business insights.

    The focus is to:
        Identify best-selling products based on total sales.
        Analyze sales trends across years, quarters, and months.
        Determine high-revenue categories and sub-categories.
        Understand customer purchasing patterns and regional sales distribution.

DATASET USED
    A Superstore-style e-commerce dataset containing:
        Orders table (Order ID, Customer ID, Product Name, Category, Sub-Category, Sales, Profit, Quantity, Region, Ship Mode, Order Date)
        People table (Regional Sales Managers)
        Returns table (Returned Order IDs)
    All tables were connected in Power BI using relationships.

PROCESS
    Imported the dataset into Power BI.
    Created relationships among Orders, People, and Returns tables using Order ID and Region fields.
    Performed data cleaning (data types, removing nulls).
    Created DAX measures like:
        Total Sales
        Unique Customers
    Built visuals to analyze:
        Category-wise sales
        Sub-category profit
        Sales by Product Name
        Sales by Ship Mode
        Sales by Region
        Sales trend over Year, Quarter, and Month
        Scatter plot comparing Sales vs Quantity
    Added slicers for Region and Category to enable dynamic filtering.
    Designed a two-page dashboard for insights and trends.

DASHBOARD
    Page 1 – Overview
    Includes visuals such as:
        Total Sales and Unique Customers
        Sales by Category
        Sales by Product Name
        Sales by Ship Mode
        Profit by Sub-Category
        Profit by Ship Mode
        Slicers for Region & Category
    Page 2 – Trends
    Consists of:
        Sales by Year
        Sales by Quarter
        Sales by Month
        Sales vs Quantity Scatter Plot

PROJECT INSIGHTS
    1. Best-Selling Products
    From “Sum of Sales by Product Name” chart:
        Items like Canon imageCLASS 2200, High Speed Automatic Electric Stapler, and Global Troy Executive Leather Chair emerged as top revenue-generating products.
        These products consistently contribute the highest sales volume.
    2. High-Revenue Categories
    The “Sum of Sales by Category” chart shows:
        Furniture has the highest sales.
        Followed by Technology and Office Supplies.
        This indicates strong demand in big-ticket furniture and tech-related items.
    3. Sales Trends
    From page 2 visuals:
        Yearly Trend (2011–2014):
            Sales increased steadily, with the highest sales in 2014.
        Quarterly Trend:
            Q4 shows the highest sales indicating year-end seasonal buying trends.
        Monthly Trend:
            Sales peak in November and December, showing strong holiday demand.
    4. Regional Sales Pattern
        West region shows the highest sales (pie chart).
        Other regions like East and South also contribute significantly.
    5. Customer Insights
        There are 686 unique customers, showing a diverse customer base.
        Higher sales in Furniture and Technology indicate preference for office and business products.
    6. Shipping Behavior
        Standard Class is the most used shipping mode (56% of sales).
        Customers prefer cost-efficient shipping over fast delivery.

FINAL CONCLUSION
    Using Power BI, this project successfully identifies best-selling products, major sales trends, and high-revenue categories.

    Key conclusions:
        Furniture is the top-performing category.
        Canon imageCLASS 2200 and similar products are top-selling items.
        West region is the highest revenue contributor.
        Sales show a strong upward trend, peaking in 2014, with seasonal spikes in Q4 and December.
        Customer base is healthy with 686 unique buyers.
        Shipping data reveals a preference for Standard Class deliveries.
    This dashboard gives a clear understanding of the company’s performance and helps in making data-driven decisions related to inventory planning, product strategy, and marketing.



