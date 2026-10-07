# apple-dashboard
# 🍎 Apple Inc. Stock Market Analysis Dashboard

An interactive **Apple Inc. (AAPL) Stock Market Analysis Dashboard** developed using **Power BI and Stock Market API data**.

The dashboard provides a visual analysis of Apple's stock performance, including price trends, opening and closing prices, high and low prices, trading volume, maximum returns, and month-over-month volume changes.

---

## 📊 Dashboard Preview

![Apple Stock Market Dashboard](https://github.com/Arpit-prog1/apple-dashboard/blob/main/Snapshot%20of%20the%20dashboard.png.png)

---

## 📌 Project Overview

The purpose of this project is to analyze Apple Inc.'s stock market performance using real-time/historical stock market data obtained through an API.

The data is processed and visualized in Power BI to create an interactive dashboard that helps users understand:

- Stock price movements
- Opening and closing price trends
- High and low prices
- Trading volume
- Maximum daily returns
- Monthly trading-volume changes
- Overall stock market performance

The dashboard covers approximately the **latest 100 days of Apple stock performance**.

---

## 🎯 Project Objectives

The main objectives of this project are:

1. Analyze Apple's stock price movement.
2. Compare opening and closing prices.
3. Identify high and low stock prices.
4. Analyze daily trading volume.
5. Identify periods with unusually high trading volume.
6. Analyze maximum daily returns.
7. Compare month-over-month trading volume.
8. Build an interactive and easy-to-understand financial dashboard.
9. Demonstrate the use of APIs for financial data analysis.
10. Convert raw stock market data into meaningful business insights.

---

## 🛠️ Tools & Technologies

- **Power BI** – Dashboard development and visualization
- **Stock Market API** – Data collection
- **Power Query** – Data cleaning and transformation
- **DAX** – Calculations and KPIs
- **REST API** – Data retrieval
- **GitHub** – Project documentation and version control

---

## 🔌 API Integration

The project uses a **Stock Market API** to retrieve Apple Inc. stock market data.

The API provides information such as:

- Date
- Open price
- High price
- Low price
- Close price
- Trading volume

The API data is then transformed and loaded into Power BI for analysis.

### API Workflow

API
↓
Raw Stock Market Data
↓
Power Query
↓
Data Cleaning & Transformation
↓
DAX Calculations
↓
Power BI Dashboard
↓
Business Insights

---

## 🔐 API Key Security

The API key is required to access the stock market API.

**The API key should NEVER be uploaded to GitHub.**

Instead, store it locally using an environment variable or a secure configuration file.

Example:

```text
API_KEY=your_api_key_here
