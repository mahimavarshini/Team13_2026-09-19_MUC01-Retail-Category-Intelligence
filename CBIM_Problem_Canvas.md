# Micro-Use Case 01 (MUC01): Retail Category Intelligence

## Category Business Intelligence Model (CBIM) Problem Canvas

---

### Canvas Metadata & 3-Member Team Structure

- **Project Title**: Retail Category Intelligence & Exploratory Data Analysis (EDA)
- **Institution / Department**: KL University — Department of Computer Science & Engineering / Data Analytics
- **Dataset**: `MUC01_Retail_Sales_Dataset 1.csv` (107,838 Transactions | 12 Stores across Andhra Pradesh)
- **Team Leadership & Ownership Structure**:
  - **Member 1**: `[Member 1 Govardhan , 2300080016]` — *CBIM Canvas Co-Development, Step 5.1 (Data Ingestion & Hygiene) & Step 5.2 (Category Revenue Trajectory & Consistency)*
  - **Member 2**: `[Member 2 Shaik Saniya Firoj , 2300030628]` — *Step 5.3 (Top 2 / Bottom 2 SKUs & Supplier Challenge) & Step 5.4 (Discount Tiers 0%–25%+ & Elasticity)*
  - **Member 3 (Team Lead)**: `[Member 3 Mahima Varshini , 2300031837]` — *Step 5.5 (Day-of-Week/Monthly Time Patterns & Promotional Timing) & Step 5.6 (Category Manager Briefing & Final Business Synthesis)*

---

```
+---------------------------------------------------------------------------------------------------------------+
|                                      CBIM PROBLEM CANVAS ARCHITECTURE                                         |
+---------------------------------------+---------------------------------------+-------------------------------+
| 1. CONTEXT & BACKGROUND               | 2. BUSINESS PROBLEM & OBJECTIVES      | 3. KEY STAKEHOLDERS           |
| - Multi-store retail enterprise       | - Margin leakage from unguided promos | - Chief Merchandising Officer |
| - 12 Stores across Andhra Pradesh     | - High inventory holding costs        | - Category Managers           |
| - 5 Categories: Electronics, Apparel, | - Stockouts on hero products          | - Regional Store Operations   |
|   Grocery, Home, Personal Care        | - Suboptimal regional replenishment   | - Supply Chain / Warehousing  |
+---------------------------------------+---------------------------------------+-------------------------------+
| 4. DATA ASSETS & GRANULARITY          | 5. CORE ANALYTICAL HYPOTHESES         | 6. TARGET KPIS & METRICS      |
| - 107,838 transaction-level rows      | - H1: Electronics leads growth        | - Net Revenue & Units Sold    |
| - Scope: Jan 1, 2026 - Jun 30, 2026   | - H2: Grocery is the stable anchor    | - Average Transaction Value   |
| - Zero missing values & 0 duplicates  | - H3: Top 2 SKUs drive category cash  | - Category Consistency Index  |
| - 100% mathematical formula accuracy  | - H4: Steep discounts erode margins   | - Effective Discount %        |
+---------------------------------------+---------------------------------------+-------------------------------+
| 7. DECISION INTERVENTIONS             | 8. VALUE & PROJECTED IMPACT           | 9. 3-MEMBER WORK DIVISION     |
| - Guardrail discounts on Electronics  | - 3-5% gross margin preservation      | - Member 1: Step 5.1 & 5.2    |
| - Priority stocking for Top 2 SKUs    | - 15-20% reduction in dead inventory  | - Member 2: Step 5.3 & 5.4    |
| - Challenge Bottom 2 SKU suppliers    | - Optimized working capital turnover  | - Member 3 (Lead): Step 5.5   |
| - Weekend replenishment alignment     | - Higher customer basket realization  |   & 5.6 (Final Strategy)      |
+---------------------------------------+---------------------------------------+-------------------------------+
```

---

### Detailed Canvas Breakdown

#### 1. Context & Business Background

- **Operational Footprint**: Multi-store omnichannel retail network operating 12 physical outlets across key commercial centers in Andhra Pradesh (Vijayawada, Kakinada, etc.) spanning five core merchandise categories: Electronics, Apparel, Grocery, Home & Kitchen, and Personal Care.
- **Time Horizon**: 181 consecutive operating days (January 1 to June 30, 2026), capturing post-holiday purchasing trends and mid-year seasonality.

