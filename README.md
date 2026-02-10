# Coffee-Shop-Sales-Promotion-Optimization-
# The Caffeine Crew — Coffee Shop Promotions Project

## What this project is
This project looks at coffee shop sales data and answers one marketing question:
**How can a coffee shop choose the right promotion type and timing to increase sales and customer engagement?**
(See slides and report for full context.) 

## Data used
We used a Kaggle dataset with transactions from three coffee shop locations in New York City for 2023.
It includes transaction date/time, store location, product category, quantity, and price. 

## What we did
- Created a revenue field (quantity × price)
- Looked at revenue trends over time (daily revenue across the year)
- Compared revenue by store location
- Analyzed peak hours and slower hours
- Compared product categories by time of day (heat map)
- Ran regressions to understand which factors were most associated with revenue changes :contentReference[oaicite:3]{index=3}

## Key findings (high level)
- Revenue increased over the year.
- The three locations performed similarly overall.
- Morning hours generated the highest revenue; evenings were the weakest.
- Mondays performed best and Tuesdays were consistently the weakest day. 

## Recommendations
- Staff and stock more heavily during morning peak hours.
- Run targeted promotions on Tuesdays to lift the slowest day.
- Use a loyalty program aimed at morning commuters.
- Test off-peak offers (afternoon/evening) to increase traffic in slower periods. 

## Files
- `caffeine crew slides (marketing).pdf` — Presentation slides
- `Caffeine Crew Report 1A (2).pdf` — Technical appendix and analysis details

## Notes / limitations
The dataset only covers 2023 and doesn’t include things like customer demographics, weather, holidays, or competitor activity, so results may not capture every driver of demand. :contentReference[oaicite:6]{index=6}
