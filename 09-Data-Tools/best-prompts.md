# Best Prompts for Data AI

10 ready-to-use prompts for analysis, reporting, and data storytelling.

## 1. Data Health Audit [Beginner]
**Use case:** Check data quality before analysis.

```text
You are a data quality analyst.
Dataset description: [DESCRIBE]
Columns: [LIST]
Sample rows:
[PASTE SAMPLE]

Run a data health audit:
- Missing values
- Duplicates
- Outliers
- Type mismatches
- Potential leakage or bias issues

Return a prioritized cleanup plan.
```

## 2. Exploratory Analysis Copilot [Intermediate]
**Use case:** Get fast EDA insights from CSV data.

```text
Act as a senior data analyst.
Business context: [CONTEXT]
Dataset fields: [FIELDS]
Primary question: [QUESTION]

Provide:
- EDA plan
- Key descriptive stats
- Segment comparisons
- Candidate visualizations
- First-pass insights with confidence notes
```

## 3. KPI Dashboard Blueprint [Intermediate]
**Use case:** Plan a useful analytics dashboard.

```text
You are a BI consultant.
Business goal: [GOAL]
Users of dashboard: [ROLES]
Data sources: [SOURCES]

Design:
- KPI definitions
- Visual chart suggestions
- Filter and drilldown logic
- Alert thresholds
- Dashboard layout wireframe in text
```

## 4. SQL Insight Generator [Beginner]
**Use case:** Generate SQL for common business questions.

```text
Act as an analytics engineer.
Database schema:
[PASTE TABLES]
Business questions:
[PASTE QUESTIONS]

For each question provide:
- SQL query
- What the query returns
- Assumptions
- Potential caveats
```

## 5. Cohort Analysis Prompt [Advanced]
**Use case:** Understand retention and behavior patterns.

```text
You are a product analytics specialist.
Event data structure:
[PASTE]
Cohort definition: [SIGNUP DATE / FIRST PURCHASE / etc]
Metric focus: [RETENTION/REVENUE/ENGAGEMENT]

Create:
- Cohort analysis methodology
- Required transformations
- Query/pseudocode steps
- Interpretation guide
- Common pitfalls to avoid
```

## 6. Forecasting Scenario Builder [Advanced]
**Use case:** Build realistic forward-looking projections.

```text
Act as a forecasting analyst.
Historical data summary:
[PASTE]
Forecast horizon: [TIMEFRAME]
Business constraints: [CONSTRAINTS]

Generate:
- Baseline forecast
- Optimistic and conservative scenarios
- Key assumptions table
- Risk drivers
- Monitoring triggers for reforecasting
```

## 7. Executive Summary from Analysis [Intermediate]
**Use case:** Translate technical findings for leadership.

```text
You are a data storyteller for executives.
Analysis findings:
[PASTE]
Audience: [C-SUITE / MANAGERS]

Write:
- 5-bullet executive summary
- Business impact statement
- Recommended actions (prioritized)
- Risks and confidence level
- One-slide narrative draft
```

## 8. A/B Test Evaluator [Advanced]
**Use case:** Evaluate experiment results correctly.

```text
Act as an experimentation analyst.
Experiment setup:
[PASTE]
Results summary:
[PASTE]
Metric definitions:
[PASTE]

Return:
- Statistical interpretation
- Practical significance
- Segment-level effects
- Potential confounders
- Decision recommendation (ship/iterate/stop)
```

## 9. Python Notebook Starter [Beginner]
**Use case:** Generate a clean analysis notebook structure.

```text
You are a Python data mentor.
Analysis objective: [OBJECTIVE]
Dataset format: [CSV/JSON/PARQUET]

Produce starter notebook code sections:
- Imports and setup
- Load and validate data
- EDA functions
- Visualization section
- Insight summary template

Use pandas + matplotlib/seaborn.
```

## 10. Insight QA and Bias Check [Advanced]
**Use case:** Stress-test conclusions before sharing.

```text
You are a critical data reviewer.
Conclusions drafted:
[PASTE CONCLUSIONS]
Data limitations:
[PASTE]

Audit for:
- Overclaiming
- Survivorship bias
- Selection bias
- Metric misuse
- Missing alternative explanations

Return a safer, evidence-grounded conclusion set.
```
