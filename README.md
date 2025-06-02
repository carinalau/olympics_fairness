# Fairness in the Olympics: A Statistical Analysis of Medal Distributions and Judging Bias

This project examines questions of fairness in Olympic competition, including how geopolitical influence, structural advantages, and judging practices may affect medal outcomes. The analysis was conducted as part of **ORIE 3120: Practical Tools for Operations Research, Machine Learning and Data Science** at Cornell University and reflects a comprehensive statistical investigation into over a century of Olympic data. It received a grade of 79/85.

---

## Project Overview

**Central Questions:**
- Are countries earning a fair share of gold medals relative to their total medal count?
- Does judging bias exist in subjective sports like gymnastics?
- Are the Summer and Winter Olympics equally fair across countries?
- Which Olympic events are most open to international competition?

**Dataset:**  
A cleaned and curated dataset spanning Olympic athlete participation from **1896 to 2016**, covering over **250,000 athlete-event entries**. Variables include age, nationality, sport, medal outcome, and event type.

---

## Methodology

- **Linear Regression** to evaluate gold medal “fair share” and assess judging bias in subjective vs. objective sports.
- **Residual Assumption Checks** including:
  - Homoscedasticity (constant variance)
  - Independence
  - Normality
- **Monte Carlo Simulation** to compare actual medal distributions to those expected under uniform randomness.
- **K-Means Clustering** to identify national performance archetypes in Summer vs. Winter Olympics.
- **One-Tailed Hypothesis Testing** to quantify fairness across individual Olympic events.

---

## Key Findings

- The **United States** consistently overperforms in converting total medals to golds, suggesting structural or investment-based advantages.
- **Soviet Union and East Germany** show evidence of potential judging bias in gymnastics, unlike the U.S. or China.
- **Seasonal clustering** reveals clear dominance profiles (e.g., Winter-heavy, Summer-heavy, Balanced), often tied to geographic or economic factors.
- Several events (e.g., **Men’s Football**) are more open than expected, while others (e.g., **Men’s Athletics**) show concentration of winners, likely due to resource disparities.

---

## Tools and Libraries

- `Python` - (core programming language)
- `NumPy`, `Pandas` - Data cleaning and analysis
- `Matplotlib`, `Seaborn` - Data visualization
- `SciPy`, `statsmodels` - Regression and statistical tests
- `scikit-learn` - K-Means clustering

---

## Credits

This project was completed by:

- **Carina Lau**
- **Skylar Weirens**  
- **David Valarezo**  
- **Anna Geng**  

ORIE 3120: Practical Tools for Operations Research, Machine Learning and Data Science
