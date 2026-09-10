# Tax Co-Pilot for the Post-Deduction Era
> Next-Generation Consumer Fintech Tax Planning Module

---

## Executive Summary

With nearly 88% of individual tax filers migrating to India’s New Tax Regime, consumer fintechs face severe cross-sell erosion on traditional tax-saving instruments under Sections 80C and 80D[cite: 3]. 

This project repositions a consumer fintech’s tax module away from reactive, Q4 "March Panic" deduction-led savings toward year-round tax certainty and regime guidance[cite: 3]. By architecting consent-driven data ingestion via the Account Aggregator (AA) rail, the module transforms annual tax compliance into continuous financial planning while creating contextual, high-intent cross-sell opportunities[cite: 3].

---

## Problem Statement & Strategic Opportunity

* **The March Panic:** Taxpayers traditionally delay decisions until Q4, leading to hurried, suboptimal lumpsum investments[cite: 3].
* **Data Friction:** Manual document uploads (Form 16, Form 26AS, bank statements) cause heavy drop-offs during activation[cite: 3].
* **Cross-Sell Erosion:** Migration to the New Tax Regime eliminates conventional 80C/80D cross-sell triggers[cite: 3].

**Solution:** A real-time, predictive tax liability engine that ingests financial data year-round, provides proactive regime recommendations, and surfaces contextual micro-investments[cite: 3].

---

## User Personas

1. **Salaried X (Compliant & High Volume):** Income documented via Form 16. Needs automated calculation, refund speed, and clear regime guidance[cite: 3].
2. **Freelancer Y (Complex Income):** Multiple income streams with varying TDS (e.g., 194J), needing quarterly liability estimates and expense categorization[cite: 3].
3. **Investor Z (High Net Worth):** Capital gains across equity, F&O, RSUs, and ESOPs requiring automated brokerage sync and loss-offset analysis[cite: 3].

---

## Ingestion Strategy & Product Architecture

* **Account Aggregator Rail:** Consent-first ingestion to fetch verified income, investment, and interest data securely[cite: 3].
* **Manual Fallback:** Designed fallback flows for FIP coverage exclusions (unintegrated banks/brokerages)[cite: 3].
* **Progressive Profiling:** Collects minimal necessary credentials upfront to calculate baseline projections before requesting sensitive investment details[cite: 3].

---

## AARRR Metrics & Funnel Modeling

**North Star Metric:** Annualized Tax Savings Realized per Active User (ATSR)[cite: 3]

| Funnel Stage | Business Goal | Primary KPI | V1 Target | Strategic Significance |
| :--- | :--- | :--- | :--- | :--- |
| **Acquisition** | Attract high-intent filers | Module Sign-Up Rate (MSR) | 15% MSR | Evaluates GTM messaging efficiency[cite: 3] |
| **Activation** | Obtain complete data profiles | Data Profile Completion (DPC) | 70% DPC in 7 days | **Core bottleneck;** enables predictive accuracy[cite: 3] |
| **Retention** | Habitual year-round usage | Streak Completion Rate (SCR) | 40% 4-week streak | Drives repeat engagement via micro-nudges[cite: 3] |
| **Revenue** | Contextual cross-selling | Cross-Sell Conversion (CSCR) | 15% CSCR | Validates predictive advisory monetization[cite: 3] |
| **Referral** | Satisfaction & organic growth | Net Promoter Score (NPS) | NPS > 50 | Measures user trust and product value[cite: 3] |

---

## Key Product Decisions & Roadmap

* **Funnel Sensitivity Analysis:** Sensitivity modeling proved that Account Aggregator consent completion—not user acquisition—was the binding bottleneck limiting paid conversion[cite: 3].
* **V1 Scope Pivot:** Redirected engineering scope toward optimizing the Consent Screen UX, targeting 35% completion and under 5% recommendation reversal[cite: 3].
* **Phased Rollout:**
  * **Phase 1 (Q4):** Frictionless Ingestion, Form 16 OCR, & Regime Decision Engine for Salaried users[cite: 3].
  * **Phase 2 (Q1-Q3):** Gamified Streaks, Habit Formation, & Contextual Cross-Sell Funnels[cite: 3].
  * **Phase 3 (Q4+):** Complex Persona Rollout (Brokerage APIs, Crypto/F&O tracking, AI Query Chatbot)[cite: 3].

---

## Author
**Daksh Pratap Singh**  
*Undergraduate Student, Indian Institute of Technology (IIT) Kanpur*  
* [LinkedIn](https://www.linkedin.com/in/daksh-pratap-singh-8b6a372a2/)
* [GitHub](https://github.com/dakshprsingh)
