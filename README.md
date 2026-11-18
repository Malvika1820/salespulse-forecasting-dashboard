
#  SalesPulse — Sales Forecasting & Pipeline Analytics Dashboard

A full-featured, web-based **Sales Forecasting & Pipeline Analytics Dashboard** built for real-time revenue intelligence, funnel diagnostics, and interactive scenario modeling.

 **Live Demo:** `https://github.com/Malvika1820/salespulse-forecasting-dashboard/tree/main`

---

##  Project Overview
Traditional sales forecasting relies heavily on static spreadsheets and manual assumptions, making it difficult to detect stalled deals or accurately project quarterly revenue[cite: 14]. **SalesPulse** solves this by combining multi-user session authentication, universal CRM/Kaggle CSV ingestion, probability-weighted pipeline analytics, time-series linear regression forecasting, and automated AI diagnostic alerts inside a zero-latency browser application.

---

##  Key Features
*  Multi-User Authentication & Session Persistence:** Split-screen Sign In / Sign Up portal with dynamic user profile personalization (displays logged-in user's full name, email, and avatar initials via `localStorage`)[cite: 14].
*  Universal CSV Ingestion & Regex Schema Mapping:** Automatically parses and normalizes external CSV exports from **Salesforce**, **Maven Analytics**, and **Kaggle** using PapaParse and regular-expression column matching[cite: 14]. Includes a built-in **165-deal B2B enterprise dataset** for instant demonstration[cite: 14].
*  AI Executive Insights Engine:** Automatically scans pipeline health to flag quota attainment pacing, high-value whale opportunities, and deals aging over 60 days[cite: 14].
*  Interactive What-If Simulation Sliders:** Adjust conversion probabilities across funnel stages (`Qualification`, `Demo`, `Proposal`, `Negotiation`) in real time to simulate revenue impact[cite: 14].
*  Predictive Forecasting & Analytics Suite:**
  * KPI Summary Cards:** Raw Open Pipeline, Weighted Forecast, Closed Won Revenue, and Win Rate[cite: 14].
  * Stage Funnel & Rep Leaderboard:** Interactive Chart.js bar and stacked charts[cite: 14].
  * 60-to-90-Day Linear Regression Forecast:** Projects upcoming monthly revenue run-rate from historical closed-won trends[cite: 14].
  * Deal Aging Risk Matrix:** Scatter plot highlighting high-value deals stalled in the funnel[cite: 14].
*  Export & Briefing Tools:** Filterable Opportunity Deal Ledger, one-click CSV export of at-risk deals, and a print-ready executive briefing stylesheet[cite: 14].

---

##  Technology Stack
* **Frontend Structure & Styling:** HTML5, CSS3 (Grid, Flexbox, Custom Variables)[cite: 14]
* **Analytics & Core Logic:** Vanilla JavaScript (ES6+)[cite: 14]
* **Data Visualization:** Chart.js (v4)[cite: 14]
* **CSV Parsing:** PapaParse (v5.4)[cite: 14]
* **Persistence:** Browser Web Storage API (`localStorage`)[cite: 14]

---

##  How to Run & Test
1. **Live Web App:** Open the GitHub Pages link above (or open `index.html` in any modern web browser)[cite: 14].
2. **Sign In:** Enter your name, email, and password to see your personalized profile appear in the top navbar, or click **Instant 1-Click Guest Demo**[cite: 14].
3. **Upload Data:** Click **Upload CSV** and select any CRM or Kaggle dataset (e.g., `sales_pipeline.csv`) to watch all KPIs and charts update automatically[cite: 14].

---

##  Repository Contents
* `index.html` — Complete single-page web application (Authentication + Analytics Dashboard)[cite: 14]
* `SalesPulse_Project_Report_Final.docx` — Complete Mini Project Report (Presidency University Format)[cite: 24]


---

##  Team Members (Presidency University, Bengaluru)
* **Malvika** — `20231CSD0155`
* **Vaishnavi** — `20231CSD0112`
* **Raziya** — `20241CSD3001`
* **Tejasvini** — `20241CSD3002`

**Program:** B.Tech in Computer Science & Engineering (Data Science) — Course Code: `CSS7102` (Batch: `CSD25`)  
**Under the Guidance of:** Ms. P. Sai Sudha, Assistant Professor, School of Computer Science & Engineering
