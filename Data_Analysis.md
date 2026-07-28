# Data Analysis Phase

## Phase Overview

This phase focuses on translating the modeled e-commerce data into actionable business insights, using a structured, question-driven approach to uncover the true drivers of sales, returns, and marketing performance.

The primary goal is to move beyond surface-level reporting and answer the specific business questions that matter most for decision-making — financial health, regional demand, payment behavior, return costs, and marketing efficiency — using the Star Schema built in the Data Modeling phase.

---

## Analysis Methodology

The analysis approach follows a **KPI-driven framework**, where each business area is broken down into three guiding questions. Each question is paired with a defined metric and a clear analytical goal, ensuring every chart and dashboard built in Power BI is tied directly to a decision the business needs to make.

The analysis was structured into three core areas:

- **Sales & Financial Performance**
- **Returns & Order Quality**
- **Marketing & Ad Performance**

---

## Area 1: Sales & Financial Performance

[#area-1-sales-financial-performance](#area-1-sales-financial-performance)

This area establishes the financial baseline of the business and identifies where revenue is coming from.

### KPI 1: Is the business financially sustainable?

- **Metric:** Total Sales, Total Profit, Profit Margin.
- **Goal:** Establish the financial baseline and determine whether headline revenue reflects true business health.

### KPI 2: Where are orders coming from — and which cities drive growth?

- **Metric:** Total orders by city (Mumbai, Delhi, Bengaluru, Pune).
- **Goal:** Identify regional concentration and guide logistics & marketing resource allocation.

### KPI 3: How do customers pay — and which categories actually sell?

- **Metric:** Payment mode split (UPI, CARD, COD, WALLET) & sales by category.
- **Goal:** Spot payment friction and category over-concentration that creates demand risk.

---

## Area 2: Returns & Order Quality

[#area-2-returns-order-quality](#area-2-returns-order-quality)

This area quantifies the operational and financial cost of returns and identifies the most actionable fix.

### KPI 1: How large is the returns problem — and what does it cost operationally?

- **Metric:** Total returned orders, RTO orders, and delivery success rate.
- **Goal:** Quantify fulfilment failure and benchmark delivery performance against industry standards.

### KPI 2: What is the true financial damage of returns — and is it getting worse?

- **Metric:** Lost revenue from returns, tracked monthly.
- **Goal:** Expose the bottom-line impact and identify whether the problem spikes seasonally or is structural.

### KPI 3: Why are customers returning — and which reason can we fix first?

- **Metric:** Return count by reason (Size Issue, RTO, Quality, Delayed Delivery, etc.) & return rate by category.
- **Goal:** Prioritise the highest-volume, most actionable fix.

---

## Area 3: Marketing & Ad Performance

[#area-3-marketing-ad-performance](#area-3-marketing-ad-performance)

This area evaluates whether marketing spend is efficient and whether the business is overexposed to a single channel.

### KPI 1: Is our ad spend generating proportional revenue — across all seasons?

- **Metric:** Total Ad Revenue vs. Total Ad Spend, tracked monthly.
- **Goal:** Detect seasonal misalignment between budget and demand peaks, and identify missed scaling opportunities.

### KPI 2: Are our campaigns efficient — or are weak ones hiding behind strong ones?

- **Metric:** ROAS per campaign & blended CAC.
- **Goal:** Uncover performance disparity across campaigns to justify killing underperformers and scaling top earners.

### KPI 3: Which channel actually drives sales — and are we dangerously over-reliant on one?

- **Metric:** Last-touch channel attribution split (Meta, Google, Influencer, Email/SMS, Organic, Offline).
- **Goal:** Assess channel concentration risk and identify underinvested channels with growth potential.

---

# Conclusion

This phase demonstrates how a Star Schema data model can be translated into a focused set of business questions across Sales, Returns, and Marketing.

By anchoring every KPI to a specific metric and a decision-oriented goal, the analysis becomes:

- Easier to prioritize
- Directly actionable for stakeholders
- A strong foundation for the Power BI dashboards built in the next phase

The resulting KPI framework provides the analytical backbone for the dashboards, surfacing the financial baseline, regional and payment trends, return cost drivers, and marketing efficiency signals needed to guide business decisions.
