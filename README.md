# ML-Model---SuperStore---DataSet-
This dataset tracks retail order data for a fictional store called "Superstore." It includes details like: 
Orders  
Customers  
Products  
Shipping  
Sales and Profits

🎯 Goal: Prepare Superstore Data for ML
Let’s assume we want to build a predictive ML model such as:

Predict Profit

Predict Sales

Classify whether an order will be profitable or not (Profit > 0)




| Column Name       | Description                                                                                              |
| ----------------- | -------------------------------------------------------------------------------------------------------- |
| **Row ID**        | Unique identifier for each row.                                                                          |
| **Order ID**      | Unique ID for each customer order. Multiple rows can share an Order ID (if order has multiple products). |
| **Order Date**    | Date the order was placed.                                                                               |
| **Ship Date**     | Date the order was shipped.                                                                              |
| **Ship Mode**     | Shipping method (e.g., First Class, Standard Class).                                                     |
| **Customer ID**   | Unique identifier for a customer.                                                                        |
| **Customer Name** | Name of the customer.                                                                                    |
| **Segment**       | Market segment: *Consumer, Corporate, Home Office*.                                                      |
| **Country**       | Country name (usually just "United States").                                                             |
| **City**          | Customer’s city.                                                                                         |
| **State**         | Customer’s state.                                                                                        |
| **Postal Code**   | Customer’s ZIP/postal code.                                                                              |
| **Region**        | One of: *East, West, Central, South*.                                                                    |
| **Product ID**    | Unique product identifier.                                                                               |
| **Category**      | Product category: *Furniture, Office Supplies, Technology*.                                              |
| **Sub-Category**  | More specific classification (e.g., Chairs, Phones, Binders).                                            |
| **Product Name**  | Full product name.                                                                                       |
| **Sales**         | Revenue generated from the sale (in USD).                                                                |
| **Quantity**      | Number of units sold.                                                                                    |
| **Discount**      | Discount given on the product (e.g., 0.2 for 20%).                                                       |
| **Profit**        | Profit earned from the sale. Can be negative.                                                            |
