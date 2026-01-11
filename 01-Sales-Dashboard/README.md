# Sales Dashboard

## Project Description

A comprehensive PowerBI dashboard designed to track and analyze sales performance across regions, products, and time periods.

## 📊 Dashboard Features

### Key Metrics Tracked:
- **Total Sales**: Year-to-date and monthly comparisons
- **Sales by Region**: Regional performance breakdown
- **Product Performance**: Top-selling and underperforming products
- **Sales Trends**: Monthly and quarterly trend analysis
- **Target vs Actual**: Achievement of sales targets

### Interactive Elements:
- Drill-down capability by Region → Territory → Customer
- Date range filters for custom period analysis
- Product category and segment filters
- Sales rep performance filtering

## 🛠️ Technical Details

**Data Source**: Sales database (SQL)
**Refresh Rate**: Daily
**Data Model**: Star schema with Facts and Dimensions
**Key Relationships**:
- Sales Fact ↔ Date Dimension
- Sales Fact ↔ Product Dimension
- Sales Fact ↔ Region Dimension
- Sales Fact ↔ Customer Dimension

## 📈 DAX Measures

- Sales YTD
- Sales vs Target
- Growth %
- Average Order Value
- Customer Count
- Sales per Customer

## 💡 Business Insights

- Real-time sales monitoring
- Quick identification of underperforming regions
- Product performance trending
- Target achievement tracking
- Sales growth analysis

## 📁 Files in This Project

- `SalesDashboard.pbix` - Main PowerBI file
- `sales_data.csv` - Sample data source
- `Data Dictionary.xlsx` - Field definitions

## 🎯 Use Cases

- Sales manager reviews daily performance
- Executive summary for stakeholder meetings
- Territory performance benchmarking
- Sales forecast validation
- Compensation tracking for sales reps

---

**Created**: January 2026
**Last Updated**: January 2026
**Status**: Active
