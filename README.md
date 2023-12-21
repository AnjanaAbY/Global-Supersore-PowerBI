# Global Superstore dashboard

## Overview

Welcome to the Power BI project for the global store dataset! This project provides a detailed report on sales transactions across branches worldwide. It includes various visualizations to help stakeholders analyze and understand key aspects of the business.

## Table of Contents

- [Getting Started](#Getting_Started)
- [Data Cleaning](#data-cleaning)
- [Visual Segmentation](#visual-segmentation)
- [Shipping Analysis](#shipping-analysis)
- [Sales Visualizations](#sales-visualizations)
- [Tables](#tables)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get started with the Power BI project, follow these steps:

1. Download the Power BI file from [insert_link_here].
2. Open the file using Power BI Desktop.
3. Explore the various visualizations and tables to gain insights into sales transactions.

### Prerequisites

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/)

## Data Cleaning

The dataset has undergone basic data cleaning to ensure accuracy and consistency. Cleaning steps include [mention specific data cleaning steps if relevant].

## Visual Segmentation

- **Region, Country, and Market Slicers:**
  - Utilize slicer visualizations to segment data by region, country, and market for a focused analysis.

## Shipping Analysis

- **Shipping Percentage by Ship Mode:**
  - A DAX formula has been applied to calculate the percentage of shipping costs based on ship mode.
    ```DAX
    DIVIDE(SUM('Orders'[Shipping Cost]), CALCULATE(SUM('Orders'[Shipping Cost]), ALL('Orders'[Ship Mode])))
    ```

## Sales Visualizations

- **Sales by Region (Map):**
  - Use the map visualization to visually represent sales across different regions.
  
- **Sales by City (Stacked Column Chart):**
  - Analyze sales trends in various cities using the stacked column chart.

- **Sales by State (Map):**
  - Visualize sales distribution across different states using the map.

- **Sales by Market (Stacked Bar Chart):**
  - Understand sales performance by market through the stacked bar chart.

## Tables

- **Tables for Detailed Information:**
  - Supporting tables have been created for each visualization, providing detailed metrics such as total sales, average sales, etc.

## Contributing

If you would like to contribute to this project, please follow our [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

