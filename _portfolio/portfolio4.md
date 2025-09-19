---
title: Show&Well Provider Directory
subtitle: (Python, SQL, BigQuery, Google Cloud, Tableau)
alt: Click the image below to be redirected to the dashboard

caption:
  title: Show&Well – Ratings-Backed Provider Directory
  subtitle: (Python, SQL, BigQuery, Google Cloud, Tableau) 
  thumbnail: assets/img/portfolio/rectandwell.png
---
[![Show&WellDashboard](assets/img/portfolio/well.jpeg)](https://public.tableau.com/app/profile/julian.van.beusekom/viz/SAWProPipelineVis/ShowAndWellProPipeline?publish=yes)

End-to-end data product on Google Cloud: a Python scraper hits the Google Places API (New) to fetch ratings & details, 
lands them to GCS → BigQuery (bronze ➜ silver ➜ gold views), and powers a Tableau dashboard (map with county overlay, 
category summary, top by reviews).

Key pieces: reproducible run_all.sh, typed views, geocoding + distance calc (ST_DISTANCE), 
and a tiering model (Gold/Silver/Bronze). Exports a single CSV for easy BI ingestion.

GitHub for the project: [View Here](https://github.com/JulianVB3102/ShowAndWellPipeline)

{:.list-inline}
- Date: September 2025
- Client: Show & Well
- Category: Data Engineering · Analytics Engineering · BI
