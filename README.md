# A/B Test Analysis for E-commerce Funnel Optimization

## Project Overview

This project analyzes the results of an A/B test conducted on an e-commerce platform to evaluate whether a new funnel experience (Group B) improves user conversion compared to the current version (Group A).

The analysis includes data cleaning, exploratory data analysis, funnel evaluation, experiment validation, and statistical hypothesis testing.

---

## Business Objective

Determine if the new product funnel increases user progression and final purchases enough to justify implementation.

---

## Tools & Libraries

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Statsmodels  
- Jupyter Notebook  

---

## Project Workflow

### 1. Data Cleaning & Validation
- Checked duplicates and structure consistency
- Converted date columns
- Validated experiment timeline
- Verified dataset integrity

### 2. Exploratory Data Analysis
- User distribution by A/B group
- Region and device segmentation
- Event activity behavior
- User engagement patterns

### 3. Funnel Analysis
Analyzed the following stages:

**product_page → product_cart → purchase**

Compared funnel progression between Group A and Group B.

### 4. Experiment Quality Checks
- No marketing campaign interference detected
- Stable daily traffic
- No abnormal event spikes
- No invalid event timestamps

### 5. Statistical Testing
Used two-proportion Z-tests to compare conversion rates between groups.

---

## Key Visualizations

### Funnel Conversion Comparison

![Funnel Comparison](images/funnel_comparison.png)

### Conversion Rates by Group

![Conversion Rates](images/conversion_rates.png)

### Daily Event Activity

![Daily Activity](images/daily_activity.png)

### Events per User Distribution

![User Activity](images/user_event_distribution.png)

---

## Final Results

- Group B improved one intermediate step (**product_page → product_cart**)
- No statistically significant increase in final purchases
- Overall business impact is not meaningful

### Recommendation

**Do not implement Group B yet.**  
The new version does not improve final conversion enough to replace the current experience.

---

## Repository Structure

```text
AB_Test_Analysis/
│── AB_Test_Project.ipynb
│── README.md
│── requirements.txt
│── data/
│── images/
```

## Skills Demonstrated
Data Cleaning
Exploratory Data Analysis
Funnel Metrics
A/B Testing
Hypothesis Testing
Business Recommendations
Data Visualization


### Author
Jorge Moncisvais
Data Analyst | Reporting, Operations & Business Insights