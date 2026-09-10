# Data Analyst 

### Education 
Data Analysis / TripleTen 
Masters in Management

### Work Experience 

### Projects

BootCamp at TripleTen: 
- Urban Mobility & Economic Productivity Analysis (LATAM & Global Cities)

Overview
An end-to-end data processing and exploratory analysis project investigating the relationship between urban traffic congestion (TomTom Traffic Index) and economic productivity metrics (OECD Cities GDP per capita, unemployment, and population). Built to support infrastructure investment decisions at the American Development Bank (IDB).

Key Features & Technical Workflow

1. Data Cleaning & Standardization: Cleaned, formatted, and standardized mismatched schemas across multiple real-world datasets using pandas and numpy.
2. Feature Engineering & Aggregation: Transformed high-frequency datetime traffic logs to compute annual city-level mobility indicators (delays, congestion length, live travel times) filtered for 2024.
3. Dataset Unification: Merged disparate spatial and economic datasets into a single analytics-ready table.
4. Exploratory Data Analysis (EDA): Visualized relationships between mobility bottlenecks and urban economic outputs using seaborn and matplotlib.

Tech Stack
Language: Python
Libraries: Pandas, NumPy, Seaborn, Matplotlib
Environment: Jupyter Notebook

- MercadoLibre User Journey & Cohort Retention Analysis

Overview
A SQL-driven data analysis project focused on measuring user retention, cohort behavior, and user journeys for MercadoLibre. The project tracks post-signup activity to evaluate drop-off rates across key engagement milestones (D7, D14, D21, and D28) and benchmark performance across different countries and registration periods.

Key Features & Technical Workflow

1. Cohort Segmentation: Built CTEs using DATE_TRUNC and MIN() to group users into monthly registration cohorts (YYYY-MM) based on their initial sign-up date.
2. Retention Milestone Calculation: Designed conditional aggregation queries using COUNT(DISTINCT CASE WHEN ...) to compute accumulated active user retention at 7, 14, 21, and 28 days post-signup.
3. Safe Percentage & Metric Normalization: Applied NULLIF() to prevent division-by-zero errors and scaled retention metrics to standardized percentage rates rounded for executive reporting.
4. Geographic & Temporal Benchmarking: Grouped and filtered behavioral data across regional markets and date ranges (2025-01-01 to 2025-08-31) to highlight activation decay trends.

Tech Stack
Language: SQL (PostgreSQL / ANSI SQL dialect)
Key Techniques: Common Table Expressions (CTEs), Aggregation & Conditional Case Statements, Date/Time Functions, Multi-table Joins
