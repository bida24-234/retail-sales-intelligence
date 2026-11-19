# Retail Sales Intelligence – Data Dictionary

This document describes the fields contained in the raw and processed datasets used in the Retail Sales Intelligence project.

## Sales

| Field | Description |
|---|---|
| Order Number | Unique ID for each order |
| Line Item | Identifies individual products purchased as part of an order |
| Order Date | Date the order was placed |
| Delivery Date | Date the order was delivered |
| CustomerKey | Unique key identifying which customer placed the order |
| StoreKey | Unique key identifying which store processed the order |
| ProductKey | Unique key identifying which product was purchased |
| Quantity | Number of items purchased |
| Currency Code | Currency used to process the order |

## Customers

| Field | Description |
|---|---|
| CustomerKey | Primary key to identify customers |
| Gender | Customer gender |
| Name | Customer full name |
| City | Customer city |
| State Code | Customer state (abbreviated) |
| State | Customer state (full) |
| Zip Code | Customer zip code |
| Country | Customer country |
| Continent | Customer continent |
| Birthday | Customer date of birth |

## Products

| Field | Description |
|---|---|
| ProductKey | Primary key to identify products |
| Product Name | Product name |
| Brand | Product brand |
| Color | Product color |
| Unit Cost USD | Cost to produce the product in USD |
| Unit Price USD | Product list price in USD |
| SubcategoryKey | Key to identify product subcategories |
| Subcategory | Product subcategory name |
| CategoryKey | Key to identify product categories |
| Category | Product category name |

## Stores

| Field | Description |
|---|---|
| StoreKey | Primary key to identify stores |
| Country | Store country |
| State | Store state |
| Square Meters | Store footprint in square meters |
| Open Date | Store open date |

## Exchange Rates

| Field | Description |
|---|---|
| Date | Date |
| Currency | Currency code |
| Exchange | Exchange rate compared to USD |
