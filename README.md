# mysql-view-task7

# Retail Management System – SQL Views

This file contains example SQL views that simplify data retrieval and improve security by abstracting complex queries.

Views are powerful tools for:
- Simplifying queries for reports and dashboards
- Restricting sensitive data access
- Improving query readability

## What's Included

The views demonstrate:

- Combining tables for reporting
- Filtering recent or high-value data
- Summarizing aggregates
- Isolating specific subsets of data

## View Highlights

- `view_customer_orders`: Joins orders with customer and product details
- `view_product_stock_summary`: Shows category-wise stock and pricing
- `view_high_value_orders`: Filters orders above a threshold amount
- `view_recent_orders`: Orders placed in the last 30 days
- `view_supplier_products`: Lists products with supplier names and prices
- `view_customer_order_totals`: Total spend and order counts per customer
- `view_low_stock_products`: Products running low on stock
