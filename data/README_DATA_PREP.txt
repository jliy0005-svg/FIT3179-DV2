DV2 CHART-READY DATA PACK

You do NOT need to manually edit the original BITRE or ABS files.

Files:
- city_summary_chart_ready.csv
  Charts 1, 2, 4, 5; also joins to the choropleth geometry for Chart 3.
  Latitude/Longitude are included.

- mode_share_2025.csv
  Chart 6 heatmap. Missing/not-applicable modes remain blank and retain Data_Status.

- national_mode_share_2025.csv
  Chart 7 mode-share visual.

- city_totals_long.csv
  Chart 8 overview/detail timeline.

- city_rankings.csv
  Chart 9 bump/ranking chart. Rank 1 = highest patronage for that financial year.

- covid_waterfall.csv
  Chart 10. National total patronage from 2018-19 onward plus year-to-year changes.

- recovery_2025.csv
  Chart 11. 100 = 2018-19 patronage level.

- DV2_chart_ready_data.xlsx
  Audit/reference workbook including the original cleaned datasets, coordinate table,
  and a Chart_Data_Guide sheet.

IMPORTANT:
- BITRE 'na' and '..' have NOT been converted to zero.
- The ABS 2025 population is used only for the 2024-25 per-resident comparison.
- Keep the original source files as evidence/provenance.
- For Chart 3, a capital-city boundary TopoJSON is still required; that will be prepared
  when we reach the choropleth step.
