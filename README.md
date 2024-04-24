# Project: Replication of Michael L. Anderson's "The Benefits of College Athletic Success: An Application of the Propensity Score Design"

## Overview
This project seeks to replicate and validate the findings of Michael L. Anderson's influential study on the causal relationship between college football success and various institutional outcomes such as donations, applications, enrollment, and academic performance. Anderson's work employs sophisticated statistical techniques to explore these dynamics, highlighting significant positive impacts of athletic success on institutional metrics. Our study aims to apply Python for data analysis to re-examine these findings.

## Data Files
The data files uploaded to this repository include:
- `college data.dta`
- `covers_data.dta`

### Data Tables
The data table files are in Stata format (.dta), detailing the processing steps and manipulations required for the analysis.

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
Using Python libraries such as Pandas, NumPy, and StatsModels, this study first focuses on replicating the analyses originally carried out in Stata in Python. Subsequently, machine learning algorithms including Lasso, Random Forest, and Gradient Boosting are employed to enhance the outcomes of the study, improving regression and propensity score estimation to observe their impact on the author's conclusions.

## Note
This replication study is conducted for educational purposes, aiming to apply and validate the methodologies used by Anderson in examining the impacts of college athletic success. It provides an opportunity for hands-on experience with causal inference techniques in observational data.

## Link to Colab notebook
[Link to Google Colab](https://colab.research.google.com/drive/1b0X3uAkiVyGJPw1SmWUoTwFphuU8opfU?authuser=2#scrollTo=sVRi7dJbp73Y)


## Link to Paper and Data Files
For reference to the original study and access to the datasets used in this replication, please visit [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/ASXOBS).

## Link to Presentation Files
https://docs.google.com/presentation/d/1izyNkTTR634ye9lQSorWV7mgFgMZGVNq/edit?usp=sharing&ouid=106975341459544501752&rtpof=true&sd=true

