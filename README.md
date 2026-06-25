# ESG Dashboard — Philippines (PSE)

An interactive ESG (Environmental, Social, Governance) dashboard tracking 20 PSE-listed companies across 7 sectors of the Philippine Stock Exchange.

Built as a single-file HTML/CSS/JS application. No frameworks, no dependencies, no build step.

**Live demo:** [esg-dashboard-ph.netlify.app](https://esg-dashboard-ph.netlify.app)

---

## Features

- **KPI overview** — average ESG score, companies tracked, medium and high risk counts
- **ESG trend chart** — market average by pillar (Environmental, Social, Governance) from 2019 to 2024
- **Risk distribution donut** — visual breakdown of Low / Medium / High risk companies
- **Pillar breakdown by sector** — average E, S, G scores per industry
- **Company cards** — expandable accordion with individual pillar scores, market cap, and ESG risk rationale
- **Live filters** — filter by sector and risk level; results update instantly
- **Live timestamp** — displays current Philippine time (PHT)

---

## Sectors Covered

Banking · Energy · Technology · Telecom · Property · Consumer · Mining

---

## Data Sources

- World Bank Governance Indicators
- IFC Sustainability Framework
- PSE Disclosure Reports 2024
- UN SDG Corporate Data
- SEC Philippines Annual Reports

Scores are on a 0–100 scale. Market cap figures in USD via BSP exchange rate.

**Note on data:** All ESG scores and company data are static and based on publicly available disclosures as of 2024. The dashboard does not connect to a live data feed. The timestamp shown is the current local time (PHT) and does not indicate real-time data updates. This is a portfolio and research visualization tool, not a live market intelligence product.

---

## How to Use

View the live version at [esg-dashboard-ph.netlify.app](https://esg-dashboard-ph.netlify.app)

---

## Stack

Pure HTML · CSS · Vanilla JavaScript · Inline SVG charts

---

## About

Built as part of a research and data portfolio focused on ESG risk, Southeast Asian capital markets, and corporate governance in emerging economies.

**GitHub:** [github.com/joyce-gonzales/esg-dashboard-ph](https://github.com/joyce-gonzales/esg-dashboard-ph)
