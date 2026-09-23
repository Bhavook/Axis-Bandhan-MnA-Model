# Strategic M&A Accretion/Dilution Model: Axis Bank & Bandhan Bank

## 📌 Project Overview
This project is a dynamic, multi-tranche Mergers & Acquisitions (M&A) financial model analyzing the hypothetical acquisition of Bandhan Bank by Axis Bank. Built entirely from first principles in Excel, the model evaluates the transaction's financial viability, structural funding mechanics, and immediate impact on shareholder value (Earnings Per Share). 

**Objective:** To determine whether the acquisition is mathematically Accretive or Dilutive to Axis Bank's standalone EPS, factoring in takeover premiums, regulatory capital constraints, and post-tax cost of capital.

---

## ⚙️ Deal Mechanics & Assumptions
The transaction is structured to reflect the strict regulatory environment of the Indian banking sector (preserving CET1 capital ratios).

*   **Target:** Bandhan Bank (Implied Standalone Market Cap: ~₹29,737 Cr)
*   **Acquirer:** Axis Bank (Implied Standalone Market Cap: ~₹3,86,480 Cr)
*   **Takeover Premium:** 25% (Reflecting historical precedent in Indian banking control premiums)
*   **Total Implied Purchase Price:** ₹37,170.9 Cr

### The Funding Strategy (90 / 5 / 5)
Unlike corporate acquisitions, commercial banks cannot freely drain liquidity without violating RBI CRR/SLR mandates. Therefore, the deal is anchored as a **Share Swap**:
*   **Equity (90%):** ₹33,453.8 Cr funded via issuance of ~26.92 Cr new Axis Bank shares.
*   **Cash (5%):** ₹1,858.5 Cr from existing reserves (Interest foregone pegged at the RBI SDF rate of 5.0%).
*   **Debt (5%):** ₹1,858.5 Cr via Tier-II bond issuance (Pre-tax cost of debt modeled at 8.0%).
*   **Statutory Tax Rate:** 25.168% (Section 115BAA) applied to calculate the marginal tax shields on both debt and foregone cash.

![Funding Mix](Visual%201-Funding%20mix.png)

---

## 📊 Financial Impact: Accretion / (Dilution) Analysis
The model calculates the combined net income after accounting for post-tax interest expenses and foregone interest income. 

*   **Axis Bank Standalone EPS:** ₹89.30
*   **Combined Entity EPS:** ₹85.67
*   **Net Impact:** **-4.07% (Dilutive)**

![EPS Impact](Visual%202-EPS%20Impact.png)

### Strategic Rationale for Dilution
The mathematical dilution (-4.07%) occurs because Axis Bank's cost of equity (earnings yield of ~7.2%) exceeds the target's standalone earnings yield (~3.6%). However, in a real-world scenario, this short-term dilution would be offset by **Post-Merger Synergies**:
1.  **Revenue Synergies:** Cross-selling Axis Bank's premium wealth management and credit card portfolios to Bandhan's deep rural and microfinance customer base.
2.  **Cost Synergies:** Rationalization of overlapping urban branches and consolidation of backend IT/HR infrastructure. 

---

## 🛠️ Skills Demonstrated
*   **Financial Modeling:** Dynamic cell referencing, scenario building, and keyboard-first Excel navigation.
*   **Corporate Finance:** Cost of capital calculations, Share Swap ratios, and Tax Shield mechanics.
*   **Commercial Banking Acumen:** Understanding of regulatory liquidity constraints vs. free corporate cash flow.

---

## ⚠️ Disclaimer

> **This document is an independent academic exercise prepared solely for learning purposes as part of a PGDM (Finance) project at Welingkar Institute of Management, Mumbai.** 
>
> It is not affiliated with, endorsed by, or reviewed by Axis Bank, Bandhan Bank, or any of their officers, employees, or advisors. All figures, assumptions, and conclusions are the author's own estimates, built on publicly available information and simplified for illustrative purposes; they do not represent an actual or proposed transaction between the two banks. 
> 
> Nothing in this workbook constitutes investment advice, a recommendation, or an offer to buy or sell any security, and it should not be relied upon for any financial, legal, or investment decision. Please verify all data independently before any other use.
