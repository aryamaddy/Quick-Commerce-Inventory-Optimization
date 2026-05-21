# 🛒 Quick-Commerce Inventory Optimization & Churn Reduction

## 📌 Problem Statement
In quick-commerce (10-minute delivery), if an item is out of stock or cannot be delivered within the promised time window, customers immediately close the app (bounce). This project analyzes hourly purchase patterns to detect stock-out vulnerabilities and suggests inventory rebalancing strategies to minimize customer churn.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn

## 📊 Key Insights Found
1. **Peak Failure Hours:** Customer bounce rate spikes drastically between **6 PM - 9 PM**, reaching up to **26%** due to stock depletion during evening high-demand hours.
2. **High-Risk Categories:** `Biscuits` (33% bounce) and `Beverages` (26% bounce) face the highest out-of-stock rates, despite being fast-moving items.
3. **Smooth Demand Curve:** Implemented a 3-hour NumPy/Pandas rolling average to smooth out transaction noise and precisely pinpoint demand velocity.

## 💡 Business Recommendation
By increasing the stock of **Munchies, Biscuits, and Beverages by 20% between 5:30 PM and 9:00 PM** in high-density dark stores, the platform can reduce stock-out losses by **15%** and significantly improve customer retention.
