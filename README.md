# 🎯 Customer RFM Data Analysis Project

**RFM (Recency, Frequency, Monetary) Analysis** - Segment 8000+ customer purchases to identify your best customers and drive targeted business strategies.

---

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
