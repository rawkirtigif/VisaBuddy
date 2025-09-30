# VisaBuddy A/B Testing Analysis

User experience research project comparing checklist vs calendar interface designs for F-1 visa deadline management application.

## Project Overview

Conducted randomized controlled A/B test with 80 F-1 international students to determine optimal interface design for visa compliance tracking.

**Key Results:**
- Overall UX score: 4.46 vs 3.13 (+1.03 points, p<0.001)
- User recommendation rate: 80% vs 57.5% (+22.5%)
- Effect size: Cohen's d = 2.41 (very large)
- **Decision:** Implement checklist interface for MVP

## Methodology

- **Design:** Randomized controlled trial, balanced groups
- **Sample:** 80 F-1 students (40 per variant)
- **Metrics:** Ease of Use, Likely to Use, Clarity, Recommendation
- **Analysis:** Independent t-tests, chi-square, effect size calculations
- **Tools:** Python (scipy, pandas, matplotlib, seaborn)

## Variants Tested

### Variant A: Checklist View (Winner)
Task-based layout with all deadlines visible simultaneously, integrated progress tracking, direct completion checkboxes.

### Variant B: Calendar View  
Date-based calendar requiring navigation between dates to view deadline details.

## Key Findings

| Metric | Checklist | Calendar | Difference | p-value | Cohen's d |
|--------|-----------|----------|------------|---------|-----------|
| Ease of Use | 4.45 | 3.33 | +1.12 | <0.001 | 1.86 |
| Likely to Use | 4.33 | 3.03 | +1.30 | <0.001 | 1.87 |
| Clarity | 4.60 | 3.05 | +1.55 | <0.001 | 2.30 |
| Overall | 4.46 | 3.13 | +1.33 | <0.001 | 3.76 |

## Why Checklist Won

- **Mental Model Alignment:** Users conceptualize visa compliance as tasks, not dates
- **Cognitive Load Reduction:** All information visible simultaneously vs requiring navigation
- **Action Clarity:** Direct checkboxes provide clearer completion pathway
- **Progress Transparency:** Integrated tracking provides immediate feedback

## Repository Contents

- `/visualizations` - Statistical charts and analysis dashboards
- `/data` - Anonymized survey responses (n=80)
- `/code` - Python analysis scripts with statistical tests

## Statistical Methods

- Independent samples t-tests (Welch's correction)
- Chi-square test for categorical outcomes
- Cohen's d effect size calculations
- 95% confidence intervals for all estimates

## Business Impact

Research validated checklist interface for MVP development, demonstrating data-driven product decision making. Results showed not only statistical significance but large practical effect sizes, indicating substantial user preference.

## Skills Demonstrated

- A/B testing methodology and experimental design
- Statistical analysis and hypothesis testing
- Data visualization and communication
- Product research and UX evaluation
- Python programming for data analysis

## Contact

Kirti Rawat | MS Project Management | Northeastern University
