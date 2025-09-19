# Spotify Performance Analysis Project

## Overview

This project was conducted in July 2025 as part of the Data Analytics training program.  
The goal was to clean and enrich Spotify’s financial and user engagement dataset, engineer additional KPIs, and develop stakeholder-focused dashboards in Tableau.  

The project addressed the needs of **three key stakeholders** at Spotify:  

- **Sarah (Head of Strategy)** – focused on long-term growth and user trends  
- **Mark (Director of Revenue)** – optimizing revenue streams and ARPU  
- **Olivia (VP of Operations)** – ensuring cost efficiency and operational effectiveness  

🔗 **Tableau Public Dashboard:** [Spotify Project](https://public.tableau.com/views/SpotifyProject_17534541379890/DB1_KPIOverview?:language=de-DE&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## Project Objectives

- Provide a comprehensive analysis of Spotify’s revenue, costs, and user base  
- Deliver actionable insights to improve profitability, engagement, and efficiency  
- Build **interactive dashboards** tailored to each stakeholder’s perspective  
- Document KPI calculations and design assumptions for transparency  

---

## Dataset

The dataset (Q1/2017 – Q1/2023) contained Spotify’s financial and engagement metrics.  
Key fields included:  

- **Revenue & Profitability:** Total Revenue, Premium Revenue, Ad Revenue, Gross Profit, Net Profit  
- **User Metrics:** MAUs, Premium MAUs, Ad MAUs, ARPU (Premium & Ad)  
- **Cost Structure:** Cost of Revenue, Sales & Marketing, R&D, General & Administrative  
- **Derived KPIs (engineered):**  
  - ARPU (Ad & Premium)  
  - CAC (Customer Acquisition Cost) for Ad and Premium  
  - LTV (Lifetime Value) & LTV/CAC Ratio  
  - Profitability Ratios (Gross Profit %, CIR, etc.)  

---

## Approach

1. **Data Review & Cleaning**  
   - Corrected inconsistencies in Google Sheets (e.g., revenue, cost, profit figures)  
   - Added missing metrics like **Net Profit**  
   - Created a clean, enriched dataset for analysis  

2. **Feature Engineering / KPI Development**  
   - Researched KPI logic for freemium business models (churn rate, LTV, CAC)  
   - Implemented formulas for ARPU, LTV, CAC, LTV/CAC Ratio  
   - Validated results against existing benchmarks  

3. **Scope of Work & Design Plan (Phase 1)**
   - Defined stakeholder questions and KPIs  
   - Mapped deliverables and milestones (Dashboard, Report, Recording)  

4. **Dashboard Design (Phase 2)**
   - **Overview Dashboard** – High-level KPIs for Strategy (Sarah)  
   - **User Details Dashboard** – Detailed ARPU, MAU, LTV/CAC for Revenue (Mark)  
   - **Cost Structure Dashboard** – Cost breakdown and efficiency analysis for Operations (Olivia)  
   - **Key Insights & Recommendations** – Strategic takeaways per stakeholder  
   - **Annotations Page** – Documented formulas and KPI assumptions  

---

## Deliverables

- **Cleaned Dataset** (Google Sheets)  
- **Scope of Work & Design Plan** (PDF)  
- **Final Report** (PDF with insights & recommendations)  
- **Tableau Dashboards** (Overview, User Details, Cost Structure, Key Insights, Recommendations, Annotations)  
- **Recorded Presentation** (project summary & walkthrough)  

---

## Key Insights

- **Revenue & Profitability**: Premium accounts drive revenue growth, but profitability is still negative due to low ad monetization and high CAC.  
- **User Growth**: MAUs are growing, but the share of paying Premium users is decreasing → pressure on ARPU.  
- **Ad-Supported Users**: Very low ARPU, generating losses. Opportunity lies in better ad monetization and Free-to-Premium conversion.  
- **Cost Structure**: Over 60% of costs are tied to Premium delivery. R&D and Marketing costs are rising → efficiency potential identified.  

---

## Recommended Actions

**Sarah (Strategy)**  

- Focus on sustainable Premium growth  
- Monitor Ad vs. Premium MAU ratio as early signal  

**Mark (Revenue)**  

- Improve ARPU through pricing and upsell strategies  
- Strengthen ad monetization (targeted formats, brand partnerships)  
- Systematically drive Free-to-Premium conversions  

**Olivia (Operations)**  

- Streamline Premium delivery costs  
- Analyze R&D and Sales & Marketing spend for efficiency  
- Use **LTV/CAC Ratio** as a core KPI for efficiency management  

---

## Results

- A fully functional **Spotify-branded Tableau dashboard** serving stakeholder needs  
- Clear documentation of **KPIs and assumptions**  
- Actionable recommendations for growth, profitability, and efficiency  
- Professional end-to-end workflow: **data cleaning → KPI engineering → dashboard → reporting**  

---

## Repository Structure

- **data/**
  - `spotifyData_cleanFinal.xlsx` – cleaned and enriched dataset  
- **reports/**
  - `SpotifyProject_ScopeOfWork_Designplan Phase1.pdf` – scope of work & design plan  
  - `SpotifyProject_Final Report.pdf` – final report with insights & recommendations  
- **dashboards/**
  - `Tableau_Public_Link.txt` – link to published Tableau dashboard  
- **README.md** – project documentation (this file)

---

📊 **Tableau Public Dashboard:** [Spotify Project](https://public.tableau.com/views/SpotifyProject_17534541379890/DB1_KPIOverview?:language=de-DE&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
✍️ **Author:** Thomas Jortzig  
📅 **Date:** July 2025
