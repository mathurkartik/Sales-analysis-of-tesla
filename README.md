# Sales-analysis-of-tesla
# Tesla EMEA Sales and Service Data Generator

## Overview
This repository contains a set of Python scripts designed to generate realistic pseudo-data for Tesla's sales and service operations in the EMEA (Europe, Middle East, and Africa) region. The generated data is intended for use in data analysis, dashboard creation, and business intelligence projects.

## Scripts

1. `generate_sales_data.py`: Creates sales data including VIN, date, region, product, price, and customer satisfaction.
2. `generate_vehicle_usage_data.py`: Generates vehicle usage statistics such as mileage, charging frequency, and Autopilot usage.
3. `generate_parts_inventory_data.py`: Produces inventory data for various Tesla parts, including costs, quantities, and reorder information.
4. `generate_customer_demographics.py`: Creates demographic data for Tesla customers, including age, income, and environmental concern.

## Features

- Realistic data patterns including seasonal trends and regional variations
- Inflation-adjusted pricing for vehicles and parts
- Varied distributions for vehicle usage and customer demographics
- Inventory data reflecting different characteristics of various parts
- Data suitable for creating meaningful KPIs and insightful visualizations

## Usage

1. Ensure you have Python 3.x installed along with the required libraries (pandas, numpy).
2. Run the scripts in the following order:
- python generate_sales_data.py
- python generate_vehicle_usage_data.py
- python generate_parts_inventory_data.py
- python generate_customer_demographics.py
3. The scripts will generate CSV files in the same directory:
- `tesla_sales_data_with_vin.csv`
- `tesla_vehicle_usage_data.csv`
- `tesla_parts_inventory_data.csv`
- `tesla_customer_demographics.csv`

## Data Description

### Sales Data
- Date range: 2020-01-01 to 2023-12-31
- Regions: North Europe, South Europe, Central Europe, UK
- Products: Model S, Model 3, Model X, Model Y
- Includes: VIN, sale date, price, customer satisfaction

### Vehicle Usage Data
- Linked to sales data via VIN
- Includes: average daily mileage, charging frequency, Supercharger usage, Autopilot usage, annual mileage

### Parts and Inventory Data
- Various Tesla parts with different characteristics
- Includes: quantity, reorder point, lead time, cost, supplier information

### Customer Demographics
- Linked to sales data via VIN (used as CustomerID)
- Includes: age, income, occupation, family size, previous EV ownership, environmental concern

## Intended Use
This data is designed for:
- Creating dashboards and visualizations in tools like Tableau
- Practicing data analysis and business intelligence techniques
- Simulating realistic business scenarios for Tesla's EMEA operations

## Note
This is pseudo-data generated for educational and practice purposes. It does not represent actual Tesla sales or customer data.

## Contributing
Feel free to fork this repository and submit pull requests with improvements or additional features.

## License
This project is open-source and available under the MIT License.
