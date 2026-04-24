# Customer Behavior Analysis using RFM Segmentation in Excel

## 📋 Project Overview
This project demonstrates a complete **RFM (Recency, Frequency, Monetary)** analysis on an Ecommerce Consumer Behavior dataset. 

RFM analysis is a powerful customer segmentation technique used to identify high-value customers, at-risk customers, and opportunities for targeted marketing. 

The analysis was performed entirely in **Microsoft Excel**, covering data cleaning, scoring, segmentation, and dashboard creation.

## 🎯 Objectives
- Calculate RFM scores for ~1,000 customers
- Segment customers into meaningful groups (Champions, Loyal Customers, At Risk, etc.)
- Build an interactive dashboard to visualize insights
- Practice key Excel skills: formulas, PivotTables, charts, conditional formatting, and slicers

## 📁 Dataset
- **Source**: Ecommerce Consumer Behavior Analysis Data (Kaggle)
- **Rows**: 1,000 customers
- **Key Columns**: 
  - `Customer_ID`
  - `Recency` (days since last purchase)
  - `Frequency` (number of purchases)
  - `Monetary` (total spend in USD)
- File: `Dataset.csv` (includes raw data)
- File: `Ecommerce_Consumer_Behavior_Analysis_Data.xslx` (includes raw data + full RFM_Analysis sheet)
- File: `guideline.docx` (Includes methodology used when doing the RFM Analysis)

## 🛠️ Methodology

### 1. RFM Scoring (1–5 scale)
- **Recency**: Lower days = higher score (most recent buyers get 5)
- **Frequency**: Higher purchases = higher score
- **Monetary**: Higher spend = higher score

Used `PERCENTILE.INC` for quintile-based scoring.

### 2. Customer Segments
- **Champion**
- **Loyal Customer**
- **Potential Loyalist**
- **Big Spender**
- **At Risk**
- **About To Sleep**
- **Lost Customer**
- **Others**

### 3. Dashboard Features
- Segment distribution (counts & percentages)
- Average spend, frequency, and recency by segment
- Interactive slicers
- Visual charts (bar, column, pie)


## 🧰 Tools & Excel Features Used
- Excel Formulas (`IF`, `PERCENTILE.INC`, `TEXT`, `AND`)
- Excel Tables
- PivotTables & Pivot Charts
- Conditional Formatting
- Slicers for interactivity
- Dashboard layout & visualization

Author: Primrose Wambui
