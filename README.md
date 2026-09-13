# FP&A Financial Model

An independently built FP&A financial model developed in Microsoft Excel to demonstrate practical skills in financial modeling, forecasting, debt analysis, and sensitivity analysis.

## Project Overview

This project focuses on building an integrated financial model that connects operating assumptions with financial statements and supporting schedules.

The model was developed independently using a publicly available dataset sourced from Kaggle.

The objective was to build a structured model that demonstrates how operating performance, financing decisions, and key assumptions flow through a business's financial statements and ultimately affect profitability.

## What the Model Includes

### Financial Statements

The core model incorporates:

- Income Statement
- Balance Sheet
- Cash Flow Statement
- Revenue
- Cost of Goods Sold
- Operating expenses
- Depreciation
- Interest expense
- Earnings Before Tax
- Net Income
- Forecast periods
- Supporting financial assumptions

The statements are designed to work together as an integrated financial model.

All financial figures are presented in ₹.

### Debt Schedule

A supporting debt schedule was developed to model the company's financing position.

It includes:

- Beginning debt balance
- Debt issuance
- Principal repayment
- Ending debt balance
- Interest expense
- Interest-rate assumptions

The debt schedule connects financing assumptions with the broader financial model and interest expense calculations.

### Sensitivity Analysis

A two-variable sensitivity analysis was created to evaluate how changes in key operating assumptions affect projected net income.

The analysis varies:

- Units Sold
- Cost of Goods Sold as a percentage of Revenue

The resulting scenarios are compared against the base-case net income to evaluate the impact of changes in operating assumptions on profitability.

## Dataset

The underlying operating dataset was sourced from Kaggle.

The dataset contains information including:

- Month
- Product
- Units sold
- Price per unit
- Region
- Revenue

Revenue is derived from the underlying operating data.

The dataset served as the starting point for the analysis, while the financial statements, assumptions, forecasts, debt schedule, and sensitivity analysis were independently developed in Excel.

## Model Structure

The model is organized around the following components:

### 1. Financial Statements

The core three-statement model contains:

- Income Statement
- Balance Sheet
- Cash Flow Statement
- Revenue assumptions
- Unit volume assumptions
- Price per unit assumptions
- COGS as % of Revenue
- SG&A as % of Revenue
- Tax rate
- Working capital assumptions
- Long-term debt assumptions
- Interest expense assumptions

The financial statements are forecast from 2026F to 2030F using the underlying operating and financial assumptions.

### 2. Supporting Schedules

Supporting schedules drive key components of the financial statements.

#### Fixed Assets Schedule

- Capital expenditures
- Existing asset useful life
- New asset useful life
- Existing asset depreciation
- New asset depreciation
- Total depreciation
- Beginning PP&E
- Ending PP&E

#### Retained Earnings Schedule

- Beginning retained earnings
- Net income
- Dividends
- Ending retained earnings

#### Revolver Schedule

- Available cash
- Beginning cash balance
- Cash from operations
- Cash from investing activities
- Debt movements
- Common stock movements
- Dividends
- Cash available for revolver
- Revolver balance
- Revolver interest rate
- Interest expense

### 3. Sensitivity Analysis

The sensitivity analysis evaluates the effect of changes in:

- Units Sold
- COGS as a percentage of Revenue

on projected net income.

This provides a scenario-based view of how changes in key operating assumptions can influence profitability.

## Model Flow

```text
Operating Assumptions
        │
        ▼
Financial Statements
        │
        ├── Income Statement
        ├── Balance Sheet
        └── Cash Flow Statement
        │
        ▼
Supporting Schedules
        │
        ├── Fixed Assets
        ├── Retained Earnings
        └── Revolver
        │
        ▼
Sensitivity Analysis
```

### Repository Structure ###

FPA-Financial-Model/
│
├── FPA_Financial_Model.xlsx
├── README.md
│
└── screenshots/
    ├── 01-financial-statements.png
    ├── 02-cash-flow-and-assumptions.png
    ├── 03-supporting-schedules.png
    ├── 04-sensitivity-analysis.png
    └── 05-debt-schedule.png
        │
        ▼
Net Income / Profitability Scenarios
