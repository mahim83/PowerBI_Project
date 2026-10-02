# E-commerce Sales Dashboard (Power BI)

An interactive Power BI dashboard that analyses e-commerce sales across India, covering revenue, profit, quantity sold, product categories, payment modes and customer geography.

## Files

| File | Description |
|------|-------------|
| `Ecommerce Sales Dashboard.pbix` | Power BI report (open with Power BI Desktop) |
| `Orders.csv` | 500 orders: Order ID, Order Date, Customer Name, State, City |
| `Details.csv` | 1,500 order line items: Order ID, Amount, Profit, Quantity, Category, Sub-Category, Payment Mode |

The two tables are related through `Order ID`.

## Dataset

**Orders.csv**
- `Order ID`, `Order Date` (DD-MM-YYYY), `CustomerName`, `State`, `City`

**Details.csv**
- `Order ID`, `Amount`, `Profit`, `Quantity`, `Category`, `Sub-Category`, `PaymentMode` (e.g. COD, EMI)

## Insights the dashboard supports

- Total sales, profit and quantity (KPIs)
- Sales and profit by category and sub-category
- Revenue by payment mode
- Sales by state and city
- Trends over time by order date

## How to use

1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. Clone or download this repository.
3. Open `Ecommerce Sales Dashboard.pbix`.
4. If prompted, update the CSV source paths via **Transform data > Data source settings**.

## Tools

- Power BI Desktop (data modelling, DAX, visuals)
- CSV data sources
