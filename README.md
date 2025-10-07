# Indie Game Conversion Analysis

## Overview
An exploratory analysis of how indie game genres differ in their wishlist-to-purchase conversion rates on Steam.  
The project focuses on identifying temporal patterns and genre differences using Python and Plotly.

## Objectives
- Calculate and visualize conversion rates across different release stages and genres.
- Highlight the top 5 genres and analyze their yearly conversion trends.
- Present insights using interactive visualizations.

## Data
- source: Popular Video Games 1980 - 2023 (Excel, ~3MB)
- Variables include: genre, release year, wishlist count, play count, comment count, etc.
- Raw data excluded from GitHub due to file size.

## Key Findings
- User journey: Conversion rates across different stages do not follow a hierarchical funnel with progressive attrition, suggesting diverse user behaviors rather than a uniform progression.
- Genre differences: Conversion rates differ significantly across genres (ANOVA F = 5.357, p < 0.001), with Visual Novel and Adventure games exhibiting higher consistency.
- Temporal trend: A decreasing trend with reduced variance is observed in the conversion rates of the top 5 genres over time. Further testing confirms a structural breakpoint around 2015 (T = 6.216, p < 0.001) and a significant decline in variance across all genres (r = –0.647, p = 0.031).
![Conversion by Stage](outputs/figures/static/Conversion_by_Stage.png)
![Conversion by Genre](outputs/figures/static/Conversion_by_Genre.png)
![Conversion Trends of Top 5 Genres](outputs/figures/static/Conversion_Trends_of_Top5_Genres.png)
