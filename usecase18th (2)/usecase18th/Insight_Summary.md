# Executive Insight Summary — Retail Category Intelligence (MUC01)
**Course / Institution**: KL University — Category Management & Retail Analytics  
**Dataset**: `MUC01_Retail_Sales_Dataset 1.csv` (107,838 Transactions | 12 Stores)  

### 👥 Team Ownership & Rubric Module Mapping (3 Members)
- **👤 Member 1 (`[Name/ID]`):** CBIM Problem Canvas, Step 5.1 (Data Ingestion & Hygiene), Step 5.2 (Category Revenue Trajectory & Consistency Analysis).
- **👤 Member 2 (`[Name/ID]`):** Step 5.3 (Top 2 / Bottom 2 SKUs & Supplier Challenge), Step 5.4 (Discount Tiers 0%–25%+ & Price Elasticity).
- **👑 Member 3 (`[Your Name/ID]` - Team Lead):** Step 5.5 (Day-of-Week/Monthly Time Patterns, Category vs. Business Comparison & Promotional Timing), Step 5.6 (Category Manager Briefing & Final Synthesized Strategy).

---

### 1. Key Empirical Findings
- **Data Hygiene & Foundation (Step 5.1)**: Successfully validated 107,838 unique transactions across 12 Andhra Pradesh stores over 181 operational days. Confirmed 0 missing values, 0 duplicate transactions, and 100% mathematical adherence to the net revenue formula (`revenue == units_sold * unit_price * (1 - discount_pct/100)`).
- **Category Trajectory & Consistency (Step 5.2)**: **Electronics** is the primary revenue growth driver, generating >45% of enterprise turnover. **Grocery** is identified as the most stable, consistent revenue anchor with the lowest coefficient of monthly variation, providing steady store footfall.
- **SKU Extremes & Underperforming Suppliers (Step 5.3)**: Top 2 SKUs per category (e.g., Laptops & Smart TVs in Electronics; Jeans & Kurtas in Apparel) drive disproportionate revenue. Conversely, chronic bottom performers in Personal Care (Face Wash variants) tie up working capital, indicating suppliers to renegotiate or replace.
- **Promotional Inelasticity (Step 5.4)**: Analysis across discount tiers (0%, 5%, 10%, 15%, 20%+) reveals that while modest discounts accelerate Grocery inventory velocity, steep 20% discounts on Electronics erode gross margin without generating proportional unit volume lift.
- **Temporal Peaks & Weekend Lift (Step 5.5)**: Network sales register a **10%–15% revenue lift on weekends** (Saturday & Sunday). Electronics exhibits the sharpest weekend surge compared to overall business trends, dictating peak promotional windows.

---

### 2. Strategic Category Manager Recommendations (Step 5.6)
1. **Assortment Rationalization**: Maintain 100% in-stock availability for Top 2 hero SKUs across categories while delisting or renegotiating vendor agreements on chronic Bottom 2 SKUs.
2. **Promotional Restructuring**: Cease flat 20% markdowns on high-ticket Electronics. Shift budgets toward cross-category bundles (e.g., grocery vouchers on electronics purchases) timed for Friday–Sunday rollout.
3. **Regional Stock Allocation**: Deepen Electronics and Apparel inventory in high-ATV metropolitan stores (Vijayawada), while prioritizing Grocery velocity in regional centers like Kakinada.
4. **Supply Chain Synchronization**: Schedule warehouse dispatches for Thursday evenings to ensure full shelf replenishment ahead of the weekend shopping surge.

---

### 3. Analytical Limitations
1. **Absence of Cost Data (COGS)**: The dataset lacks product cost prices, restricting profit analysis to gross revenue rather than net margin.
2. **No Customer Tracking**: Omission of unique customer IDs precludes repeat purchase, retention, and basket market-basket association mining.
3. **Seasonality Window**: The 6-month observation window (January–June 2026) captures summer dynamics but excludes peak Q3/Q4 festival seasonality (Diwali).
