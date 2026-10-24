# Chelsea vs Tottenham — Power BI Pre-Match Analysis

## Overview

This project is a football analytics dashboard built in **Power BI** to compare Chelsea and Tottenham ahead of their Premier League fixture on **24 October 2026**.

The report brings together recent team form, goals scored and conceded, points earned, and previous head-to-head meetings. It is a descriptive analysis of historical results, not a predictive model.

## Project objectives

- Compare Chelsea and Tottenham's recent results.
- Summarise wins, points, goals scored, and goals conceded across each team's selected recent matches.
- Review the teams' previous head-to-head meetings.
- Practise data preparation with Power Query and visual reporting in Power BI.

## Data source

Historical match results were sourced from [Football-Data.co.uk](https://football-data.co.uk/).

The analysis uses CSV data for these Premier League seasons:

- 2023/24
- 2024/25
- 2025/26
- 2026/27 (results available at the time this snapshot was prepared)

**Data redistribution note:** The source CSV files are not included in this repository while the applicable redistribution terms are being checked. Please obtain the data from the source and review its current terms before reusing or redistributing it.

## Data preparation

The data was prepared in **Power Query**. The main steps included:

1. Importing the season CSV files.
2. Adding a season label to identify each file's season.
3. Appending the seasons into a combined match-results table.
4. Creating calculated fields for total goals, match outcome points, goal difference, and head-to-head identification.
5. Creating filtered tables for Chelsea's recent matches, Tottenham's recent matches, and their head-to-head meetings.

## Dashboard features

- **Team summary cards:** wins, total points, goals scored, and goals conceded.
- **Recent-form tables:** selected recent matches for Chelsea and Tottenham, including goals for, goals against, result, and points.
- **Head-to-head chart:** goal comparisons across the six meetings shown in the report.
- **Result formatting:** colour cues for wins, draws, and losses.

## Key findings shown in this snapshot

Based on the selected recent-match tables in the dashboard:

| Metric | Chelsea | Tottenham |
|---|---:|---:|
| Wins | 2 | 1 |
| Points | 7 | 6 |
| Goals scored | 10 | 6 |
| Goals conceded | 8 | 5 |

Chelsea earned one more point and scored more goals across the selected matches. Tottenham conceded fewer goals and recorded more draws. These figures describe the selected results; they do not establish which team would win the fixture.

The head-to-head visual compares the six meetings included in the dashboard.

## Tools and skills demonstrated

- Microsoft Power BI
- Power Query
- CSV data import and transformation
- Appending datasets from multiple seasons
- Calculated columns and match-result logic
- Dashboard layout, tables, cards, and charts
- Basic football performance analysis

## Files

The repository is intended to contain:

- `Chelsea_Tottenham_Analysis.pbix` — the Power BI report
- `Chelsea_Tottenham_PreMatch.png` — a screenshot of the report
- `README.md` — this project overview

The original source CSV files are intentionally omitted for now pending confirmation of redistribution terms.

## Limitations

- This is a descriptive dashboard, not a machine-learning or statistical prediction model.
- No win probabilities or forecast scores are produced.
- The report reflects the data and selected match records available when the snapshot was prepared on **24 October 2026**.
- The recent-match summaries depend on the records selected in the Power BI report; check the report's dates and filters before drawing further conclusions.

## Conclusion

This project demonstrates an introductory football analytics workflow: sourcing historical results, combining and transforming data in Power Query, and presenting team and head-to-head comparisons in Power BI.

It is intended as a portfolio project showing data preparation, visualisation, and clear communication of descriptive findings.
