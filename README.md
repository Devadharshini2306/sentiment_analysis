# House Price Dashboard using Python Dash

## Project Overview

This project presents an interactive dashboard developed using Python Dash to analyze house price data.
The dashboard allows users to explore relationships between different features and house prices dynamically.

## Objectives

* Visualize house price data effectively
* Create an interactive dashboard using Python Dash
* Allow users to explore data using dropdown filters
* Understand relationships between features and price

## Tools & Technologies

* Python
* Dash
* Plotly
* Pandas

## Dataset

The dataset used is a house price dataset (`train.csv`) which contains:

* Various numerical features (area, quality, rooms, etc.)
* Target variable: `SalePrice`

## Dashboard Features

* Interactive **Scatter Plot** (Feature vs SalePrice)
* **Dropdown Filter** to select different features
* Dynamic graph updates based on user selection
* Clean and responsive UI design

## Steps Performed

1. Loaded dataset using Pandas
2. Selected numerical columns for analysis
3. Built dashboard layout using Dash
4. Added dropdown for feature selection
5. Implemented callback function for interactivity
6. Created scatter plot using Plotly
7. Styled the dashboard for better visualization

## Key Insights

* House prices increase with living area
* Certain features strongly influence house prices
* Larger houses tend to have higher sale prices
* Interactive dashboard helps in better data exploration

## Output

* Interactive web-based dashboard
* Dynamic visualization of house price relationships

## Project Structure

Task3_Dashboard:
-> dashboard.py
-> train.csv
-> README.md

## How to Run

1. Install required libraries:

id="dashrun1"
pip install dash plotly pandas

2. Run the dashboard:

id="dashrun2"
python dashboard.py

3. Open in browser:

id="dashrun3"
http://127.0.0.1:8050/

## Conclusion

This project demonstrates how Python Dash can be used to build interactive dashboards.
It helps users analyze and visualize data effectively through dynamic and user-friendly interfaces.

## Author

DEVADHARSHINI V
