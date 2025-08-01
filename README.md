# KPMG Data Analysis using Excel

## Course
Data Management and Analysis with MS Excel

## Project Overview
This project analyzes customer demographics, transactions, and new customer data to provide insights into business performance and customer behavior. It involves data cleaning, analysis, and visualization across six tasks using Excel.

## Dataset Description

### 1. Customer Address Dataset
Contains customer addresses and property valuations.  
Columns:  
- customer_id: Unique customer identifier  
- address: Customer street address  
- postcode: Postal code  
- state: State of residence (e.g., New South Wales, QLD)  
- country: Country (Australia for all entries)  
- property_valuation: Integer representing property valuation  

### 2. Customer Demographic Dataset
Contains customer demographics and purchase behavior.  
Columns:  
- customer_id: Unique customer identifier  
- first_name, last_name: Customer's names  
- gender: Customer gender  
- past_3_years_bike_related_purchases: Number of bike purchases in last 3 years  
- DOB: Date of birth  
- job_title: Job title  
- job_industry_category: Industry category  
- wealth_segment: Wealth classification (e.g., Mass Customer)  
- deceased_indicator: Deceased status (Y/N)  
- default: Default status (may include invalid data)  
- owns_car: Car ownership (Yes/No)  
- tenure: Customer tenure  

### 3. Transactions Dataset
Contains transaction details including product and customer info.  
Columns:  
- transaction_id: Unique transaction ID  
- product_id: Unique product ID  
- customer_id: Customer ID making the transaction  
- transaction_date: Date of transaction  
- online_order: Whether order was online (TRUE/FALSE)  
- order_status: Status of order (e.g., Approved)  
- brand: Product brand  
- product_line: Product line (e.g., Standard)  
- product_class: Product class (e.g., medium)  
- product_size: Product size  
- list_price: Listed price  
- standard_cost: Standard cost  
- product_first_sold_date: First sale date of the product  

### 4. New Customer List Dataset
Information about potential new customers.  
Columns:  
- first_name, last_name: Names  
- gender: Gender  
- past_3_years_bike_related_purchases: Number of bike purchases  
- DOB: Date of birth  
- job_title: Job title  
- job_industry_category: Industry category  
- wealth_segment: Wealth classification  
- deceased_indicator: Deceased (Y/N)  
- owns_car: Car ownership  
- tenure: Tenure  
- address, postcode, state, country: Location details  
- property_valuation: Property valuation  
- Rank: Ranking based on criteria  
- Value: Potential value  

## Tasks

### Task 1: Data Cleaning (12 Marks)
Prepare datasets for analysis by cleaning inconsistencies:  
- Remove duplicate records from Address data and standardize state names.  
- Correct erroneous and missing data in Demographics including gender representation.  
- Standardize date format and remove incomplete records in Transaction data.  
- Standardize address, gender, job titles, and industry categories in New Customer data.  

### Task 2: Customer Segmentation (12 Marks)
Segment customers to identify key groups:  
- By wealth segment: count customers and average tenure.  
- By gender: count customers and average bike-related purchases.  
- By job industry: count customers and analyze wealth distribution within industries.  

### Task 3: Transaction Analysis (12 Marks)
Analyze transaction trends and patterns:  
- Sales trends: chart total sales per month and identify seasonal spikes.  
- Product performance: total sales by brand and average sales price by product line.  
- Customer behavior: identify top 10 customers by transaction value and average purchases per customer.  

### Task 4: New Customer Insights (12 Marks)
Analyze potential new customers:  
- Demographics: distribution by wealth segment and industry, average bike purchases.  
- Location analysis: distribution by state and correlation of property valuation with wealth segment.  
- Estimate potential revenue based on historical bike purchases and value.  

### Task 5: Customer Lifetime Value (CLV) Analysis (16 Marks)
Calculate and analyze CLV:  
- Use formula:  
  CLV = (Average Purchase Value × Purchase Frequency) × Customer Lifespan  
  - Average Purchase Value (APV): Total Revenue / Number of Purchases  
  - Purchase Frequency (PF): Total Transactions / Unique Customers  
  - Customer Lifespan: Average tenure from Demographic data  
- Segment CLV by wealth segment and relate CLV to demographics.  

### Task 6: Executive Summary and Recommendations (16 Marks)
Summarize findings and suggest business strategies:  
- Highlight insights from segmentation, transaction analysis, new customer insights, and CLV.  
- Recommend marketing strategies targeting high-value segments.  
- Suggest business expansion opportunities based on location analysis.  
- Recommend product offering improvements from transaction insights.  
