**📊 Netflix Content Strategy & Growth Analysis Using SQL**


**📁 Dataset Information**

Source: Netflix Movies & TV Shows dataset

Total Records: 8,800+ titles

The dataset contains mixed data formats (e.g., duration stored as text, date stored as varchar), requiring data cleaning and transformation before analysis.

🛠 Project Workflow

**1️⃣ Data Cleaning & Preparation:**

- Converted date_added from VARCHAR to DATE format.

- Extracted numeric duration values into a new column (duration_int).

- Separated and analyzed Movies and TV Shows independently.

- Performed data quality checks on null values.

**2️⃣ Exploratory Data Analysis:**

- Content distribution (Movies vs TV Shows)

- Movie duration analysis (min, max, average)

- TV Show season distribution

- Top longest-running TV shows (Window functions)

- Country-wise content distribution

- Year-wise content production trend

- Year-over-Year (YoY) growth analysis

- Platform onboarding trend (based on added year)

- Movies vs TV Shows growth by year added


**📈 Key Insights:**

- Movies dominate the platform, contributing ~70% of total content.

- Most TV Shows have 1–2 seasons; long-running shows are rare.

- Major content production growth occurred between 2015–2018.

- Peak production year: 2018.

- Platform onboarding peaked in 2019, indicating aggressive expansion.

- Growth phase (2016–2019) was heavily movie-driven.

- Post-2019 decline suggests slowdown or strategic content optimization.


**🎯 Business Understanding:**

The analysis reveals that Netflix experienced rapid expansion between 2015–2019 through aggressive content acquisition and movie-heavy additions, followed by a noticeable slowdown in recent years.


**This project demonstrates:**

Data cleaning skills

SQL querying (aggregations, window functions, CTEs)

Trend analysis

Business-oriented interpretation of data
