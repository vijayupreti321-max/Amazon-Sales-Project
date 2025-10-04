# Amazon Sales Analysis

This project analyzes Amazon sales data to provide insights into the sales performance of various products over time. The dataset includes information about products sold, their prices, quantities, and the locations where they were sold.

## Project Overview

In this project, we use Python and libraries such as **Pandas**, **Matplotlib**, **Seaborn**, and **Numpy** to analyze and visualize Amazon sales data. The dataset contains 80,000 records with the following columns:
- **Order ID**: Unique identifier for each order.
- **Order Date**: Date when the order was placed.
- **Product**: Name of the product sold.
- **Price**: Price of the product in dollars.
- **Quantity**: Quantity of the product sold.
- **City**: City where the order was shipped.
- **State**: State where the order was shipped.

## Key Insights

- **Total Sales**: The total sales amount across all transactions is **$7,078,209.08**.
- **Average Sales per Transaction**: The average sales per transaction is **$224.36**.
- **Top-Selling Products**: The products with the highest sales are:
  - Alexa
  - Kindle
  - Fire Stick
- **Lowest-Selling Products**: The products with the lowest sales are:
  - Echo Dot
  - Ring Doorbell
  - Smart Plug
- **Cities with Highest Sales**: The cities that generated the highest sales are:
  - Phoenix
  - Los Angeles
  - Philadelphia
- **States with Highest Sales**: The states that generated the highest sales are:
  - New York (NY)
  - California (CA)
  - Arizona (AZ)
  
## Sales Trends

The project also explores **yearly sales trends**, showing how the sales evolved over time. The year with the highest sales was **2020**, while **2022** saw the lowest sales.

### Visualizations

The project includes various visualizations to better understand the data:
- **Pie chart** showing sales by product.
- **Line chart** showing sales by city.
- **Bar chart** showing sales by state.
- **Heatmap** showing the maximum quantity of products sold by Order ID.
- **Line chart** showing the sales trends over the years.

## Technologies Used

- **Python**: The main programming language for analysis.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib** and **Seaborn**: For data visualization.
- **Numpy**: For numerical operations.

## Data Preprocessing

The dataset was cleaned and preprocessed in the following steps:
1. **Data Loading**: The dataset was loaded into a pandas DataFrame.
2. **Date Conversion**: The `Order Date` column was converted from string format to a `datetime` format.
3. **Handling Missing Data**: Any rows with missing `Order Date` values were dropped.
4. **Total Amount Calculation**: A new column `Total Amount` was added, calculated as the product of `Price` and `Quantity` for each row.

## Future Work

Future improvements to this project could include:
- Analyzing customer demographics and their purchasing patterns.
- Predicting future sales based on historical data using machine learning models.
- Analyzing the effect of seasonal promotions and sales on the total sales.

## How to Use

1. **Clone the repository**:
   To get started, clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/Amazon-Sales-Analysis.git
