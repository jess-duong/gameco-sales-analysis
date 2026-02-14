# GameCo Video Game Sales Analysis

**Regional market analysis of 16,598 video game titles (1980-2016) to guide development budget allocation across global markets.**

[![View Presentation](https://img.shields.io/badge/Excel-Presentation-2B5329?style=flat-square&logo=microsoftpowerpoint&logoColor=white)](Presentation/GameCo_Sales_Analysis_Jessica_Duong.pdf)
[![View Data Dictionary](https://img.shields.io/badge/Docs-Data_Dictionary-6AAB73?style=flat-square&logo=readthedocs&logoColor=white)](Data/GameCo_Data_Dictionary.pdf)
[![View Appendix](https://img.shields.io/badge/Docs-Appendix-C4A84D?style=flat-square&logo=readthedocs&logoColor=white)](Data/GameCo_Appendix_Final.pdf)
---

## Project Background

GameCo is a video game company looking to use data to inform how it allocates development budgets for new games. The strategy team needed to understand which regions drive the strongest sales, what genres perform best in each market, and how competitive positioning varies globally. Without clear demand signals, budget decisions were being made on intuition rather than evidence.

This analysis examined historical sales data from VGChartz covering 16,598 video game titles across North America, Europe, Japan, and other regions from 1980 to 2016. Using pivot tables, market share trend analysis, and franchise-level aggregation, the project identified regional growth patterns, genre preferences, and competitive dynamics to produce a data-backed budget allocation framework.

## Data Structure

The dataset contains one record per game title with regional sales breakdowns (NA, EU, Japan, Other) measured in millions of physical units sold. Key metadata includes genre, platform, publisher, and release year. During analysis, calculated fields were added for regional market share percentages, year-over-year trends, publisher totals (using SUMIF), and franchise groupings (using wildcard pattern matching on game names). Data cleaning addressed publisher naming variations (e.g., consolidating "Sony Computer Entertainment" and "Sony"), character encoding issues in titles like Pokemon, and the exclusion of incomplete 2016 data and anomalous 2017/2020 records.

## Executive Summary

Europe has quietly overtaken North America as the largest video game market by share, genre preferences differ dramatically across regions, and franchise success is heavily localized. These findings point to a clear conclusion: a one-size-fits-all global strategy underperforms, and GameCo should allocate development budgets regionally based on demonstrated demand patterns.

**Top Findings:**

1. **Europe surpassed North America in market share by 2016 (37.7% vs. 31.9%).** North America's share declined steadily from a peak of 54.7% in 2002, while Europe grew from 26% to become the largest regional market. This shift means future investment priorities should weight Europe more heavily.

2. **Genre preferences vary significantly by region.** Shooter games skew heavily Western with 56% of sales from North America, while Role-Playing is the only genre where Japan leads all regions at 38% share. Sports titles split between NA (51%) and EU (28%) with minimal Japan presence.

3. **Top franchise performance is region-specific.** FIFA dominates Europe with 61% of its sales there, Call of Duty leads North America at 52%, and Pokemon over-indexes in Japan at 31%. This means content investment must be tailored to regional tastes, not averaged globally.

## Insights Deep Dive

### Europe's Growth Changes the Investment Equation

North America historically dominated global video game sales, holding over 50% market share through most of the 2000s. But starting around 2011, that dominance began eroding. Europe's share climbed steadily from 26% in 2000 to 37.7% in 2016, eventually surpassing North America's 31.9%. Japan remained relatively stable between 9-14%. This is not a one-year anomaly; it is a sustained multi-year trend that should reshape how GameCo prioritizes regional development and marketing budgets.

![Europe has become the largest growth engine, overtaking North America by 2016](Visualizations/gameco-findings.jpg)

### Genre Strategy Must Be Regionalized

Across the top five genres, North America and Europe share similar preferences for Action and Sports titles, but the similarities end there. Shooter games are overwhelmingly a Western phenomenon (56% NA, 30% EU, just 3.7% Japan). Meanwhile, Japan's gaming market looks fundamentally different, with Role-Playing games commanding 38% share compared to just 35% for NA and 20% for EU. Platform games also show a strong NA skew at 54%. These patterns mean a genre that performs well in one market may underperform in another, and budget allocation should reflect this reality.

![Western markets favor Action and Shooter while Japan strongly prefers RPGs](Visualizations/gameco-deliverables.jpg)

### Franchise Dominance Is Regional, Not Global

The top five franchises (Super Mario Bros, Wii, Call of Duty, Pokemon, FIFA) collectively drive massive sales, but each franchise wins in different markets. In North America, Call of Duty maintains consistent annual performance between 10-17M units, while FIFA barely registers. The opposite is true in Europe, where FIFA grew from 4M to 13M units annually between 2006-2014, eventually overtaking Call of Duty by 2012. In Japan, Pokemon and Mario dominate while Call of Duty and FIFA sell less than 1M units per year. This franchise-level regionalization reinforces that GameCo needs localized content strategies, not global ones.

![Revenue is franchise-driven with different titles winning by region](Visualizations/gameco-constraints.jpg)

## Recommendations

**Increase European investment to match its market leadership.** Europe is now the largest regional market by share and has shown consistent growth for over a decade. GameCo should increase development and marketing budgets for the EU market, with particular emphasis on Sports titles and localized content that aligns with European gaming culture.

**Align genre investment with regional demand patterns.** Action and Shooter titles should remain priorities for North America and Europe, where they command the strongest sales. For Japan, GameCo should increase RPG and Platform game investment, recognizing that this market has fundamentally different preferences from Western markets.

**Build region-specific franchise and release strategies.** Rather than launching titles uniformly worldwide, GameCo should time releases and marketing campaigns to regional demand cycles. Annual release franchises like Call of Duty work well in North America, while sports-driven titles should lead European campaigns. Japan requires dedicated localization and content tailored to RPG and platform audiences.

**Use regional share, not global averages, for budget allocation.** Global averages mask the significant regional differences revealed in this analysis. Budget allocation frameworks should weight each region's share and growth trajectory independently, with Europe receiving increased allocation proportional to its rising market position.

## Tools & Skills

| Tool | Use |
|------|-----|
| Excel | Data cleaning, pivot tables, calculated fields, statistical analysis |
| Pivot Tables | Regional aggregation by genre, year, platform, and publisher |
| Excel Charts | Comparative visualizations for market trends and franchise performance |

Analytical techniques: descriptive statistics, market share trend analysis, competitive benchmarking, franchise aggregation, regional segmentation.

## Deliverables

| Document | Description |
|----------|-------------|
| [Stakeholder Presentation](Presentation/) | Executive summary with visualizations and strategic recommendations |
| [Data Dictionary](Data/) | Variable definitions, calculated fields, and data quality notes |
| [Data Appendix](Data/) | Complete regional breakdowns, genre analysis, and franchise performance tables |
| [Excel Workbook](Visualizations/) | Charts and pivot tables supporting the analysis |

## Author

**Jess Duong** | Data Analyst  
[LinkedIn](https://www.linkedin.com/in/jess-duong/) | [Portfolio](https://jess-duong.github.io/) | duong.t.jess@gmail.com

---

*Data source: VGChartz Video Game Sales Database. Sales figures represent physical units sold for titles exceeding 10,000 units globally. This project was completed as part of the CareerFoundry Data Analytics program.*
