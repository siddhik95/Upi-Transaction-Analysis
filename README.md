# UPI Transactions Analysis Dashboard (Power BI)

An interactive 5-page Power BI dashboard analysing UPI (Unified Payments Interface) digital payment transactions in India for 2024. The project explores transaction volume and value, time-based patterns, geographic and bank-level distribution, fraud and risk, and device/network usage.

## Dataset

- **Source:** UPI Transactions 2024 (Kaggle)
- **Power BI table name:** `upi_transactions`
- **Columns:**

| Column | Description |
|---|---|
| transaction id | Unique transaction identifier |
| timestamp | Date and time of the transaction |
| transaction type | Type of transaction (e.g. P2P, P2M) |
| merchant_category | Merchant category of the transaction |
| amount (INR) | Transaction amount in Indian Rupees |
| transaction_status | Success / failed status |
| sender_age_group | Age group of the sender |
| receiver_age_group | Age group of the receiver |
| sender_state | State of the sender |
| sender_bank | Sender's bank |
| receiver_bank | Receiver's bank |
| fraud_flag | Whether the transaction was flagged as fraud |
| day_of_week | Day of the week |
| device_type | Device used (e.g. Android, iOS, Web) |
| hour_of_day | Hour of the transaction (0-23) |
| is_weekend | Weekend indicator |
| network_type | Network used (e.g. 4G, 5G, WiFi) |

## Dashboard Pages

1. **Overview** – Headline KPIs: total transactions, total value, success rate, average ticket size, fraud rate.
2. **Transaction Patterns** – Trends by hour, day of week, transaction type, and merchant category.
3. **Geography & Banks** – Transaction distribution by sender state and sender/receiver bank.
4. **Fraud & Risk** – Fraud rate across categories, age groups, states, and time windows.
5. **Device & Network** – Usage and success rates by device type and network type.

The dashboard is powered by 16 DAX measures covering totals, rates, averages, and comparisons.

## Tools & Technologies

- Power BI Desktop
- DAX
- Excel / CSV (source data)
  
## Author

**Siddhi Kanavaje**
Data Analyst | Python · Power BI · SQL · R · Excel

## License

This project is for educational purposes. Dataset credit: original Kaggle dataset author.
