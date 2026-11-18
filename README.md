
#  SalesPulse — Sales Forecasting & Pipeline Analytics Dashboard

A full-featured, web-based **Sales Forecasting & Pipeline Analytics Dashboard** built for real-time revenue intelligence, funnel diagnostics, and interactive scenario modeling.

 **Live Demo:** `https://github.com/Malvika1820/salespulse-forecasting-dashboard/tree/main`

---

##  Project Overview
Traditional sales forecasting relies heavily on static spreadsheets and manual assumptions, making it difficult to detect stalled deals or accurately project quarterly revenue. **SalesPulse** solves this by combining multi-user session authentication, universal CRM/Kaggle CSV ingestion, probability-weighted pipeline analytics, time-series linear regression forecasting, and automated AI diagnostic alerts inside a zero-latency browser application.

---

##  Key Features
*  Multi-User Authentication & Session Persistence:** Split-screen Sign In / Sign Up portal with dynamic user profile personalization (displays logged-in user's full name, email, and avatar initials via `localStorage`).
*  Universal CSV Ingestion & Regex Schema Mapping:** Automatically parses and normalizes external CSV exports from **Salesforce**, **Maven Analytics**, and **Kaggle** using PapaParse and regular-expression column matching. Includes a built-in **165-deal B2B enterprise dataset** for instant demonstration.
*  AI Executive Insights Engine:** Automatically scans pipeline health to flag quota attainment pacing, high-value whale opportunities, and deals aging over 60 days.
*  Interactive What-If Simulation Sliders:** Adjust conversion probabilities across funnel stages (`Qualification`, `Demo`, `Proposal`, `Negotiation`) in real time to simulate revenue impact.
*  Predictive Forecasting & Analytics Suite:**
  * KPI Summary Cards:** Raw Open Pipeline, Weighted Forecast, Closed Won Revenue, and Win Rate.
  * Stage Funnel & Rep Leaderboard:** Interactive Chart.js bar and stacked charts.
  * 60-to-90-Day Linear Regression Forecast:** Projects upcoming monthly revenue run-rate from historical closed-won trends.
  * Deal Aging Risk Matrix:** Scatter plot highlighting high-value deals stalled in the funnel.
*  Export & Briefing Tools:** Filterable Opportunity Deal Ledger, one-click CSV export of at-risk deals, and a print-ready executive briefing stylesheet.

---

##  Technology Stack
* **Frontend Structure & Styling:** HTML5, CSS3 (Grid, Flexbox, Custom Variables)
* **Analytics & Core Logic:** Vanilla JavaScript (ES6+)
* **Data Visualization:** Chart.js (v4)
* **CSV Parsing:** PapaParse (v5.4)
* **Persistence:** Browser Web Storage API (`localStorage`)

---

##  How to Run & Test
1. **Live Web App:** Open the GitHub Pages link above (or open `index.html` in any modern web browser)[cite: 14].
2. **Sign In:** Enter your name, email, and password to see your personalized profile appear in the top navbar, or click **Instant 1-Click Guest Demo**.
3. **Upload Data:** Click **Upload CSV** and select any CRM or Kaggle dataset (e.g., `sales_pipeline.csv`) to watch all KPIs and charts update automatically.

---

##  Repository Contents
* `index.html` — Complete single-page web application (Authentication + Analytics Dashboard)
* `SalesPulse_Project_Report_Final.docx` — Complete Mini Project Report (Presidency University Format)


---

##  Team Members (Presidency University, Bengaluru)
* **Malvika** — `20231CSD0155`
* **Vaishnavi** — `20231CSD0112`
* **Raziya** — `20241CSD3001`
* **Tejasvini** — `20241CSD3002`

**Program:** B.Tech in Computer Science & Engineering (Data Science) — Course Code: `CSS7102` (Batch: `CSD25`)  
**Under the Guidance of:** Ms. P. Sai Sudha, Assistant Professor, School of Computer Science & Engineering
