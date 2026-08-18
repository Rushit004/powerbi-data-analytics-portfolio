# Power BI Data Analytics Portfolio

A collection of end-to-end Power BI dashboards, each taking a real or simulated dataset from raw files through Power Query cleaning, data modeling, DAX, and a fully interactive multi-page report. The projects progress from single-dataset analysis toward business-brief-driven work and simulated client engagements with automation layered on top.

## How to explore this portfolio

Since GitHub does not render `.pbix` files natively, every project below is self-contained with its own README, screenshots, and download links:

- 📁 **Browse a project:** Click into any folder below — each has its own README with page-by-page breakdowns, DAX highlights, and screenshots.
- ⬇️ **Download and open:** Every project ships its `.pbix` file — open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free) to interact with the live report.
- 🖼️ **Just want to look:** Each project's `Screenshots/` folder has a full visual walkthrough if you'd rather not open Power BI at all.

---

## Projects

### 1. [IPL Data Analytics Dashboard](./01_IPL%20Dashboard%20in%20Power%20BI)

![IPL Overview](01_IPL%20Dashboard%20in%20Power%20BI/Screenshots/04_ipl_overview_page.png)

An interactive dashboard built on IPL data across all seasons (2008–2024) — match analysis, team performance, and player statistics, with 20+ DAX measures and bookmark-based navigation.

- **Dataset:** IPL all-seasons (Matches + Deliveries CSV)
- **Highlights:** Orange/Purple Cap tracking, toss-impact analysis, drill-through player cards
- **[Read the full README →](<./01_IPL Dashboard in Power BI/README.md>)**

### 2. [Global Super Store Analytics Dashboard](./02_Global%20Super%20Store)

![Global Super Store Overview](02_Global%20Super%20Store/Screenshots/01_executive_overview.png)

A 15-page dashboard plus a parameter-driven paginated invoice report, built on a 51K-order global retail dataset spanning 147 countries — translating a written business brief into executive KPIs, churn analysis, and a decomposition tree.

- **Dataset:** Global Super Store (51,290 orders, 2016–2019, 147 countries)
- **Highlights:** 30+ DAX measures, Field Parameters, What-if parameters, an RDL paginated report, Power BI Service deployment
- **[Read the full README →](<./02_Global Super Store/README.md>)**

### 3. [Adventure Works Sales Dashboard](./03_Advanture%20Works)

![Adventure Works Overview](03_Advanture%20Works/Screenshots/01_dashboard_overview.png)

A simulated client engagement built from a 9-part stakeholder brief — a 7-page star-schema dashboard with a custom Reseller Loyalty Score, plus a Power Automate flow that emails a live sales summary on demand.

- **Dataset:** Adventure Works sales, reseller, and salesperson data
- **Highlights:** 25+ DAX measures, star-schema modeling, drillthrough navigation, no-code Power Automate integration
- **[Read the full README →](<./03_Advanture Works/README.md>)**

### 4. [Financial Dashboard — Power BI + Python Automation](./05_Financial%20Dashboard)

![Financial Dashboard Overview](05_Financial%20Dashboard/Screenshots/01_dashboard_overview.png)

Built for a US government credit-risk client whose real bottleneck wasn't the dashboard — it was a 5-hour manual daily data pipeline. Solved with an Outlook → Power Automate → Python/Google Drive API pipeline feeding a 4-page credit-risk dashboard with a custom LTV scoring model.

- **Dataset:** ~25 daily survey files, merged and cleaned via an automated pipeline
- **Highlights:** 3-stage automation pipeline, Google Drive API with service-account auth, custom LTV scoring model
- **[Read the full README →](<./05_Financial Dashboard/README.md>)**

---

## What this portfolio demonstrates

- End-to-end Power BI workflows across 4 distinct datasets: raw data → Power Query cleaning → data modeling → DAX → interactive dashboard
- Progression from single-dataset analysis (IPL) toward business-brief-driven work (Global Super Store) and simulated client engagements (Adventure Works, Financial Dashboard)
- 100+ custom DAX measures written across the portfolio, spanning time intelligence, ranking, churn, custom scoring models, and conditional classification
- Beyond-the-dashboard skills: RDL paginated reports, Power BI Service deployment, and Power Automate flows that connect Power BI to the wider Power Platform
- A project where the dashboard was the smaller half of the deliverable — the Financial Dashboard's real value came from replacing a manual, error-prone data pipeline with an automated one

---

## Skills covered across this portfolio

| Area | Where it shows up |
|---|---|
| Power Query (M) | All 4 projects — null handling, merges, appends, calculated columns |
| DAX | 100+ measures — `CALCULATE`, `FILTER`, `ALL`/`ALLEXCEPT`, `RANKX`, `SWITCH`, time intelligence |
| Data modeling | Star-schema design, cross-filter direction, Date and financial-calendar tables |
| Advanced interactivity | Bookmarks, Field Parameters, What-if parameters, drillthrough, custom tooltips |
| Reporting formats | Standard dashboards + an RDL paginated report (Power BI Report Builder) |
| Automation | Power Automate email flows, a Python + Google Drive API pipeline |
| Deployment | Power BI Service publishing |

---

## Repo structure

```
powerbi-data-analytics-portfolio/
│
├── 01_IPL Dashboard in Power BI/
│   ├── README.md
│   ├── Screenshots/
│   ├── Learnings/
│   ├── Report/
│   └── indian-premier-league-ipl-all-seasons.zip
│
├── 02_Global Super Store/
│   ├── README.md
│   ├── DataSet/
│   ├── Reports/
│   └── Screenshots/
│
├── 03_Advanture Works/
│   ├── README.md
│   ├── Datasets/
│   ├── Report/
│   ├── Screenshots/
│   └── Adventure Works.pdf
│
├── 05_Financial Dashboard/
│   ├── README.md
│   ├── Automation/
│   ├── Data/
│   ├── Report/
│   ├── Screenshots/
│   └── Financial Dashboard.pdf
│
└── README.md   ← you are here
```

## Tools used

- Microsoft Power BI Desktop & Power BI Service
- Power Query (M language)
- DAX (Data Analysis Expressions)
- Power BI Report Builder (paginated/RDL reports)
- Power Automate
- Python (`pandas`, Google Drive API) for pipeline automation

---

## About the author

Rushit Tholiya — 3rd year B.Tech (Computer Science) at Nirma University, Ahmedabad

Currently building skills in data analysis and data science, working through a structured Power BI → SQL → Python roadmap toward a career in **data science / data analytics**.

- [LinkedIn](https://linkedin.com/in/rushit-tholiya-605341311)
- [GitHub profile](https://github.com/Rushit004)