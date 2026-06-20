# UPI-TRANSACTION-ANALYSIS

# UPI Transaction Analytics Dashboard

**Real-time Digital Payment Analysis & Fraud Detection System**

A comprehensive Power BI dashboard for monitoring UPI transactions, 
analyzing payment trends, customer behavior, and detecting anomalies 
in India's digital payment ecosystem.

## 📊 Purpose

This dashboard was built to provide **real-time insights** into UPI payment operations by:

- **Transaction Monitoring**: Track daily, weekly, and monthly transaction volumes & values
- **Fraud Detection**: Identify suspicious patterns, failed transactions, and anomalies
- **Merchant Performance**: Analyze top merchants, payment success rates, and revenue distribution
- **Customer Behavior**: Understand payment habits, frequency, and preferred UPI apps
- **Risk Analysis**: Monitor high-risk transactions and user segments
- **Payment Gateway Performance**: Evaluate transaction success rates and processing times
- **Financial Reporting**: Generate revenue reports and payment settlement analytics

**Key Stakeholders**: Payment processors, merchants, fintech analysts, risk managers, compliance teams

## 🛠️ Tech Stack

| Category | Technology |
|----------|-----------|
| **BI Tool** | Power BI Desktop / Power BI Service |
| **Data Source** | SQL Server, Payment Gateway APIs, CSV Files |
| **Data Transformation** | Power Query (ETL), Python scripts |
| **Data Modeling** | DAX (Data Analysis Expressions) |
| **Visualization** | Power BI visuals, custom maps, flow charts |
| **Version Control** | Git / GitHub |
| **File Format** | .pbix (Power BI Project File) |

**Key Features Used**:
- ✅ Real-time data refresh
- ✅ Anomaly detection algorithms
- ✅ Geospatial mapping (India state-wise analysis)
- ✅ Time-series trending
- ✅ KPI thresholds & alerts
- ✅ Custom DAX measures for fraud scoring


   ## 📁 Data Source

### Data Overview
- **Dataset**: UPI Payment Transactions Database
- **Records**: ~500,000+ transactions
- **Time Period**: 2023-2024
- **Update Frequency**: Daily (Real-time)
- **File Format**: SQL Server / API / CSV

### Data Tables Included

| Table | Description | Records |
|-------|-------------|---------|
| **Transactions** | Transaction ID, amount, date, status, merchant | 500,000+ |
| **Users/Customers** | Customer ID, phone, age, location, KYC status | 50,000+ |
| **Merchants** | Merchant ID, category, location, settlement rate | 15,000+ |
| **Payment Gateway** | Gateway name, transaction fee, success rate | 8 major gateways |
| **UPI Apps** | GooglePay, PhonePe, Paytm, BHIM, WhatsApp Pay | 50,000+ users |
| **Failed Transactions** | Failed transaction ID, reason, amount, retry count | 25,000+ |
| **Device Info** | Device type, OS, IP location, browser details | Linked to users |

### Data Fields
- **Transaction**: UPI ID, Amount, Date/Time, Status (Success, Failed, Pending)
- **Merchant**: Merchant Category (Retail, Utilities, Travel, Food, etc.)
- **User**: Age Group, State, City, KYC Status, Device Type
- **Risk**: Transaction risk score, fraud probability, velocity check
- **Settlement**: Settlement amount, settlement date, merchant fees
- **Analytics**: Transaction duration (ms), retry count, device fingerprint

### Data Privacy
✅ All customer names and phone numbers anonymized
✅ Real transaction patterns used, dummy payment amounts
✅ Compliant with RBI & NPCI guidelines


 ## ⭐ Features & Highlights

### 📊 Interactive Dashboards (Multiple Pages)

#### 🏠 **Overview / Executive Summary**
- Total transactions & transaction value (₹)
- Daily transaction volume trend
- Success vs failed transaction ratio
- Top UPI apps by user count
- Geographic distribution (India heatmap)

#### 💳 **Transaction Analysis**
- Transaction volume by hour, day, week
- Average transaction value & median
- Transaction value distribution (histogram)
- Top transaction categories
- Payment success rate by gateway
- Processing time analysis

#### 🎯 **Merchant Performance**
- Top 20 merchants by transaction count
- Top merchants by revenue
- Merchant category breakdown
- Merchant settlement rates
- New vs returning merchant ratio
- Average transaction value per merchant

#### ⚠️ **Fraud Detection & Risk**
- Suspicious transaction alerts
- Transaction risk score distribution
- Failed transaction reasons (timeout, invalid, limit exceeded)
- High-risk user segments
- Velocity checks (transactions per hour/day)
- Geographic anomalies
- Device fingerprint analysis

#### 👥 **Customer Behavior & Demographics**
- User age group distribution
- Geographic spread across states/cities
- KYC verified vs unverified users
- Average transaction frequency per user
- Customer lifetime value (CLV)
- Repeat customer ratio

