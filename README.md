# Experimental Design: Texting Efficiency Analysis

## Project Overview
This project investigates how different typing methods influence texting speed. We designed a **Randomized Complete Block Design (RCBD)** experiment to evaluate four "texting conditions" based on thumb usage (one vs. two) and phone orientation (vertical vs. horizontal).

## Methodology
* **Experimental Design:** Randomized Complete Block Design (RCBD) with 4 blocks (participants) and 4 treatments per block.
* **Data Collection:** Measured time (seconds) to type a standardized pangram ("the quick brown fox...") across randomized trials.
* **Tools Used:** R (Statistical Analysis), ANOVA, Boxplots.

## Key Findings
* Performed an **ANOVA** test, which resulted in a p-value of 0.113 for the Texting Condition factor.
* Validated model assumptions using **Shapiro-Wilk** (normality) and **Bartlett** (homogeneity of variances) tests.
* Visual analysis (Boxplots) suggested two-thumb horizontal typing was the fastest method, though the sample size (n=16) limited statistical significance.

## Files
* `texting_analysis.R.pdf`: The R code file used for data cleaning, ANOVA modeling, and generating diagnostic plots.
* `Final_Report.pdf`: The full technical report, including experimental setup and detailed conclusion.
