# ODI-Cricket-Data-Analysis-PowerBI-Dashboard
The objective of the ePSN Cricket Data Analysis Power BI dashboard is to provide a centralized, interactive, and visually intuitive platform that converts cricket data into actionable insights for analysts, cricket enthusiasts, and decision-makers.


📊 Problem Statement
EPSN – ODI Cricket Data Analysis using Power BI

One Day International (ODI) cricket generates high-volume, multi-entity statistical data across batting, bowling, and fielding dimensions. The raw dataset consists of match-level and player-level records spanning multiple years, containing performance indicators such as runs, strike rate, overs, wickets, economy, catches, dismissals, innings data, and match outcomes.

However, the dataset lacks:

A normalized analytical structure for performance benchmarking

KPI standardization across batting, bowling, and fielding

Dynamic filtering for player-wise and time-based analysis

Multi-dimensional drill-down capabilities

Optimized aggregation logic for advanced cricket metrics

🎯 Core Technical Challenge

Design and implement a scalable Business Intelligence solution in Power BI that transforms raw ODI match data into a structured analytical model capable of delivering interactive, player-centric performance insights.

🏗 Technical Objectives
1️⃣ Data Engineering & Transformation

Perform ETL using Power Query

Clean inconsistent player records and match spans

Standardize statistical calculations (runs, overs, innings, dismissals)

Handle missing/null values and data granularity issues

Create derived columns for performance calculations

2️⃣ Data Modeling Architecture

Implement a Star Schema Model

Fact Table: ODI Match Performance Data

Dimension Tables: Player, Match, Date, Team, Role

Establish one-to-many relationships

Optimize model performance using:

Proper cardinality settings

Removal of unnecessary columns

Measures instead of calculated columns

Data type optimization

3️⃣ Advanced DAX KPI Implementation

Develop dynamic DAX measures for:

🏏 Batting KPIs

Batting Average = Total Runs / (Innings – Not Outs)

Strike Rate = (Runs / Balls) × 100

Highest Score

4s and 6s Distribution

Half-Centuries and Centuries

Span Analysis (Career Duration)

🎯 Bowling KPIs

Bowling Average = Runs Conceded / Wickets

Economy Rate = Runs Conceded / Overs

Bowling Strike Rate = Balls Bowled / Wickets

Best Bowling Figures (e.g., 3/34)

Maiden Overs Analysis

5-Wicket Hauls

🧤 Fielding KPIs

Total Catches

Catches as Wicketkeeper vs Fielder

Stumpings

Dismissals per Innings Ratio

Match-wise Dismissal Impact

4️⃣ Interactive Analytical Capabilities

Player-level dynamic slicer filtering

Page-wise segmentation:

Batting Analysis

Bowling Analysis

Fielding Analysis

Cross-filtering between visuals

Drill-through from summary to detailed stats

Time-based performance trend evaluation

KPI card visualization for quick performance benchmarking

5️⃣ Performance Optimization

Efficient DAX measure design

Avoiding row-context heavy calculations

Aggregation optimization

Model size reduction techniques

Ensuring responsive dashboard performance

📌 Business & Analytical Outcome

The EPSN ODI Data Analysis Dashboard provides:

360° player performance evaluation

Role-based statistical comparison (Batsman, Bowler, All-rounder, WK)

Career span analytics

Match impact assessment

Data-driven performance benchmarking

The solution transforms raw ODI cricket datasets into a structured analytical framework that supports advanced statistical analysis, strategic evaluation, and interactive performance insights through optimized BI architecture.


💡 Advanced enhancements you can mention to make this project stand out even more

Just tell me which one you want 🚀
