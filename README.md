# E-commerce Customer Data Analysis

## Project Overview
This project aims to perform an in-depth **Exploratory Data Analysis (EDA)** on customer data from an e-commerce platform. 
The primary goal is to uncover patterns, behaviors, and insights to inform strategic decisions for improving customer engagement, boosting sales, and enhancing retention.

## Project Structure
- **Eda/**: Contains all EDA-related scripts, reports, and visualizations.
  - `eda.Rmd`: An R Markdown file for generating the EDA report.
  - `eda.html`: The rendered HTML report of the EDA analysis.

## Data Description
The analysis uses two datasets:
1. **Traffic Data**: Contains information on customer traffic sources, user behavior metrics, and revenue data.
2. **Orders Data**: Provides order details such as customer ID, order status, payment method, and pricing information.

> **Note**: The actual data files are not included in this repository to protect customer privacy.

### Key Features
- **Traffic Data**:
  - `Source / Medium`: Traffic sources (e.g., Google CPC, YouTube Social).
  - `Users`, `New Users`, `Sessions`, `Bounce Rate`: User engagement metrics.
  - `Transactions`, `Revenue`: Ecommerce conversion metrics.

- **Orders Data**:
  - `customer_unique_id`, `order_id`: Unique identifiers for customers and orders.
  - `item_quantity`, `selling_price`, `shipping_fee`: Order details.
  - `payment_method`, `order_status`: Payment and order status information.

## Objectives of the Analysis
1. **Customer Segmentation**: Identify different customer segments based on demographics and behavior for targeted marketing.
2. **Behavioral Patterns**: Identify trends in purchase frequency, spending, and product preferences.
3. **Customer Journey Insights**: Map the stages of the customer journey to pinpoint potential improvement areas.

## Key Findings and Insights
The analysis aims to reveal:
- **Customer Segmentation**: Clustering customers by buying frequency and spending for personalized marketing.
- **Behavioral Patterns**: Insights into trends in purchase frequency and spending habits, indicating how factors like shipping fees influence customer decisions.
- **Customer Journey Insights**: Mapping the stages of the customer journey highlights potential areas for improvement, particularly around shipping costs, which impact customer retention and satisfaction.

More in the presentation file.

## Technologies and Tools
- **R**: For data manipulation, visualization, and reporting.
- **R Markdown**: To create reproducible reports combining code, output, and explanations.
- **ggplot2**: For data visualization.
- **dplyr** and **tidyverse**: For data wrangling and manipulation.

