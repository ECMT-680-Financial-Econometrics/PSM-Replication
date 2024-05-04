# Project: Replication of Michael L. Anderson's "The Benefits of College Athletic Success: An Application of the Propensity Score Design"

## Overview
This project aims to replicate and validate Michael L. Anderson's influential study on the causal relationship between college football success and institutional outcomes like donations, applications, enrollment, and academic performance. Anderson's research employs advanced statistical methods, demonstrating substantial positive effects of athletic success on institutional metrics. While Anderson's study was conducted using STATA, this project intends to re-examine these findings using Python for data analysis.

## Data Files
The data files uploaded to this repository include:
- `college data.dta`
- `covers_data.dta`

### Data Tables
The data table files are in Stata format (.dta).

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

### Generate Tables
The file "generate_tables.do" was used to compare code analyis. The files will be in the Replication notebook in the first text chunk.

## Python Analysis
Using Python libraries such as Pandas, NumPy, and StatsModels, this study first focuses on replicating the analyses originally carried out in Stata in Python.
Subsequently, machine learning algorithms like ridge regression is employed to enhance the outcomes of the study, improving regression and propensity score estimation to observe their impact on the author's conclusions.
The replicaation includes the STE Table 2 and STE Table 3.

## Note
This replication study is conducted for educational purposes, aiming to apply and validate the methodologies used by Anderson in examining the impacts of college athletic success.
It provides an opportunity for hands-on experience with causal inference techniques in observational data.

## Link to Colab Reaplication notebook
[Link to Google Colab]([https://colab.research.google.com/drive/1b0X3uAkiVyGJPw1SmWUoTwFphuU8opfU?authuser=2#scrollTo=sVRi7dJbp73Y](https://colab.research.google.com/drive/1tKJ6iimlCVpmPOPW0nMZ6iHfzbTZu6tP?authuser=1#scrollTo=-GjTvw_q7sQP))
Open file and begin running at code chunk 1 (instructions within collab as comments to understand the code)

## Link to Paper and Data Files
For reference to the original study and access to the datasets used in this replication, please visit [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/ASXOBS).

## Link to PSM Machine Learning Colab
[https://docs.google.com/presentation/d/1izyNkTTR634ye9lQSorWV7mgFgMZGVNq/edit?usp=sharing&ouid=106975341459544501752&rtpof=true&sd=true
]([https://colab.research.google.com/drive/1HR3c7cwMA3ZgBUK-DcXSK2X3ACdooOZl?usp=sharing](https://colab.research.google.com/drive/1WX1UsRDY-IrkP2XQ2NkOhlufixzMn_kY?authuser=1#scrollTo=YXrB4Gl28jI2))
Open file and begin running at code chunk 1 (instructions within collab as comments to understand the code)
