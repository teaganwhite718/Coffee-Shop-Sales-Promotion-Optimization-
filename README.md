
# The Caffeine Crew — Coffee Shop Promotions Project ☕️

## What this project is
This project analyzes coffee shop sales data to answer one marketing question:
**How can a coffee shop optimize the timing and type of promotions to increase customer engagement and sales?**

## Data used📍
We used a Kaggle dataset with transactions from three coffee shop locations in New York City for 2023.  
It includes transaction date/time, store location, product category, quantity, and price.

## Tools used⚙️
- **Python** (data cleaning, analysis, and modeling)  
- **Jupyter Notebook** (`marketing_caffeine_crew (1).ipynb`)  
- **pandas** (data manipulation)  
- **matplotlib / matplotlib.pyplot** (charts and visualizations)  
- **seaborn** (visualizations)  
- **statsmodels.api** (regression modeling)  
- **matplotlib.ticker** (plot formatting)  

## What we did📊
- Created a revenue field (quantity × price)  
- Looked at revenue trends over time (daily revenue across the year)  
- Compared revenue by store location  
- Analyzed peak hours and slower hours  
- Built a product category by time-of-day heat map  
- Ran regression models to understand which factors were most associated with revenue changes  

## Key findings (high level)
- Revenue increased over the year.  
- The three locations performed similarly overall.  
- Morning hours were strongest; evenings were weakest.  
- Mondays performed best and Tuesdays were consistently the weakest day.  

## Recommendations
- Staff and stock more heavily during morning peak hours.  
- Run targeted promotions on Tuesdays to lift the slowest day.  
- Use a loyalty program aimed at morning commuters.  
- Test off-peak offers (afternoon/evening) to increase traffic in slower periods.  

## Files
- `caffeine_crew_slides_under25mb.pdf` — Presentation slides (compressed under 25MB)
- `Caffeine Crew Report 1A (2).pdf` — Technical appendix and analysis details  
- `marketing_caffeine_crew (1).ipynb` — Working notebook (analysis + visualizations)

## Notes / limitations
The dataset covers only 2023 and does not include customer demographics, weather, holidays, events, or competitor activity, so results may not capture every driver of de