#### 📱 **UPI App Performance**
- Market share by UPI app (GooglePay, PhonePe, Paytm, etc.)
- User growth trend per app
- Transaction success rate by app
- App-wise average transaction value
- User retention by app

#### 📈 **Financial & Settlement**
- Daily revenue & settlement amount
- Gateway fees & commission breakdown
- Settlement cycle analysis (T+1, T+2, etc.)
- Payout delays & exceptions
- Monthly revenue trends
- Profit margin by merchant category

### 🎯 Key Features
- ✅ **Real-time Refresh** - Updates every hour
- ✅ **Anomaly Detection** - Automated fraud alerts
- ✅ **Geospatial Maps** - State & city-wise analysis
- ✅ **Drill-down Capability** - Click for transaction details
- ✅ **Dynamic Filters** - Date, amount, status, category, app
- ✅ **Predictive Insights** - Risk scoring algorithm
- ✅ **Custom KPIs** - Success rate, fraud rate, settlement time
- ✅ **Mobile Responsive** - View on any device

  ## 🔍 Key Questions This Dashboard Answers

### 💰 **Transaction Volume & Value**
- ❓ What is the total transaction value (₹) today/this month?
- ❓ How many UPI transactions occur daily on average?
- ❓ What is the peak transaction time (hour/day)?
- ❓ What is the average transaction value?
- ❓ Which day of the week has maximum transactions?
- ❓ What is the month-over-month growth in transaction volume?

### 🏪 **Merchant & Category Analysis**
- ❓ Who are the top 10 merchants by transaction count?
- ❓ Which merchant category generates most revenue?
- ❓ What is the success rate for each merchant?
- ❓ Are there merchants with unusually high failed transactions?
- ❓ Which merchants have fastest settlement cycles?
- ❓ Which new merchants are performing well?

### ✅ **Transaction Success & Failures**
- ❓ What is the overall transaction success rate?
- ❓ What are the top reasons for transaction failures?
- ❓ Which payment gateways have highest success rates?
- ❓ What is the average retry rate for failed transactions?
- ❓ Are there specific times when failures spike?
- ❓ Which UPI apps have highest failure rates?

### 📱 **UPI App Performance & Market Share**
- ❓ What is the market share of each UPI app (GooglePay, PhonePe, etc.)?
- ❓ Which app has the highest user growth?
- ❓ Which app has the most transactions?
- ❓ Are users switching between UPI apps?
- ❓ Which app has the best customer satisfaction?
- ❓ What is the average transaction value per app?

### ⚠️ **Fraud & Risk Detection**
- ❓ How many high-risk transactions are flagged daily?
- ❓ What is the fraud rate (% of transactions)?
- ❓ Which users/merchants show suspicious patterns?
- ❓ Are there geographic hotspots for fraud?
- ❓ What are common fraud indicators detected?
- ❓ How many transactions are blocked by risk algorithms?

### 👤 **Customer & User Behavior**
- ❓ How many unique users transacted today/this month?
- ❓ What is the average transaction frequency per user?
- ❓ Which age group has highest transaction volume?
- ❓ Which states/cities have most UPI users?
- ❓ What % of users are KYC verified?
- ❓ What is the repeat customer ratio?

### 🌍 **Geographic Analysis**
- ❓ Which state generates most transaction value?
- ❓ Which city has highest transaction frequency?
- ❓ Are there regional variations in transaction patterns?
- ❓ Which regions show fraud risk?
- ❓ What is the urban vs rural transaction split?
- ❓ Which regions are fastest growing?

### 💳 **Payment Gateway Performance**
- ❓ Which payment gateway handles most volume?
- ❓ What is the success rate by gateway?
- ❓ Which gateway has fastest processing time?
- ❓ Are any gateways experiencing outages?
- ❓ What is the cost per transaction by gateway?
- ❓ Which gateway has lowest failure rate?

### 📊 **Financial & Settlement**
- ❓ What is the total settlement amount (₹)?
- ❓ What is the average gateway fee per transaction?
- ❓ Are there delayed settlements?
- ❓ What is the settlement success rate?
- ❓ How long does settlement typically take?
- ❓ Which merchant categories have highest fees?

### 📈 **Trends & Growth**
- ❓ What is the YoY transaction growth rate?
- ❓ Is fraud rate increasing or decreasing?
- ❓ What is the trend in average transaction value?
- ❓ Are new users growing faster than repeat users?
- ❓ Which merchant category shows fastest growth?

---

### 💡 **Sample Insights Generated**
```
✅ 2.5M UPI transactions daily (₹5,000 crore value)
✅ PhonePe leads with 35% market share, GooglePay 32%, Paytm 20%
✅ 98.5% transaction success rate (↑ 0.3% from last month)
✅ Retail category generates 40% of total transaction value
✅ Peak transaction time: 7-9 PM (evening peak)
✅ Fraud detection rate: 0.8% of transactions flagged
✅ Average settlement time: 1.2 days
✅ Top merchant: XYZ Retail with 50K daily transactions
'''
The Dashboard preview


















