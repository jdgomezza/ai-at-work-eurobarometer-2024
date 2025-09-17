# AI at Work — Eurobarometer 2024 (EB 101.4)

**Goal:** analyze how workers across selected EU countries perceive and experience AI at work:
- **Employer AI awareness**  
- **AI used for performance/sanctions**  
- **Perception: AI improves workers’ safety**

**Stack:** Python (Pandas, Matplotlib) · Jupyter · Eurobarometer 101.4 (2024)

---

## Highlights

<img src="output/highlights_bar.png" alt="Country highlights bar chart" width="680">

- **Austria (AT)** — awareness: **~73%** (fairly+totally), safety positive: **~76%**
- **France (FR)** — awareness: **~52%**, safety positive: **~67%**
- **Poland (PL)** — awareness: **~74%**, safety positive: **~65%**
- **Spain (ES)** — awareness: **~71%**, safety positive: **~77%**

> See `output/highlights.csv` for all values used in this summary.

---

## Full Results (charts)

**Employer AI awareness (by country)**  
<img src="output/ai_awareness_stacked.png" alt="Employer AI awareness by country" width="680">

**AI used for performance/sanctions (by country)**  
<img src="output/ai_used_for_performance_stacked.png" alt="AI used for performance/sanctions by country" width="680">

**Perception: AI improves workers’ safety (by country)**  
<img src="output/ai_improves_safety_stacked.png" alt="AI improves workers' safety by country" width="680">

---

## Data

- **Source:** Eurobarometer 101.4 (2024) — “AI at work” module.  
  Dataset: **ZA8844** (SPSS `.sav`).  
  How to obtain: Download from **GESIS** after free registration.  
- This repo **does not** include raw data. Place the `.sav` file in `data/` if you want to reproduce.

---

## How to run

1. **Clone / Download** this repo (Code → Download ZIP or clone).
2. Create a Python 3.10+ environment and install deps:
   ```bash
   pip install -r requirements.txt
