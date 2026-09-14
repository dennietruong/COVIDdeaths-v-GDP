# 📊 GDP and COVID-19 Cases & Deaths

**Dennie Truong (2022)**

[![Project](https://img.shields.io/badge/Project-Applied%20Statistics-2f6f8f)](#)
[![Focus](https://img.shields.io/badge/Focus-Public%20Health%20%26%20Economics-4c956c)](#)
[![Study Period](https://img.shields.io/badge/Data-Jan%202020%20%E2%80%93%20Apr%202022-6c757d)](#)

> **Examining whether a US state's economic output is associated with the spread and severity of COVID-19.**

**Abstract:** Prior studies in Europe and China reported positive associations between economic growth/GDP and COVID-19 spread, suggesting that urbanization and economic activity may facilitate transmission. This project tests whether a similar relationship holds across US states and Washington, DC, using combined data on state GDP, COVID-19 case and death rates, US region, and governor's political party from January 2020 to April 3, 2022. Using linear regression, chi-square, and ANOVA tests, we found no evidence of an association between a state's GDP and total COVID-19 deaths (r = 0.195, n = 51, p = 0.172), no evidence of an association between US region and total COVID-19 cases (χ² = 9.770, n = 51, p = 0.375), and no evidence of a difference in mean COVID-19 deaths by governor's political party (F = 2.098, n = 51, p = 0.150). These results contrast with earlier international findings, potentially due to differences in urbanization timing and the stage of the pandemic examined.

## 🔬 Research Question

**Is there an association between US states' GDP and COVID-19 deaths (from January 2020 to April 2022)?**

## 📚 Background & Motivation

* A study across 28 European countries found a **positive association between GDP and total COVID-19 cases** (regression coefficient = 0.7156, p < 0.001) (Aycock & Chen, 2021).
* A study across 30 of China's provinces found **GDP positively associated with COVID-19 cases** (r = 0.69, p < 0.01) (Mo et al., 2021).
* These studies suggest economic growth and urbanization may create more opportunities for COVID-19 to spread.
* **Motivation:** If such an association exists, governments could better target public health resources to states based on their specific economic and regional needs.

## 🧪 Methods

### Data

Combined dataset covering **50 states and Washington, DC**, drawn from:

* Worldometer
* Ballotpedia
* US Bureau of Economic Analysis (BEA)
* US Energy Information Administration (EIA)
* The New York Times

### Variables

**Explanatory variables**

* State's GDP (in billions)
* US region (W = West, M = Midwest, N = Northeast, S = South)
* Governor's political party

**Response variables**

* Total COVID-19 cases, categorical (per 100,000 people): A: < 20%, B: 20–25%, C: 25–33.33%, D: > 33.33%
* Total COVID-19 cases, numeric (per 1,000,000 people)
* Total COVID-19 deaths, categorical (per 100,000 people): A: < 0.15%, B: 0.15–0.25%, C: 0.25–0.37%, D: > 0.37%
* Total COVID-19 deaths, numeric (per 1,000,000 people)

### Statistical Tests

| Relationship examined | Test |
| --- | --- |
| GDP vs. COVID-19 deaths | Linear regression / correlation |
| US region vs. COVID-19 cases | Chi-square test of association |
| Governor's political party vs. COVID-19 deaths | ANOVA |

## 📊 Key Findings

| Test | Statistic | n | p-value | Result |
| --- | --- | --- | --- | --- |
| GDP (log) vs. COVID-19 deaths | r = 0.195 | 51 | 0.172 | No evidence of association |
| US region vs. COVID-19 cases | χ² = 9.770 | 51 | 0.375 | No evidence of association |
| Governor's party vs. COVID-19 deaths | F = 2.098 | 51 | 0.150 | No evidence of difference |

* No evidence of a correlation between a state's log(GDP) and total COVID-19 deaths.
* No evidence of an association between US region and total COVID-19 cases.
* No evidence of a difference in mean COVID-19 deaths across governors' political parties.

## 🧠 Interpretation

* We found **no evidence** that a state's GDP, US region, or governor's political party are associated with COVID-19 outcomes in this dataset.
* These results contrast with the earlier European and Chinese studies, which found positive associations between GDP and COVID-19 spread.

## ⚠️ Limitations

The contrast with prior findings may be explained by:

* Urbanized regions being hit first by COVID-19, independent of GDP.
* The earlier studies being based on data from early in the pandemic, whereas this study spans January 2020–April 2022.

This study is limited to US states (and DC) through April 3, 2022, and is therefore only representative of a snapshot in the pandemic's history.

## 🔭 Future Study

Future work could examine additional relationships, such as:

* Duration of mask mandates
* Percent vaccinated
* Percent boosted

...compared against total COVID-19 cases and deaths.

## 📁 Data

| File | Description |
| --- | --- |
| *COVID-19_Vaccinations_in_the_United_States_Jurisdiction.csv* | COVID vaccination across the United States  |
| *United_States_COVID-19_Cases_and_Deaths_by_State_over_Time.csv* | State-level dataset: COVID-19 cases/deaths |
| *SC212ProjectData.csv* | Combined/merge dataset: GDP, COVID-19 cases/deaths, US region, governor's political party |

## 📄 Presentation

**Truong, Dennie (2022).** *GDP and COVID-19 Cases & Deaths.* SC212 Statistics, Colby College, Waterville, ME.

## 📚 References

* Aycock, Lauren, and Xinguang Chen. "Levels of Economic Development and the Spread of Coronavirus Disease 2019 (COVID-19) in 50 U.S. States and Territories and 28 European Countries: An Association Analysis of Aggregated Data." *Global Health Journal*, vol. 5, no. 1, Mar. 2021, pp. 24–30.
* Mo, Qiqing, et al. "Levels of Economic Growth and Cross-Province Spread of the Covid-19 in China." *Journal of Epidemiology and Community Health*, vol. 75, no. 9, 2021, pp. 824–828.

## 👤 Author

**Dennie Truong**
Colby College '24
Environmental Science · Biology · Mathematics

## 🔑 Keywords

`Applied Statistics` · `COVID-19` · `GDP` · `Public Health` · `Linear Regression` · `Chi-Square Test` · `ANOVA` · `US States`
