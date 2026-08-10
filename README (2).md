# Joseph Bernard O. — Business Intelligence Analyst Portfolio

> **Live Site:** [josephbernard.github.io](https://josephbernard.github.io) &nbsp;|&nbsp; **LinkedIn:** [linkedin.com/in/josephbernard](https://linkedin.com/in/josephbernard) &nbsp;|&nbsp; **Location:** Lagos, Nigeria

---

## 👤 About

Business Intelligence Analyst with 5+ years of experience delivering end-to-end data solutions across retail and FMCG environments. Specialising in **SQL**, **Power BI**, **DAX**, and **Excel** to transform raw transactional data into boardroom-ready dashboards that drive measurable business outcomes.

| Metric | Result |
|---|---|
| Reporting time reduction | **70%** via Power BI automation |
| YoY revenue growth contributed | **32%** |
| Inventory planning accuracy | **+15%** |
| Reporting accuracy improvement | **+30%** |

---

## 📁 Repository Structure

```
joseph-portfolio/
│
├── index.html                        # Main portfolio website
│
└── assets/
    ├── profile.png                   # Profile photo
    ├── Joseph_Bernard_CV.pdf         # Downloadable CV / Resume
    │
    ├── # Beverages Ltd Project
    ├── sql-extraction.png            # SQL data extraction screenshot
    ├── sql-query.png                 # SQL validation / UNION query screenshot
    ├── data-modeling.png             # Power BI star schema model screenshot
    ├── Beverages_Ltd_Portfolio.pdf   # BI portfolio case study (PDF)
    ├── BeveragesCo_Dashboard.pdf     # Full dashboard export (PDF)
    │
    └── # Sales Analytics Project
        ├── sa-executive.jpg          # Executive Summary page screenshot
        ├── sa-sales-perf.png         # Sales Performance page screenshot
        ├── sa-product-region.png     # Product & Region page screenshot
        ├── sa-operations.png         # Operations & Trends page screenshot
        ├── sa-drillthrough.png       # Drill-through detail page screenshot
        └── Sales_Analytics_Portfolio.pdf  # Case study (PDF)
```

---

## 📊 Portfolio Projects

### Project 1 — Beverages Ltd: Revenue Risk & Payment Intelligence Dashboard

**Industry:** Beverage Distribution · **Region:** United States (West, Northeast, South)  
**Tools:** SQL Server · Power BI · Excel · DAX · Power Query · Azure Maps  
**Video:** [▶ Watch Walkthrough on YouTube](https://youtu.be/g6XoKkZPKb8)

**Business Problem:**  
Beverages Ltd had no unified view of payment velocity across its four major retail partners. With individual retailers operating on 30–65 day payment cycles and no early warning system, the business could not identify credit risk before receivables aged into bad debt.

**Solution:**  
A six-page interactive Power BI report built end-to-end — SQL extraction → Excel validation → Power BI modelling and visualisation. Surfaces £40.79K of at-risk revenue with real-time drill-through, retailer credit scoring, and geographic risk mapping via Azure Maps.

**Key Results:**

| KPI | Outcome |
|---|---|
| Total Revenue Tracked | **£1.21M** |
| Revenue at Risk Surfaced | **£40.79K (3.36%)** |
| Avg Days-to-Pay (post-Q1 policy) | **30 days** (reduced from 34) |
| Total Units Analysed | **2M+** |
| Dashboard Pages | **6** |

**Key Findings:**
- 🔴 **Costco** — 65-day cycle, 34 days beyond target, 100% red aging profile. Escalated to critical credit review
- 🟡 **Target** — Highest proportional risk at 17.08% revenue at risk despite average payment days
- 🟢 **Q1 Policy Enforcement** — Collections stabilised at 30 days and held flat for 8 consecutive months
- 🗺 **West Region** — Generates 47.9% of total revenue (£582.40K); New York's 360-day anomaly flagged

---

### Project 2 — Sales Analytics Dashboard

**Industry:** Multi-product Retail · **Dataset:** 13 months (Dec 2023 – Dec 2024)  
**Tools:** SQL · Power BI · Excel · DAX · Power Query  
**Video:** [▶ Watch Walkthrough on YouTube](https://youtu.be/VsWR1EkGPHU?si=1Dj1zneawoD4yfnf)

**Business Problem:**  
Sales, regional, and operations teams worked from separate reports with inconsistent KPI definitions, no single source of truth, and no rule-based growth classification — preventing proactive decision-making.

**Solution:**  
A four-page interactive Power BI report serving four distinct stakeholder audiences from a single star-schema data model. Moves beyond "what happened" reporting into diagnostic analysis — explaining revenue drivers, identifying risk concentrations, and delivering actionable stakeholder recommendations.

**Key Results:**

| KPI | Outcome |
|---|---|
| Total Revenue | **£2,041,646** |
| Total Orders | **625** |
| Average Order Value | **£3,267** |
| On-Time Delivery Rate | **64%** |
| Peak Month | **Oct 2024 — £192,662** |
| Top Region | **North — £449,767** |
| Top Product | **Printer — £374K** |

**Dashboard Pages:**
1. **Executive Summary** — 30-second health check: revenue trend, growth-category donut, top 5 products, auto-generated insight narrative
2. **Sales Performance** — YTD revenue, rolling 3M revenue, MoM combo chart, regional stacked area, product × region heat matrix
3. **Product & Region** — Revenue ranking, revenue vs volume scatter plot, quarterly grouped columns, product & region intelligence callouts
4. **Operations & Trends** — Delivery reliability, speed distribution, regional benchmark comparison, drill-through order detail table

**Advanced DAX Techniques:**
- `SWITCH(TRUE())` + `RANKX` for dynamic 3-tier colour coding
- Rolling 3-month average rebuilt with `EDATE` string navigation — resolved Calendar-table filter-context bug
- Dynamic MoM growth classification: High Growth (>20%) / Moderate (0–20%) / Decline (<0%)

---

## 🛠 Technical Stack

| Category | Technologies |
|---|---|
| **Database & Querying** | SQL Server, Joins, Aggregations, UNION, WHERE / GROUP BY |
| **BI & Visualisation** | Power BI Desktop, DAX, Star Schema Modelling, Azure Maps, Drill-through |
| **Data Processing** | Excel (Advanced), VLOOKUP/XLOOKUP, Power Query (M Language), ETL |
| **Analysis Techniques** | KPI Design, Trend Analysis, Risk Modelling, Forecasting, Data Storytelling |

---

## 💼 Professional Experience

**Data Analyst — Jendol Superstore, Lagos** *(2023 – Present)*  
- Automated Power BI dashboards → **70% reduction** in reporting turnaround
- Data validation improvements → **30% increase** in reporting accuracy
- Trend analysis for inventory → **15% increase** in product availability
- Contributed to **32% YoY revenue growth** through data-driven insights

**Data Analyst — Prestige Superstore, Lagos** *(2021 – 2023)*  
- SQL + Excel KPI tracking: ATV, conversion rate, sales per sqm
- Power BI dashboard development → **40% reduction** in manual workload
- Inventory optimisation → **15% reduction** in overstock and stockouts

---

## 🎓 Education & Certifications

- **BSc Computer Science** — University of Ilorin, Nigeria
- **Microsoft Certified: Data Analyst Associate** (Power BI)
- **SQL for Data Analysis** — DataCamp
- **Advanced Excel for Data Analytics** — Coursera
- **Google Prompting Essentials** — Google
- **Business Analysis & Process Management**

---

## 🚀 Deploying to GitHub Pages

1. Create a new GitHub repository (e.g. `josephbernard.github.io` or any repo name)
2. Upload all files maintaining the folder structure above
3. Go to **Settings → Pages → Source → Deploy from branch → main / (root)**
4. Your portfolio will be live at `https://yourusername.github.io`

> **Note:** Update the `mailto:` email address and LinkedIn/GitHub URLs in `index.html` before deploying.

---

## 📬 Contact

- **Email:** joseph.bernard@email.com *(update before deployment)*
- **LinkedIn:** [linkedin.com/in/josephbernard](https://linkedin.com/in/josephbernard) *(update before deployment)*
- **Location:** Lagos, Nigeria · Open to Remote & Relocation

---

*Portfolio built with HTML, CSS and vanilla JavaScript — no frameworks, no dependencies, fully static and GitHub Pages ready.*
