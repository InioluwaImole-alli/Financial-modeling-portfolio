# Financial-modeling-portfolio# Corporate Finance & Investment Analysis Portfolio

Welcome to my financial modeling and equity research repository. This hub features fundamental, data-driven corporate valuation models built from scratch using audited financial statements, regulatory frameworks, and macroeconomic indicators. 

---

## Project 1: Geregu Power Plc — Intrinsic Valuation & Market Comps Analysis

* **Asset Class:** Public Equities (NGX)
* **Sector:** Power Generation (Utilities)
* **Deliverables:** 
  * 📊 https://1drv.ms/x/c/118f8ea519d298bd/IQBKeEGU8ur3S78ELfZTCvZSAQerMBdCw_dFFHDKTo0e4t8?e=ahQjJM
  * 📄https://1drv.ms/w/c/118f8ea519d298bd/IQCErQqowF6qQKNeerUswX65AfDY-lpGun2xAxXyCMT0J5M?e=deuQZo
### Executive Summary & Valuation Thesis
This project provides a comprehensive fundamental valuation of Geregu Power Plc against the backdrop of a highly restrictive domestic macroeconomic environment. The analysis reveals a significant divergence between fundamental intrinsic value and current market pricing—highlighting the classic frontier market variance between baseline corporate cash flows and public market technicals.

### Key Insights & Findings

* **DCF Intrinsic Value:** **₦197.27 per share**.
* **The Macro Sledgehammer:** Future free cash flows are discounted using a robust Weighted Average Cost of Capital (WACC) that reflects a high risk-free rate environment, driven by the Central Bank of Nigeria's restrictive monetary policy stance (MPR at 26.5%). High discount rates mathematically anchor the present value of utility cash flows.
* **Trading Comps Disconnect:** The asset currently trades at an elevated **43.7x EV/EBITDA** multiple based on its FY 2025 financial results. In contrast, its closest, direct industry peer—which prints over 2.5x more absolute EBITDA and operates at a significantly larger revenue and net profit scale—trades at a normalized utility multiple of **13.9x EV/EBITDA**.
* **Market Technicals vs. Value:** The massive valuation premium commanded by the target stock is structural rather than fundamental. A tightly controlled free float (~18%) combined with strong institutional asset demand creates an artificial scarcity premium on the exchange, driving market price far above intrinsic value.

### Model Architecture & Methodology
* **Historical 3-Statement Linkage:** Fully integrated Income Statement, Balance Sheet, and Cash Flow Statement (FY 2023 - FY 2025).
* **Granular Operational Revenue Drivers:** Revenue forecasts are driven cleanly by physical operational metrics: Installed Capacity (MW) × Available Capacity Factors × Expected Grid Wheeling/Evacuation Limits × NERC Multi-Year Tariff Order (MYTO) pricing frameworks.
* **Capital Structure & Debt Schedules:** Explicit mapping of interest-bearing liabilities, tracking the exact weight of net debt inside the Enterprise Value equation.
* **Sensitivity Matrix:** Double-variable sensitivity tables analyzing the impact of changing WACC baselines and Terminal Growth Rates ($g$) on the final per-share value.

* ## Project 2: May & Baker Nigeria Plc — Dual-Track Valuation Engine (DCF & Trading Comps)

* **Asset Class:** Public Equities (NGX)
* **Sector:** Healthcare (Pharmaceutical Manufacturing)
* **Deliverables:** 
  * 📊 https://1drv.ms/x/c/118f8ea519d298bd/IQAZ6pCSMj8SQbx8bKNnPwV8Abng_38cknTmAKPjx54Xwnw?e=90ODhR
  * 📄 https://1drv.ms/w/c/118f8ea519d298bd/IQChg30ITQyiSp9Lji_uFi6xAYWcUISkeeEJ4jEEqcTijLk?e=GpTGf1

### Executive Summary & Valuation Thesis
This project features an institutional-grade, dual-track valuation engine combining an Unlevered Discounted Cash Flow (DCF) model and an active Trading Comparables (Comps) matrix for May & Baker Nigeria Plc (MAYBAKER). The model explores a classic valuation paradox common in frontier markets: while conservative macroeconomic risk-discounting places the stock’s standalone intrinsic value below current market levels, a granular relative peer analysis proves the asset is trading at a steep structural discount compared to its closest public competitors, offering a compelling long-term relative value play.

### Core Valuation Mechanics & Methodology

* **1. Absolute Valuation (Intrinsic DCF Engine)**
  * **Implied Value:** **₦24.90 per share**, establishing a highly conservative baseline and built-in margin of safety.
  * **Macro Risk Integration:** Future free cash flows to the firm (FCFF) are discounted using a robust **19.39% WACC**. This rate is driven by a **24.49% Cost of Equity** that incorporates Aswath Damodaran's structural country risk premium for Nigeria (8.41% CRP) and an elevated local risk-free rate of 9.47%.
  * **Terminal Value Constraints:** The long-term growth rate ($g$) is capped strictly at the risk-free rate (9.47%) to aggressively anchor and penalize speculative outer-year cash projections.

* **2. Relative Valuation (Trading Comps Matrix)**
  * **Peer Universe:** Multiples are benchmarked against clean, normalized FY2025 financial lines for **Fidson Healthcare Plc (FIDSON)** and **MeCure Industries Plc (MECURE)**.
  * **The Relative Discount:** At its current market price of ₦38.00, May & Baker trades at a trailing **P/E of 14.7x**, significantly trailing Fidson (**26.1x**) and MeCure (**58.6x**).
  * **Multiple Diagnostics:** Across all core trading multiples—including Price-to-Sales (1.71x vs peer average of 3.47x) and Price-to-Book (4.80x vs peer average of 15.86x)—May & Baker trades at a deep sector discount despite maintaining a highly competitive 34.3% gross profit margin.

### Model Architecture & Technical Specifications
* **Integrated 3-Statement Linkage:** Fully dynamic projection engine (FY 2026F – FY 2030F) built from audited disclosures, utilizing non-circular finance loops to protect spreadsheet stability.
* **Granular EBITDA-to-NOPAT Normalization:** Isolated pure operating metrics by stripping out cross-allocated corporate expenses, identifying true EBITDA, structural Depreciation & Amortization (D&A), and Net Operating Profit After Tax (NOPAT) to judge cash generation independent of leverage.
* **Pure-Play Beta Relevering:** Deployed Damodaran's global pharmaceutical industry baseline unlevered beta (0.91), relevering it to **1.19** against May & Baker's true book capital structure (0.46 Debt-to-Equity) and a 33.0% blended marginal corporate tax shield.
* **Net Working Capital (NWC) Drivers:** Modeled discrete efficiency cycles (Receivable Days, Inventory Days, Payables Days) to dynamically feed cash adjustments directly into the Cash Flow from Operations (CFO) block.


---
