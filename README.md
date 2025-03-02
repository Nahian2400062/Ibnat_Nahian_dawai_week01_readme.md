# Ibnat_Nahian_dawai_week01_readme.md

## Research Question

Can self-reported social class be influenced by non-economic factors such as religious beliefs rather than income and education alone?

## Dataset Overview

- Source: World Values Survey (Wave 7: 2017-2022)
- Location: `D:\CEU_MA_EDP\Winter 2025\AI for EDP\WVS_subset.csv`
- Observations: 97,220
- Variables: 168
- Description: This dataset includes responses on social, political, economic, and cultural values across different countries.

## Selected Variables (for analysis)

| Variable  | Description | Type |
|-----------|---------------------------|--------|
| Q288      | Income Level (1-10 scale) | Numeric |
| Q287      | Subjective Social Class (Working, Middle, Upper, etc.) | Factor |
| Q279      | Employment Status | Factor |
| Q275      | Highest Educational Level Attained | Factor |
| Q270      | Number of People in Household | Numeric |
| Q285      | Chief Wage Earner Status | Binary |
| Q289      | Religious Denomination | Categorical |
| Q273      | Marital Status | Factor |
| Q277      | Mother's Education Level | Factor |
| Q278      | Father's Education Level | Factor |

## Descriptive Statistics (5 Key Variables)

| Variable               | Count | Mean | Std Dev | Min | 25% | 50% | 75% | Max |
| ---------------------- | ----- | ---- | ------- | --- | --- | --- | --- | --- |
| Q288 (Income Level)    | 97220 | 4.70 | 2.38    | -5  | 3   | 5   | 6   | 10  |
| Q287 (Social Class)    | 97220 | 2.88 | 1.77    | -5  | 2   | 3   | 4   | 5   |
| Q279 (Employment)      | 97220 | 3.05 | 2.15    | -5  | 1   | 3   | 5   | 8   |
| Q275 (Education Level) | 97220 | 3.49 | 2.13    | -5  | 2   | 3   | 5   | 8   |
| Q270 (Household Size)  | 97220 | 3.95 | 2.65    | -5  | 2   | 4   | 5   | 7   |

