# Energy Cost Optimization Model

![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white) 

This project is a financial modeling and data analysis tool designed to optimize annual energy consumption costs. It evaluates real-world consumption patterns to determine the most cost-effective electricity tariff among three structural options: Fixed, Monthly, and Hourly rates.

The core technical focus of this project is data normalization and logical simulation. It demonstrates how raw, unstructured text can be processed into a structured dataset to feed a financial calculation engine and drive business intelligence decisions.

## Data Transformation Pipeline

The initial source data consisted of unstructured, concatenated text strings. To process this, a comprehensive data cleaning pipeline was engineered natively within Excel:

1. **String Cleansing:** Implemented nested text functions to programmatically remove delimiters, irregular whitespace, and non-numeric characters.
2. **Pattern Extraction:** Isolated critical data points (dates, time logs, and kWh energy usage) from complex text blocks.
3. **Data Standardization:** Converted the raw string inputs into a strict, structured tabular format suitable for financial modeling.

![Data Cleaning Process](cleaning_process.png)
Transformation pipeline from raw data input strings to structured columns.

## Financial Modeling & Logic

With the structured dataset, a calculation engine was built to simulate operational costs under the three distinct pricing structures. The architecture utilizes nested logical functions and matrix lookups to dynamically apply tariff rates based on the specific time and volume of consumption.

![Cost Calculation Model](cost_calculation_model.png)
Financial model comparing the three tariff structure scenarios based on cleaned consumption data.

## Key Insights & Dashboard

The final output is an executive dashboard that synthesizes the calculation engine's results. The analysis conclusively identified the Hourly Plan as the most profitable option. The data revealed a specific consumption pattern where the user's highest energy draw occurs during off-peak hours, aligning perfectly with the lowest dynamic rate brackets ($0.10 - $0.12/kWh).

![Dashboard Preview](dashboard_electricity.png)
Executive dashboard visualizing consumption patterns and final cost optimization recommendation.
