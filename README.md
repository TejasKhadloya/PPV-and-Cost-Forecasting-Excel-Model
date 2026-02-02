# Purchase Price Variance (PPV) & Cost Forecasting Model

An Excel-based financial model that evaluates **purchase price variance (PPV)** and **unit cost risk** for a consumer electronics product using real historical data and forward-looking scenarios.

The model combines:
- Normalised cost driver indices (semiconductors, energy, freight)
- Actual USD/CNY FX rates
- Scenario-based inflation and FX assumptions

It is designed to mirror how FP&A and supply chain finance teams assess **cost volatility, margin pressure, and FX exposure** in practice.

---

## Key Takeaways

- Input cost inflation and FX movement can materially impact unit economics even when production volumes remain stable.
- Applying **partial FX exposure** significantly reduces cost volatility compared to full FX pass-through assumptions.
- Scenario-based forecasting provides clearer insight into PPV risk than single-point estimates.
- Monthly compounding reveals timing effects that annual averages often mask.

---

## How to Use the Model

1. Adjust scenario assumptions in the Executive Summary (Layer 1).
2. Review historical cost driver behaviour in Layer 2 to understand market trends.
3. Analyse monthly unit cost and PPV impact in Layer 3.
4. Compare snapshot vs FY 2025 forecast outcomes using the PPV summary.

---

## Model Structure

The model is organised into three interconnected layers to mirror how cost analysis is reviewed in practice.

### Layer 1 — Executive Summary & Scenario Inputs
Provides a snapshot of unit costs and PPV under a selected scenario, along with key assumptions and the standard cost structure.

![Executive Summary](https://github.com/TejasKhadloya/PPV-and-Cost-Forecasting-Excel-Model/blob/main/Images/Executive%20Summary.png)

### Layer 2 — Historical Cost Driver Data
Uses a complete 24-month history (2023–2024) of normalised cost indices and actual USD/CNY FX rates to ground the forecast in real market behaviour.

![Historical Data](https://github.com/TejasKhadloya/PPV-and-Cost-Forecasting-Excel-Model/blob/main/Images/Historical%20Data.png)

### Layer 3 — Forecast Mechanics & Impact (FY 2025)
Translates forecasted cost driver movements into monthly unit costs, FX-adjusted total costs, and PPV impact for January–December 2025.

![Forecast Mechanics](https://github.com/TejasKhadloya/PPV-and-Cost-Forecasting-Excel-Model/blob/main/Images/Forecast%20Mechanics.png)

---

## Key Assumptions & Methodology

- Forecasts are derived from the most recent **24 months of historical data (2023–2024)** and projected forward using scenario-based assumptions converted to monthly rates.
- USD/CNY FX impact is applied using a **partial FX exposure assumption (65%)**, reflecting that not all costs are denominated in CNY.
- Annual inflation assumptions are converted into **monthly compounding rates** for forecasting.
- Scenario “Snapshot” represents a single-period what-if view, while FY 2025 results reflect **time-weighted monthly forecasts**.
- All figures are illustrative and intended to demonstrate financial modeling methodology rather than predict actual outcomes.

---

## Data Sources

**Data used**
- USD/CNY FX monthly average rates: https://www.x-rates.com/average/?from=USD&to=CNY

**Context & methodology references**
- Apple Investor Relations (cost structure context): https://investor.apple.com/investor-relations/default.aspx
- FX exposure and risk modeling concepts: https://corporatefinanceinstitute.com/resources/valuation/foreign-exchange-risk/
- Inflation and cost forecasting concepts: https://www.investopedia.com/terms/i/inflation.asp
- Global supply chain context: https://www.apple.com/supply-chain/

---

## Disclaimer

Unless otherwise stated, indices and assumptions are illustrative and used solely for financial modeling demonstration purposes.  
This project does not represent actual Apple Inc. internal cost data or forecasts.

