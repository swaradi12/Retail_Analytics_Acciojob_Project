# Retail_Analytics_Acciojob

Problem Statement:- 

The objective of this project is to develop a Power BI dashboard using the Retail Database to provide comprehensive insights into the retail business's performance. The dashboard will focus on sales, product, customer, and demographic analysis, aiming to facilitate data-driven decision-making, optimize sales strategies, and enhance customer experiences. The goal is to empower retail stakeholders with actionable insights, enabling them to identify top-selling products, customer preferences, and target demographics. The dashboard will offer valuable insights and recommendations for targeted marketing, inventory optimization, and personalized customer experiences. The final deliverables will include a report and presentation showcasing the dashboard's findings and significance, serving as a powerful tool for retail stakeholders to improve business strategies and achieve success in the competitive retail market.

Dataset Description :-

The retail dataset provided contains valuable information about a retail company, capturing various aspects of its operations. This dataset is essential for understanding and analyzing the company's offices, employees, customers, products, product lines, orders, order details, and payments.

Table Explanations:-

Offices Table -

This table stores information about the different offices of the retail company, including the office code, city, phone number, address, state, country, postal code, and territory. Each office is uniquely identified by its office code. Represents different retail offices or stores of the business. Each office is identified by a unique office code(ID) and may contain attributes like office name, location, and contact information.

Employees Table-

The employees table holds data about the company's employees. It includes fields such as employee number (a unique identifier for each employee), last name, first name, extension, email address, office code (identifying the office where the employee works), reportsTo (the employee number of the person to whom the employee reports), and job title. Stores data about employees working in the retail business. Each employee is identified by a unique employee number (ID) and contains attributes like employee name, job title, and contact details.

Customers Table-

This table contains information about the retail company's customers. It includes fields like customer number (a unique identifier for each customer), customer name, contact last name, contact first name, phone number, address, city, state, postal code, country, sales representative employee number (identifying the employee responsible for the customer), and credit limit. Stores information about individual customers who make purchases from the retail business. Each customer is identified by a unique customer number (ID) and contains attributes like customer name, contact details, and demographic information.

Products Table-

The products table stores details about the various products sold by the retail company. It includes information such as the product code (a unique identifier for each product), product name, product line (categorization of the product), product scale, product vendor, product description, quantity in stock, buy price, and Manufacturer's Suggested Retail Price (MSRP). Contains details about the products offered by the retail business. Each product is identified by a unique product code (ID) and includes attributes such as product name, description, and price.

Product Lines Table -

This table is used to describe the different product lines (category of products) available in the company's inventory. It includes fields such as the product line name, text description, HTML description (for web-based content), and an image (stored as a BLOB) to represent the product line visually. Represents different product categories or product lines offered by the retail business. Each product line is identified by a unique product line ID and may contain attributes like product line name and description.

Orders Table-

The orders table stores data related to customer orders. It includes information like the order number (a unique identifier for each order), order date, required date, shipped date, order status (using an ENUM for predefined statuses), comments, and customer number (identifying the customer who placed the order). Represents individual orders placed by customers. Each order is identified by a unique order number(ID) and contains attributes like order date, customer number(ID) (foreign key), and office code(ID) (foreign key) from where the order was placed.

Order Details Table-

This table contains information about the individual items (line items) included in each order. It includes fields such as the order number (linking to the orders table), product code (linking to the products table), quantity ordered, price per item, and order line number. This table establishes a many-to-many relationship between orders and products. It serves as a junction table, linking orders to the products they contain. It contains foreign keys for order number (ID) and product code (ID).

Payments Table-

The payments table stores details about payments made by customers. It includes fields such as the customer number (ID) (linking to the customers table), check number, payment date, and the payment amount. Stores information about payments made by customers for their purchases. Each payment is identified by a unique payment ID and includes attributes like payment amount, payment date, and payment method.
