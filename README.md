#  Bellabeat Menstrual-Cycle Activity Analysis  
### *Exploring how daily activity patterns vary across menstrual cycle phases using Fitbit data*

 **Live HTML Report:**  
https://anna-ann11.github.io/bellabeat-menstrual-cycle-analysis/

---

##  Project Overview  
This project analyzes **Fitbit daily activity data for 33 users** and aligns each activity day with a **simulated menstrual cycle phase**.  
The goal: identify whether activity patterns change across phases — and how Bellabeat could use those insights to personalize the user experience.

This is a complete **end-to-end data analysis project**, showcasing the workflow from raw data → cleaning → simulation → SQL merging → EDA → dashboard → insights → recommendations.

---

##  Key Business Question  
**Do daily step patterns vary across menstrual cycle phases in a meaningful way, and can Bellabeat use those differences for personalization?**

---

##  Tools & Skills Used  
- **R** → data cleaning, simulation, analysis, plotting  
- **SQL (BigQuery)** → rolling joins, window functions, segmentation  
- **Tableau** → interactive dashboard visuals  
- **R Markdown** → full narrative reporting  
- **Git/GitHub** → version control & project hosting  

---

##  Project Structure  
bellabeat-menstrual-cycle-analysis/
│
├─ Bellabeat_case_study.Rmd # Full analysis report
├─ Bellabeat_case_study.html # Rendered HTML report
├─ daily_activity_cycles_full.csv # Activity + cycle merged data
├─ periods_simulated.csv # Simulated period start data
├─ Extracted_Id.csv # User IDs + first activity dates
│
├─ images/ # Report visuals
│ ├─ chart_cycleday_line.png
│ ├─ chart_phase_bars.png
│ ├─ chart_scatter_user_activity.png
│ ├─ excel_dailyActivity_sample.png
│ └─ (others...)
│
├─ analysis_outputs/ # Analysis CSV + PNG outputs
│ ├─ phase_summary.csv
│ ├─ cycleday_trend.csv
│ └─ user_delta_fol_minus_men.csv
│
├─ docs/ # GitHub Pages site (index.html)
│ └─ index.html
│
└─ README.md

---

##  Summary of Findings  
###  Phase Differences  
- **Ovulatory & Luteal phases** → slightly higher average steps  
- **Menstrual phase** → lowest activity  
- Changes are **consistent but small** (not huge effect sizes)

###  Cycle-Day Trend  
- Gentle rise around **days 13–18** (mid-cycle)

###  User-Level Variation  
- Most users show small changes  
- Some show strong cycle-sensitivity  
- Others are cycle-neutral  
- → Personalization > generalization

###  Cycle Confidence  
- “High-confidence” users show cleaner phase patterns  
- Best candidates for cycle-aware features

---

##  Dashboard Preview  
This project includes a Tableau dashboard (screenshots in repo + report) to explore:

- user-level trends  
- phase comparisons  
- cycle-day patterns  
- segmentation insights  

---

##  Why This Project Matters  
This work demonstrates how Bellabeat could move toward **cycle-aware personalization**.

It shows:  
- robust data preparation  
- advanced SQL merging  
- thorough EDA  
- statistical reasoning  
- stakeholder-friendly communication  

Perfect for **analytics roles** that value real, reproducible project work.

---

##  Reproducibility  
All code and data needed to re-run the analysis are included.  
Re-render the report with:

```r
rmarkdown::render("Bellabeat_case_study.Rmd")
Personal Note

This project was created as part of the Google Data Analytics Professional Certificate.
It combines data cleaning, simulation, SQL engineering, analysis, visualization, and storytelling into one polished case study.

If you're reviewing this project — thanks for taking the time!
