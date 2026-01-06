# DS-Football Analytics | Statistical Modeling in R

## 📌 Project Overview
This project focuses on the application of inferential statistics and predictive modeling to analyze football player performance. Using **R**, I explored the relationship between player roles, physical metrics, and goal-scoring efficiency, providing a robust statistical framework for decision-making in sports.

## 🔬 Statistical Methodology
- **Exploratory Data Analysis (EDA)**: Identification of distributions, outliers, and correlations in performance data.
- **Inferential Testing**:
  - **ANOVA**: To determine if playing position significantly impacts goal production.
  - **Tukey's HSD**: Post-hoc analysis to quantify specific differences between roles (e.g., Midfielders vs. Forwards).
- **Advanced Regression**:
  - Implementation of a **Zero-Inflated Negative Binomial (ZINB)** model. This approach was chosen to account for the high frequency of zero goals among defensive players and the overdispersion of the dataset.

## 📈 Key Findings
- Validated that playing position is the strongest predictor of goal count.
- Quantified the "Scoring Ratio" effect for hybrid roles (CC_DL).
- Achieved a high-performance predictive model validated through Train/Test splitting and RMSE metrics.

## 📂 Repository Structure
- `/notebooks`: R Markdown files and interactive HTML reports.
- `/data`: Cleaned datasets used for the analysis.
- `/docs`: Project requirements and case documentation.
- `/scripts`: R environment and history files.

## 🚀 Skills Demonstrated
- **Advanced R Programming (Tidyverse, pscl)**
- **Generalized Linear Models (GLM)**
- **Hypothesis Testing & Post-hoc Analysis**
- **Data Storytelling & Reporting**
