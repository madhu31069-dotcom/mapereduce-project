# Sales Data Analysis Project

## Project Title
Sales Data Analysis using Python

## Objective
This project analyzes sales data from a CSV file and generates a sales report. It calculates:
- Total Sales
- Sales by City
- Top Selling Products
- Sales by Category

## Technologies Used
- Python 3
- Pandas
- VS Code

## Project Structure

```
SalesAnalysisProject/
│
├── main.py
├── data_loader.py
├── analyzer.py
├── report.py
├── sales_data.csv
├── output/
│     └── report.txt
└── README.md
```

## Files Description

### sales_data.csv
Contains the sales records.

### data_loader.py
Reads the CSV file using Pandas.

### analyzer.py
Performs data analysis:
- Total Sales
- City-wise Sales
- Product-wise Sales
- Category-wise Sales

### report.py
Creates and saves the report into `output/report.txt`.

### main.py
Main file that executes all modules.

## Requirements

Install Pandas before running the project:

```bash
pip install pandas
```

## How to Run

Open the project in VS Code.

Run:

```bash
python main.py
```

## Sample Output

```
========== SALES REPORT ==========

Total Sales : Rs.293000

------ Sales By City ------

Bangalore     68000
Chennai      201600
Coimbatore    25000
Hyderabad     18000
Madurai        3500
Salem          2400

------ Top Selling Products ------

Mouse        9
Keyboard     5
Laptop       3
Phone        3
Monitor      2

------ Sales By Category ------

Accessories     11900
Electronics    281100
```

## Conclusion

This project demonstrates how Python and Pandas can be used to analyze real-world sales data. The generated report helps understand total sales, city-wise performance, product demand, and category-wise revenue.
