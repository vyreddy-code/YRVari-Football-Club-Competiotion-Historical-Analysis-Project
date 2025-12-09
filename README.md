# YRVari-Football-Club-Competiotion-Historical-Analysis-Project

Beyond-the-Pitch---Quantifying-Success-in-Modern-Football

A data-driven historical analysis of global football clubs using SQL and Tabeau This project builds a unified club-by-season dataset by integrating player valuations, match results, squad composition, and disciplinary records. Using this dataset, the analysis explores how various factors influence club performance across leagues and seasons.

The workflow includes data cleaning, ncludes end-to-end data preparation (views, transformations, joins), exploratory analysis, correlation studies, efficiency comparisons, and visual summaries.

Motivation
Understanding the dynamics of club success is critical. This analysis explores factors such as valuation, age structure, and positional roles while identifying efficient clubs and continental trends.

Football performance is often explained narratively (talent, coaching, money).

But real drivers are hidden in massive, multi-table datasets.

Modern clubs spend billions; success requires evidence-based squad building.

We unify financial strength + squad structure + discipline to see what actually predicts winning.

Problem Definition
This project aims to uncover the key drivers of football club success by analyzing how financial power, squad structure, and on-field discipline shape season-level performance. By integrating global match, player, and valuation data through BigQuery and SQL, we aim to explain why some clubs consistently outperform others.

What truly drives football club success over a season?

Individual success and its comparision to team success.

Quantify link between squad market value and win percentage.

Understand how age structure and positional contribution shape outcomes.

Evaluate continental player valuation growth trends.

Identify clubs that overperform financially (“efficient clubs”).

Objectives
The project focuses on three core pillars:

1. Financial Strength
2. Squad Composition
3. Discipline & Competition Context


Major Findings
1. Financial Strength Matters—but Weakly
- Overall correlation between squad value and win percentage ≈ 0.23
- High-value clubs typically win more, but variance is large
- Several clubs outperform their spending dramatically (win_pct ≈ 0.85 with < €5M squads)

Insight: Financial power offers an advantage, but tactical efficiency and development can rival spending.

2. Squad Composition Drives Tactical Outcomes
- Minutes-weighted age around 23–31 correlates with stronger results
- U23-heavy squads underperform unless minutes are well balanced
- When forwards contribute fewer goals, win percentages flatten even if overall goal differences remain positive

Insight: Balanced positional output—particularly from forwards—is more impactful than average age alone.

3. Discipline Influences Club Outcomes
- High yellow/red card counts correlate with lower win rates
- Aggressive teams often face momentum loss due to red cards
- League-level averages show significant variation in competitiveness and officiating intensity

Insight: Clubs that maintain discipline tend to outperform those with high card accumulation.

Visualization Dashboard
Tableau Story Link:
https://public.tableau.com/app/profile/gurveen.rekhi/viz/A10Assignment2/Story1?publish=yes

