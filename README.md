# Credit Card Financial Dashboard

A comprehensive financial analytics dashboard for credit card transactions and customer insights. This project provides detailed analysis of credit card usage patterns, customer demographics, and transaction behaviors across multiple card categories and time periods.

## 📊 Overview

This dashboard analyzes credit card data spanning the entire year 2023, with detailed breakdowns by:
- **Card Categories**: Blue, Gold, Silver, Platinum
- **Customer Demographics**: Age, income, education, employment, location
- **Transaction Metrics**: Volume, amount, frequency, utilization rates
- **Time Periods**: Weekly and quarterly analysis

## 📁 Data Structure

### Core Datasets

#### `credit_card.csv`
Main credit card dataset with detailed transaction and account information:
- Client identification and card category
- Annual fees and activation status
- Credit limits and revolving balances
- Transaction amounts and volumes
- Utilization ratios and transaction methods
- Merchant categories (Fuel, Grocery, Entertainment, Travel, Bills, Food)
- Weekly and quarterly time dimensions

**Columns**: 20+ fields including Client_Num, Card_Category, Annual_Fees, Credit_Limit, Total_Revolving_Bal, Total_Trans_Amt, Total_Trans_Vol, Avg_Utilization_Ratio, and more

#### `cc_add.csv`
Supplementary credit card data with additional transaction details:
- Same core metrics as primary dataset
- Additional temporal breakdowns
- Customer acquisition costs
- Week and quarter segmentation for Q4 2023

#### `customer.csv`
Customer demographics and profile information:
- Age, gender, dependent count
- Education level and employment
- Marital status and state location
- Home and car ownership status
- Personal loan information
- Income levels and satisfaction scores

**Columns**: 15 fields including Customer_Age, Gender, Dependent_Count, Education_Level, Income, Cust_Satisfaction_Score, etc.

#### `cust_add.csv`
Additional customer attributes:
- Comprehensive demographic breakdown
- Similar structure to customer.csv with alternative data source
- Used for validation and supplementary analysis

### Supporting Reports

#### `CREDIT CARD DASHBOARD INSIGHTS.pdf`
Executive summary document with:
- Key performance metrics
- Trend analysis
- Customer segmentation insights
- Visual dashboards and charts

#### `credit card customer report.pdf`
Detailed customer analysis including:
- Demographic distributions
- Customer satisfaction metrics
- Segment-based insights
- Behavioral patterns

#### `credit card transcation report.pdf`
Transaction-focused analysis covering:
- Volume and value metrics
- Merchant category performance
- Payment method analysis
- Temporal patterns and trends

## 🔍 Key Metrics & Dimensions

### Transaction Analysis
- **Total Transaction Amount**: Sum of all transactions per customer
- **Transaction Volume**: Count of individual transactions
- **Average Utilization Ratio**: Revolving balance / Credit limit

### Customer Segmentation
- **By Card Type**: Blue, Gold, Silver, Platinum
- **By Income**: Range from $1,250 to $515,324
- **By Satisfaction**: Scores from 1-5
- **By Geography**: Multiple US states (CA, NY, TX, FL, NJ, etc.)

### Temporal Analysis
- **Weekly Granularity**: 53 weeks across 2023
- **Quarterly Breakdown**: Q1-Q4 2023
- **Seasonal Patterns**: Trends across quarters and weeks

## 📈 Business Insights

### Customer Base
- **Size**: 500+ unique customers
- **Age Range**: 24-65 years
- **Demographics**: Mix of employed, self-employed, retirees, and government workers
- **Satisfaction**: Average scores ranging 1-5 across different segments

### Card Category Performance
- **Blue Card**: Primary offering with widest customer base
- **Premium Tiers**: Gold, Silver, Platinum for high-value customers
- **Annual Fees**: $95-$495 depending on card type

### Transaction Patterns
- **Merchant Categories**: Dominated by Bills, Food, Entertainment, and Fuel
- **Payment Methods**: Chip, Swipe, and Online transactions
- **Credit Utilization**: Varies from 0% to >95% across customers

## 🛠️ Technical Details

### Data Format
- **CSV Files**: Standard comma-separated values format
- **PDF Reports**: Visual analysis documents
- **Time Period**: Full year 2023 (Jan 1 - Dec 31)
- **Update Frequency**: As-needed basis

### Data Quality
- Comprehensive demographic information
- Transaction-level detail with merchant categories
- Multiple validation datasets (cust_add.csv, cc_add.csv)
- Consistent ID mapping (Client_Num across all files)

## 📝 Use Cases

1. **Customer Analysis**: Identify high-value customers and at-risk segments
2. **Product Performance**: Track card category adoption and profitability
3. **Marketing Campaigns**: Target customers by demographics and behavior
4. **Risk Assessment**: Monitor credit utilization and spending patterns
5. **Trend Analysis**: Identify seasonal patterns and temporal trends

## 🎯 Getting Started

1. **Load the Data**: Import CSV files into your analytics tool or database
2. **Join Tables**: Use Client_Num as the primary key across datasets
3. **Create Visualizations**: Build dashboards using the provided report templates
4. **Analyze Trends**: Segment by card category, geography, and time period

## 📊 Recommended Analysis Tools

- **Business Intelligence**: Tableau, Power BI, Looker
- **Data Analysis**: Python (Pandas, Matplotlib), R
- **Databases**: SQL Server, PostgreSQL, MySQL
- **Spreadsheets**: Excel with pivot tables

## 📞 Support

For data-related questions or analysis needs, refer to the included PDF reports:
- `CREDIT CARD DASHBOARD INSIGHTS.pdf` - Executive summary
- `credit card customer report.pdf` - Customer details
- `credit card transcation report.pdf` - Transaction metrics

## 📄 License

This dataset is provided for analytical and business intelligence purposes.

---

**Last Updated**: 2024
**Data Period**: Full Year 2023 (January - December)
**Total Records**: 500+ customers with weekly transaction data
