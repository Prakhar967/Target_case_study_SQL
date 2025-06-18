# Target Case Study – E-Commerce SQL Analysis

This project analyzes an e-commerce business case from Target (Brazil operations), focusing on customer behavior, order trends, payments, freight, and delivery performance using advanced SQL queries.

---

## Objective

To extract actionable business insights using SQL from the Target Brazil dataset and provide data-driven recommendations for improving sales, logistics, and customer experience.

---

## Dataset

The dataset includes the following tables:
- `customers`
- `orders`
- `order_items`
- `payments`
- `products`
- `sellers`
- `order_reviews`
- `geolocation`

---

## Key Questions & Insights

### Customer Behavior & Sales Trend
- Orders grew **137% from 2016 to 2017**, followed by **stable growth** in 2018.
- High activity observed during **Feb, Mar, Jun, Oct, Nov**, indicating **seasonal shopping trends**.
- **Afternoon** is the most preferred time for placing orders.

### Regional Analysis
- **SP, RJ, MG** are top states for:
  - Order volume
  - Payment value
  - Freight cost
- May and August saw the **highest order surges** in SP & RJ.

### Delivery & Logistics
- SP has the **fastest average delivery time** and **lowest freight value**.
- States like AP and RR show **delays or high freight costs** due to remote geography.
- Maximum delivery delay recorded: **210 days** (outlier).

### Payments Analysis
- Most customers paid via **single installment**.
- Installment usage drops significantly after the first payment, indicating **potential dropouts**.

---

## Business Recommendations

1. **Target repeat customers** with loyalty programs based on their 2016–2017 surge behavior.
2. **Run seasonal promotions** during Feb, Mar, Jun, Oct, and Nov to boost sales.
3. Offer **region-specific discounts and logistics improvements** in top-performing states (SP, RJ, MG).
4. Improve **delivery speed** in remote regions through **3rd-party logistics partnerships**.
5. Incentivize **on-time and full payment completion** by offering flexible EMI schemes and rewards.
6. Highlight **afternoon deals** and ensure **store readiness during peak hours**.

---

## Tools Used

- **SQL** (Google BigQuery style syntax)
- **Spreadsheet Analysis** (Excel/Sheets)
- **PDF** for case study review
- GitHub for version control and showcase

---

## Author

**Prakhar Asthana**  
Aspiring Data Analyst | SQL, Python, Excel , numpy , pandas , Hypothesis Testing , statistical analysis , tableau 
📧 asthana967@hotmail.com
🔗 [GitHub](https://github.com/Prakhar967) | [LinkedIn](www.linkedin.com/in/prakhar-asthana-5b3a8b131)

---
## How to use

You can view the case study analysis in 'Target_Sql.pdf'
datasets file can be loaded into google BigQuery or MySQL for replications
