# TATA CLIQ Sales Data Analysis
## Project Overview

This project analyzes TATA CLIQ sales data to identify meaningful patterns and trends in sales performance. The analysis focuses on revenue generation, customer behaviour, order patterns, product performance, and sales trends.

The project uses Python for data cleaning, transformation, exploratory data analysis (EDA), and visualization. Four datasets — Customers, Orders, Order Details, and Products — were cleaned, transformed, and combined to perform the analysis.

## 🛠️ Tools & Technologies
* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

## Dataset
The project uses four CSV datasets:

* **Customers** – Customer details such as customer ID, name, city, and signup date.
* **Orders** – Order information including order ID, customer ID, order date, and payment method.
* **Order Details** – Product-level transaction details such as quantity and unit price.
* **Products** – Product information including product name, category, and base price.

The datasets are connected using common identifiers such as `customer_id`, `order_id`, and `product_id`.

## 🔍 Analysis Performed
### Data Cleaning
* Loaded and inspected all datasets using Pandas.
* Checked dataset structure, data types, and missing values.
* Prepared the datasets for further analysis.

### Data Transformation
* Extracted Month, Year, Day, and Quarter from date columns.
* Created a Revenue column using:
`Revenue = Quantity × Unit Price`
* Merged the relevant datasets using common identifiers.
  
### Exploratory Data Analysis
The analysis covers:
* Overall revenue and sales performance
* Product performance
* Category-wise revenue
* Customer purchasing behaviour
* Customer revenue contribution
* City-wise sales performance
* Payment method analysis
* Monthly sales trends

## 📊 Key Insights
* Total revenue generated was approximately *₹18 crore*.
* Wireless Mouse was the most sold and highest revenue-generating product.
* Smartphone was the highest revenue-generating category.
* Laptop was the lowest revenue-generating category.
* Delhi had the highest number of customers and the highest revenue contribution.
* A relatively small group of customers contributed a significant share of total revenue.

## 📈 Visualizations
The project includes visualizations for:
* Top Category by Revenue
* Top Products by Revenue
* Top Products by Quantity
* Top Customers by Revenue
* Monthly Sales
* Top Customers by Quantity
* Top Payment Methods

## 📁 Project Structure

TATA-CLIQ-Sales-Analysis/
│
├── Data/
│   ├── customers.csv
│   ├── orders.csv
│   ├── order_details.csv
│   └── products.csv
│
├── TATA_CLIQ_Sales_Analysis.ipynb
│
├── TATA SALES PROJECT.docx
│
└── README.md


## 🏁 Conclusion

This project demonstrates how Python can be used to transform raw sales data into meaningful business insights through data cleaning, transformation, exploratory analysis, and visualization.

The analysis provides insights into high-performing products, valuable customers, leading cities, category performance, and purchasing patterns.
