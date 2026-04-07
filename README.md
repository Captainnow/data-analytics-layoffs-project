# Global Tech Layoffs Dashboard

Global Tech Layoffs Dashboard is an Excel‑based analytics project built from a real layoffs dataset. It summarizes thousands of layoff events by year, industry, and funding stage, and presents them in a clean, recruiter‑friendly dashboard for data‑analytics portfolios.

---

## Features

- **KPI Overview (Dashboard sheet)**  
  - Total unique companies affected by layoffs.  
  - Total number of people laid off across the dataset.  
  - Clear title and subtitle so recruiters immediately understand the problem you solved.

- **Layoffs Over Time**  
  - Column chart showing how layoffs change by year, derived from the `date` column in the dataset.

- **Top 10 Industries by Layoffs**  
  - Horizontal bar chart ranking industries (e.g., Consumer, Finance, Healthcare, Retail, Crypto) by total people laid off.

- **Layoffs by Funding Stage**  
  - Column chart showing layoff concentration across stages such as Seed, Series A–E, Post‑IPO, Acquired, and Unknown.

- **Clean, Recruiter‑Ready Design**  
  - Separate `Dashboard` sheet focused on visuals and KPIs.  
  - `Summary` sheet with underlying pivot‑style aggregations.  
  - `Data` sheet holding the raw dataset for transparency.

---

## Dataset

- Source file: `layoffs.csv` (tech layoffs with columns such as `company`, `location`, `industry`, `total_laid_off`, `percentage_laid_off`, `date`, `stage`, `country`, and `funds_raised_millions`).  
- The Excel workbook extracts `year` from `date` and groups by `industry` and `stage` to compute totals.

If you publish the CSV, mention the original source or link (for example, the popular tech layoffs dataset) in your repo description.

---

## Repository Structure

```text
layoffs-dashboard/
├─ layoffs_dashboard.xlsx   # Final Excel dashboard (Dashboard, Summary, Data sheets)
├─ layoffs.csv              # Raw dataset (if license allows)
├─ scripts/                 # (Optional) Python or SQL scripts used for cleaning/aggregation
└─ README.md                # Project documentation
```

The key artifact for recruiters is `layoffs_dashboard.xlsx` — they can open it and immediately see the Dashboard sheet.

---

## How to Use

1. **Clone the repository**

```bash
git clone https://github.com/your-username/layoffs-dashboard.git
cd layoffs-dashboard
```

2. **Open the Dashboard**

- Open `layoffs_dashboard.xlsx` in Excel (or compatible spreadsheet software).  
- Go to the **Dashboard** sheet to view KPIs and charts.  
- Use the **Summary** sheet if you want to inspect the underlying grouped tables.

3. **Explore / Extend**

- Filter the underlying `Data` sheet by country, industry, or stage and watch your charts update.  
- Add new pivot tables or charts (e.g., layoffs by country or by month/quarter) to extend the analysis.

---

## What This Project Demonstrates

For recruiters and hiring managers, this project shows that you can:

- Clean and structure a real‑world dataset with missing values and multiple categorical dimensions.  
- Design meaningful aggregations (by year, industry, funding stage) and calculate portfolio‑level KPIs.  
- Build a **professional Excel dashboard** with clear charts, labels, and layout — exactly what a data analyst does in many business environments.

You can reference this project in your resume as:

> “Built an Excel analytics dashboard on global tech layoffs, aggregating 2K+ events by year, industry, and funding stage, and presenting recruiter‑friendly KPIs and charts.”
> <img width="899" height="552" alt="image" src="https://github.com/user-attachments/assets/da78ef47-ab2e-4f8b-b05d-8933bc3f378d" />


---

## Author

**V. Karthikeyan**  
Aspiring Data Analyst / Biomedical Engineer – focusing on data analytics, dashboards, and AI projects in healthcare and technology.
