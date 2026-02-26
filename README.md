# 🎯 Customer RFM Data Analysis Project

**RFM (Recency, Frequency, Monetary) Analysis** - Segment 8000+ customer purchases to identify your best customers and drive targeted business strategies.

---

## 📋 Table of Contents
# Retail Customer Behavior - RFM Analysis

## 📁 Project Structure

- [Data](./data/) - Contains raw and processed data files
- [Scripts](./scripts/) - Python scripts for analysis
- [Notebooks](./notebooks/) - Jupyter notebooks with analysis
- [Results](./results/) - Output files and visualizations

## 🚀 Getting Started

Follow the notebooks in order:
1. [01_Data_Exploration](./notebooks/01_Data_Exploration.ipynb)
2. [02_RFM_Analysis](./notebooks/02_RFM_Analysis.ipynb)
3. [03_Customer_Segmentation](./notebooks/03_Customer_Segmentation.ipynb)

## 🔍 Overview

This project implements **RFM segmentation logic** to analyze customer behavior from **8,000+ purchase records**. It automatically scores and categorizes customers based on:
- **Recency**: How recently they made a purchase
- **Frequency**: How often they purchase
- **Monetary**: How much they spend

Use these insights to optimize marketing campaigns, customer retention, and revenue optimization.

---

## 📊 RFM Methodology

| Metric | Definition |
|--------|-----------|
| **Recency (R)** | Days since last purchase (lower is better) |
| **Frequency (F)** | Number of purchases in period (higher is better) |
| **Monetary (M)** | Total amount spent (higher is better) |

**Scoring**: Each metric is divided into **5 quintiles** (scores 1-5), then combined into an RFM score.

---

## ✨ Key Features

✅ **Automated RFM Scoring** - Calculate R, F, M scores from raw transaction data  
✅ **Customer Segmentation** - Group customers into actionable segments  
✅ **Data Visualization** - Charts and insights in Excel outputs  
✅ **Scalable Pipeline** - Processes 8,000+ transactions efficiently  
✅ **Export Ready** - Results in structured Excel formats  

---

## 🚀 Quick Start

### Prerequisites
```bash
Python 3.7+
pandas
openpyxl
numpy
