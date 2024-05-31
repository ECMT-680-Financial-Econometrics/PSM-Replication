# Project: Replication of Michael L. Anderson's "The Benefits of College Athletic Success: An Application of the Propensity Score Design"

## Overview
This project aims to replicate and validate Michael L. Anderson's influential study on the causal relationship between college football success and institutional outcomes like donations, applications, enrollment, and academic performance. Anderson's research employs advanced statistical methods, demonstrating substantial positive effects of athletic success on institutional metrics. While Anderson's study was conducted using STATA, this project intends to re-examine these findings using Python for data analysis.

## Data Files
While this project utilizes a pre-prepared dataset containing all necessary variables, the raw data is also provided for reference.
The data table files are in Stata format (.dta), and they include:
- `college data.dta`
- `covers_data.dta`

### College Data Summary
The "College Data" dataset covers various aspects of colleges and universities, including:
- **Institutional Information**: Names, cities, states, and control type (public/private).
- **Admissions Data**: Application, acceptance, and enrollment numbers by gender, along with SAT and ACT score ranges.
- **Donations and Financials**: Details on alumni donations, including rates and amounts, as well as donations for athletics and other areas.
- **Academic Metrics**: US News scores and rankings, academic reputation scores, and percentages of students from top high school percentiles.
- **Demographic Information**: Racial/ethnic composition of the student body.

### Covers Data Summary
The "Covers Data" dataset focuses on college football games, particularly from a betting perspective, and includes:
- **Game Details**: Dates, teams involved, and the scores.
- **Betting Information**: Bookmaker lines (spreads), over/under scores, and the actual spread between teams' scores.
- **Outcomes**: Whether the team won or lost, and if there was a tie.

## Python Analysis
Using Python libraries such as Pandas, NumPy, and StatsModels, this study initially replicates the analyses originally conducted in Stata.
Following this, machine learning algorithms like ridge regression and bootstrapping are employed to augment the workflow and evaluate their impact on the author's conclusions.
The results of the Standardized Treatment Effects (STE) presented in Table 2 and Table 3 serve as the benchmark for comparison.

## Note
This replication study is conducted for educational purposes, aiming to apply and validate the methodologies used by Anderson in examining the impacts of college athletic success.
It provides an opportunity for hands-on experience with causal inference techniques in observational data.

## Link to Paper and Data Files
For reference to the original study and access to the datasets used in this replication, please visit [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/ASXOBS).
