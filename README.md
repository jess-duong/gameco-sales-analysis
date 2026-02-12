# GameCo Video Game Sales Analysis

**Regional market analysis examining video game sales trends (1980-2016) to inform strategic budget allocation for new game development.**

[![View Presentation](https://img.shields.io/badge/View-Presentation-blue)](Presentation/)
[![View Data Dictionary](https://img.shields.io/badge/View-Data_Dictionary-green)](Data/)

## Project Overview

GameCo, a video game company, needed data-driven guidance for allocating development budgets across different markets and genres. This analysis examined 16,598 video game titles spanning 1980-2016 to identify regional market patterns, genre preferences, and competitive positioning.

### Business Questions
- Which regions and genres drive the strongest sales performance?
- How has regional market composition shifted over time?
- What genre preferences exist across different geographic markets?
- Which competitors dominate specific regional markets?

### Key Findings
- **Europe surpassed North America in market share by 2016** (37.7% vs 31.9%)
- **Genre preferences vary significantly by region**: Western markets favor Action/Shooter titles while Japan shows strong RPG preference
- **Top 5 franchises demonstrate regional specialization**: FIFA dominates Europe (61% share), Call of Duty leads North America (52%), Pokémon over-indexes in Japan (31%)

## Tools & Techniques

**Tools**: Excel, Pivot Tables, Statistical Analysis  
**Skills**: Descriptive statistics, data cleaning, market segmentation, data visualization, stakeholder presentation

### Analytical Approach
- Cleaned and standardized 16,598 records (handled missing values, removed duplicates, corrected encoding issues)
- Calculated regional market share percentages and year-over-year trends
- Created calculated fields for franchise groupings and competitive analysis
- Built pivot tables to aggregate sales by region, genre, platform, and publisher
- Designed comparative visualizations to identify market patterns

## Repository Contents
```
├── Data/                       # Data dictionary and appendix
├── Visualizations/             # Excel charts and graphs  
├── Scripts/                    # Documentation of Excel formulas
├── Presentation/               # Stakeholder presentation (PDF)
└── README.md                   # Project documentation
```

## 🎯 Strategic Recommendations

### Regional Strategy
- **Europe**: Increase investment in Sports titles and localized marketing (fastest-growing market)
- **North America**: Continue emphasis on Action and Shooter genres with frequent release cycles
- **Japan**: Focus on Role-Playing game localization and platform titles (unique market preferences)

### Content Development
- Prioritize genres with demonstrated strong regional demand
- Consider regional co-development for culturally specific content
- Monitor platform adoption trends to optimize distribution partnerships

### Marketing Approach
- Implement region-specific campaigns rather than uniform global strategy
- Track emerging markets for early growth signals
- Adjust inventory and localization timelines based on regional sales patterns

## Data Scope & Limitations

**Dataset**: VGChartz Video Game Sales  
**Records**: 16,598 games  
**Time Period**: 1980-2016 (2016 data incomplete)  
**Geographic Coverage**: North America, Europe, Japan, Other regions  
**Sales Metric**: Physical units sold (millions)

### Limitations
- **Physical sales only**: Excludes digital downloads and mobile gaming (increasingly significant after 2010)
- **Incomplete 2016 data**: 70.9M units vs 264.4M in 2015 suggests partial year
- **Publisher naming variations**: Required consolidation (e.g., "Sony Computer Entertainment" vs "Sony")
- **Franchise identification**: Pattern matching may not capture all related titles

## Documentation

- **[Data Dictionary](Data/)**: Variable definitions, calculated fields, and data quality notes
- **[Data Appendix](Data/)**: Complete regional breakdowns, genre analysis, and franchise performance tables
- **[Stakeholder Presentation](Presentation/)**: Executive summary with visualizations and strategic recommendations

## Project Context

This project was completed as part of CareerFoundry's Data Analytics program, demonstrating proficiency in Excel-based analysis, market research, and business intelligence reporting. The analysis emphasizes translating data patterns into actionable business strategy for stakeholder decision-making.

### Development Notes
- Excel formulas and pivot table configurations documented in [Scripts/](Scripts/) folder
- All visualizations created using Excel's native charting capabilities
- Analysis focuses on completed historical data; real-world application would require validation with current market conditions

## Author

**Jess Duong**  
Data Analyst | [LinkedIn](https://www.linkedin.com/in/jess-duong/) | [Portfolio](https://jess-duong.github.io/) | duong.t.jess@gmail.com

---

*For questions about methodology or to discuss this analysis, please reach out via [LinkedIn](https://linkedin.com/in/jessica-duong-35690847/) or open an issue in this repository.*
