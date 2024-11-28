# T-Test and P-Value Analysis

**Overview**
This project demonstrates the use of T-Tests and P-Values in Python to analyze statistical differences between two groups. The code generates synthetic datasets to simulate experimental and control groups and evaluates whether observed differences are statistically significant.

**Key Concepts**
- T-Test: A statistical test used to determine if there is a significant difference between the means of two groups.
- P-Value: The probability that the observed results occurred by chance. A lower p-value (< 0.05) typically indicates statistical significance.

**Features**
1. Data Simulation:
  - Generates random datasets (Group A and Group B) with specified mean and standard deviation.
  - Supports scenarios with identical or differing group parameters.
2. T-Test Implementation:
  - Uses scipy.stats.ttest_ind to perform an independent two-sample t-test.
  - Compares datasets to determine statistical significance.
3. Insights from Results:
  - T-Statistic:
    - High absolute value indicates a significant difference.
    - Negative value indicates a reduction in the mean of the treatment group compared to the control group.
  - P-Value:
      - Low p-value indicates results are unlikely due to random chance.
  - Conclusions about the effects of changes between groups.
