# AtliQ Hardware – End-to-End Power BI Analytics

## 📊 Project Overview

This project is an end-to-end Power BI analytics solution developed as part of the Codebasics Power BI Experience.

The project covers data transformation, data modeling, DAX development, financial analysis, forecasting analysis, KPI development and interactive dashboard design.

---

## 🎯 Business Objective

The objective was to build a centralized business intelligence solution for analyzing:

- Sales performance
- Net Sales
- Gross Margin
- Gross Margin %
- Cost of Goods Sold
- Operational Expenses
- Net Profit
- Forecast Quantity
- Forecast Accuracy
- Forecast Error
- Customer performance
- Product performance
- Target performance
- Year-over-Year performance

---

## 🏗️ Data Model

The Power BI model contains fact tables, dimension tables and supporting tables.

### Dimension Tables

- `dim_customer`
- `dim_product`
- `dim_date`
- `dim_market`
- `fiscal_year`

### Fact Tables

- `fact_actuals_estimates`
- `fact_forecast_monthly`
- `manufacturing_cost`
- `freight_cost`
- `Operational Expense`
- `post_invoice_deductions`
- `NsGmTarget`

### Supporting Tables

- `P & L Rows`
- `P & L Columns`
- `Set BM`
- `LastSalesMonth`
- `Key Measures`

---

## 🔄 Data Transformation

Power Query was used as the data preparation layer.

The workflow included:

1. Data exploration
2. Data cleaning
3. Data transformation
4. Data validation
5. Data integration
6. Preparation of data for the Power BI model

---

## 📐 Data Modeling

The solution uses a dimensional data model consisting of fact and dimension tables.

Dimension tables provide descriptive business attributes such as:

- Customer
- Product
- Market
- Region
- Date
- Fiscal Year

Fact tables contain measurable business values such as:

- Sales
- Quantity
- Costs
- Forecasts
- Deductions
- Operational expenses
- Targets

---

## 🧮 DAX Development

The project contains DAX measures for several analytical areas.

### Financial KPIs

- Gross Sales
- Net Invoice Sales
- Net Sales
- Total COGS
- Gross Margin
- Gross Margin %
- Gross Margin per Unit
- Operational Expense
- Net Profit
- Net Profit %

### Forecasting KPIs

- Sales Quantity
- Forecast Quantity
- Net Error
- Net Error %
- Absolute Error
- Absolute Error %
- Forecast Accuracy %
- Forecast Accuracy % LY
- Risk classification

### Benchmark & Target KPIs

- Net Sales Target
- Gross Margin Target
- Net Profit Target
- Gross Margin % Target
- Net Profit % Target
- Previous Year Benchmark
- Target Benchmark
- Variance

---

## 💰 Financial Analysis

The P&L structure follows:

```text
Gross Sales
      ↓
Pre Invoice Deduction
      ↓
Net Invoice Sales
      ↓
Post Invoice Deduction
      ↓
Post Invoice Other Deduction
      ↓
Net Sales
      ↓
Manufacturing Cost
      ↓
Freight Cost
      ↓
Other Cost
      ↓
Total COGS
      ↓
Gross Margin
      ↓
Operational Expense
      ↓
Net Profit 

---
```
## Dashboard Preview

### Executive Dashboard

![Executive Dashboard](screenshots/Atliq_Bi_Executive_Page%281%29.png)

### Finance Dashboard

![Finance Dashboard](screenshots/Atliq_Bi_Finance_page%281%29.png)

### Supply Chain Dashboard

![Supply Chain Dashboard](screenshots/Atliq_Bi_Supply_Cha      in_Page%281%29.png)

### Project Home

![Project Home](screenshots/Atliq_Bi_Home_Page%281%29.png)
