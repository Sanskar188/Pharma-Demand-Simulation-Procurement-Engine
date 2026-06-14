# 💊 Aegis Flow - AI Pharma Procurement Suite

Aegis Flow is an intelligent pharmaceutical demand simulation and procurement optimization platform designed for wholesalers, distributors, hospitals, and pharmacies.

The platform analyzes historical procurement data, forecasts medicine demand, identifies inventory risks, and generates optimal purchasing recommendations using inventory management principles such as FEFO, Safety Stock Analysis, Reorder Point Calculation, and EOQ (Economic Order Quantity).

---

## 🚀 Features

### 📊 Demand Forecasting
- Historical demand analysis
- Monthly medicine consumption trends
- Future demand prediction
- Procurement planning assistance

### 📦 Inventory Optimization
- Current inventory visibility
- Overstock detection
- Stockout risk identification
- Safety stock recommendations

### 🔄 FEFO Management
- First Expired First Out simulation
- Expiry risk detection
- Inventory rotation planning
- Waste reduction insights

### 📈 Procurement Intelligence
- Reorder point calculation
- Economic Order Quantity (EOQ)
- Purchase recommendations
- Supplier planning support

### 💰 Profitability Analysis
- Revenue contribution analysis
- Product profitability ranking
- Margin optimization insights
- High-value medicine identification

### ⚠ Risk Management
- Excess inventory alerts
- Low inventory alerts
- Expiring stock alerts
- Procurement risk assessment

### 📉 Analytics Dashboard
- Interactive KPI cards
- Procurement trends
- Demand visualization
- Inventory health metrics

### 📂 CSV Data Upload
Upload historical procurement data in CSV format and instantly generate:

- Demand forecasts
- Inventory analysis
- Procurement recommendations
- Executive summary reports

---

## 🛠 Technology Stack

### Frontend
- React.js
- Vite
- Tailwind CSS
- Framer Motion
- Lucide React Icons

### Backend (Future Expansion)
- FastAPI / Flask
- Python
- Pandas
- NumPy
- Scikit-learn

### Data Processing
- CSV Parsing
- Inventory Simulation Engine
- Demand Forecasting Models
- EOQ Calculation Engine

---

## 📁 Expected CSV Format

| Product Name | Quantity | Month | Year |
|-------------|----------|--------|------|
| Crocin | 1200 | January | 2020 |
| Dolo 650 | 950 | January | 2020 |
| Azithromycin | 750 | January | 2020 |

Required Fields:

- Product Name (String)
- Quantity (Number)
- Month
- Year

---

## 📊 Key Metrics Calculated

### Inventory Metrics
- Safety Stock
- Reorder Point
- Current Stock Status
- Service Level

### Procurement Metrics
- EOQ
- Annual Demand
- Ordering Cost
- Holding Cost

### Business Metrics
- Revenue
- Profit
- Profit Margin
- Inventory Turnover Ratio

---

## 🎯 Target Users

- Pharmaceutical Wholesalers
- Drug Distributors
- Retail Pharmacies
- Hospital Supply Chains
- Healthcare Procurement Teams
- Inventory Managers

---

## ⚡ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/aegis-flow.git
