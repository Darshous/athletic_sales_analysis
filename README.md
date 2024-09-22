
# Athletic Sales Analysis

## Project Overview

The **Athletic Sales Analysis** project is designed to analyze sales data over two years, focusing on identifying key sales trends and performance metrics. The primary goal of the analysis is to aggregate sales data by various time periods, such as daily and weekly totals, to better understand the dynamics of athletic product sales across different retailers, regions, and product categories.

## Data Source

The analysis is based on the data provided in the `athletic_sales_analysis.ipynb` file. This file contains processed sales data from 2020 and 2021, including key information such as the date of sale, retailer details, geographic location, product type, sales method, and financial metrics like total sales and operating profit.

## Objectives

The main objectives of this project are:
1. **Data Integration**: Combine and clean sales data from 2020 and 2021 to create a unified dataset for analysis.
2. **Date Processing**: Ensure that the sales dates are correctly formatted to allow for accurate time-based aggregation.
3. **Sales Aggregation**: Aggregate sales data to calculate total sales for each day and week, identifying periods with the highest sales.
4. **Trend Analysis**: Apply filters and aggregation methods to explore sales trends by specific criteria, such as product type or sales method.
5. **Comparison with Expected Results**: Evaluate the aggregated sales data against expected outcomes to identify any discrepancies and understand their causes.

## Challenges Encountered

During the analysis, several challenges were addressed:
- **Multiple Transactions on the Same Date**: The dataset includes multiple transactions for the same date, leading to higher aggregated totals than expected. This required careful filtering and aggregation to ensure the accuracy of the analysis.
- **Aggregation Logic**: The analysis needed to be carefully structured to match the expected results, which involved considering how data was grouped and summed.

## Methodology

The analysis involved the following key steps:
- **Data Preparation**: Sales data from the two years was combined and cleaned to create a consistent dataset. This step was crucial for ensuring that subsequent analyses were based on accurate and complete data.
- **Date Conversion**: The `invoice_date` column was converted to a proper date format, enabling time-based aggregation.
- **Sales Aggregation**: A pivot table was created to sum total sales by day and by week. This allowed for the identification of key dates and periods with the highest sales volumes.
- **Filtering and Analysis**: Additional filters were applied to the data to analyze specific subsets, such as sales by product type or sales method, to gain deeper insights into sales trends.

## Key Findings

The analysis identified several key sales trends, including:
- **Peak Sales Periods**: Certain dates and weeks were highlighted as having the highest sales, indicating periods of strong consumer demand.
- **Discrepancies in Expected vs. Actual Results**: Through careful aggregation and filtering, the analysis revealed discrepancies between expected sales figures and actual results, which were then addressed and explained.

## Conclusion

The **Athletic Sales Analysis** project demonstrates the importance of meticulous data processing and analysis in understanding sales trends. By carefully aggregating and analyzing the data, the project provides valuable insights into sales performance across different dimensions, such as time, product type, and sales method.

## Future Directions

Future work could involve:
- **Further Exploration**: Expanding the analysis to explore sales trends across different regions or product categories in more detail.
- **Data Visualization**: Developing visual representations of the findings to enhance the communication of key insights.
- **Predictive Analytics**: Leveraging the insights gained to build predictive models for forecasting future sales trends.

*** Prepaired by ChatGPT 4.o