#### 2. Business Problem & Strategic Objectives

- **Problem Statement**: The business lacks unified category intelligence, leading to untracked margin leakage from unguided 20% discounts, stockouts on vital hero SKUs, and inventory stagnation in regional stores.
- **Strategic Objective**: Transform transactional data into prescriptive category intelligence to optimize category growth trajectories, eliminate unprofitable promotions, and synchronize supply chain replenishment with peak consumer velocity.

#### 3. Stakeholders & Decision Makers

- **Chief Merchandising Officer (CMO)**: Enterprise category mix, revenue targets, and working capital strategy.
- **Category Managers**: SKU assortment curation, vendor negotiations, supplier reviews, and promotional calendars.
- **Regional Store Operations Heads**: Floor layout, shelf allocation, and weekend staffing.
- **Supply Chain Directors**: Warehouse fulfillment scheduling and regional logistics dispatch.

#### 4. Data Assets & Integrity

- **Dataset**: `MUC01_Retail_Sales_Dataset 1.csv` comprising 107,838 transactional records.
- **Key Fields**: Transaction ID, Date, Store ID, Store City, Category, Product Name, Units Sold, Unit Price, Revenue, Discount %.
- **Data Hygiene**: Verified by Member 1 to have zero missing values, zero duplicates, and 100% mathematical consistency with the net revenue equation.

#### 5. Analytical Hypotheses & Exploration Framework

- **Hypothesis 1 (Category Growth & Consistency)**: Electronics drives the highest revenue expansion, while Grocery represents the most consistent revenue anchor across months.
- **Hypothesis 2 (SKU Polarities)**: Within each category, the Top 2 products generate the majority of category revenue, whereas the Bottom 2 represent margin drags.
- **Hypothesis 3 (Discount Elasticity)**: Discounts greater than 10% in inelastic categories (like high-end electronics) dilute margins without driving proportional unit volume.
- **Hypothesis 4 (Temporal Velocity)**: Weekend shopping velocity significantly exceeds weekday run-rates, creating targeted promotional timing opportunities.

#### 6. Target KPIs & Business Metrics

- **Category Commercial Health**: Net Revenue (INR), Total Units Sold, Average Price Realization.
- **Stability & Consistency**: Monthly Revenue Coefficient of Variation (CV) per category.
- **Basket Dynamics**: Average Transaction Value (ATV), Volume-to-Value ratios.
- **Promotional Return**: Incremental Unit Lift vs. Discount Margin Cost.

#### 7. Actionable Business Interventions

- **Assortment Rationalization**: Maintain 100% on-shelf availability for Top 2 hero SKUs; review or delist Bottom 2 chronic laggards in Personal Care.
- **Promotional Governance**: Replace flat 20% markdowns on Electronics with bundle incentives (e.g., grocery vouchers on electronics purchases) rolled out on Friday evenings.
- **Regional Stocking**: Concentrate premium electronics inventory in high-ATV metropolitan outlets (Vijayawada), while prioritizing high-velocity grocery inventory in regional centers (Kakinada).

#### 8. Business Impact & Projected Value

- **Margin Preservation**: 3% to 5% gross margin savings by ending unguided discounts on electronics.
- **Working Capital Release**: 15% reduction in dead inventory through supplier challenges on Bottom 2 SKUs.
- **Revenue Acceleration**: Capturing the 10%–15% weekend shopping lift through synchronized Thursday night replenishment.

#### 9. 3-Member Leadership & Ownership Mapping

- **Member 1**: Canvas co-design, Step 5.1 (Data Ingestion & Hygiene), Step 5.2 (Category Trajectory & Consistency).
- **Member 2**: Step 5.3 (Top 2 / Bottom 2 SKUs & Supplier Challenge), Step 5.4 (Discount Effectiveness 0%–25%+ & Elasticity).
- **Member 3 (Team Lead)**: Step 5.5 (Day-of-Week & Monthly Patterns, Electronics Deep-Dive & Timing), Step 5.6 (Category Manager Briefing & Final Combined Recommendations).
