# Student Employment Outcome Analysis

An Excel analysis of employment, earnings, and gender representation across college majors, completed as a Data in Motion milestone project.

**Author:** Nana Ekow Bryan Sackey  
**Tool:** Microsoft Excel  
**Scope:** 172 majors across 16 major categories

[Download the Excel workbook](Student_Employment_Analysis.xlsx)

## Project overview

This project explores how employment outcomes differ across fields of study. The goal is to identify patterns that can help college leaders and career advisers improve career support and help students understand employment and earnings outcomes.

The analysis examines:

- Which majors have the most graduates?
- How do median earnings and unemployment differ across majors and categories?
- How does gender representation vary, and how do earnings compare across predominantly male and female majors?
- Which majors have higher part-time employment and college-level job rates?
- Where could career support and employer partnerships be prioritized?

## Data preparation and methods

The workbook contains a raw dataset of 173 major-level records. Each row represents a major, not an individual student. The clean dataset retains 172 records; Food Science is excluded because its total graduate count and gender fields are missing.

I used Excel tables, calculated columns, IF formulas, PivotTables, and 12 charts to organize the data and compare outcomes. Raw and clean data are kept on separate worksheets, with analysis sheets and recommendations alongside them.

Calculated measures include:

| Measure | Calculation or rule |
|---|---|
| Gender representation | Predominantly female if women exceed 70%; predominantly male if women are below 30%; otherwise mixed |
| Full-time, year-round rate | Full-time, year-round workers / total graduates |
| Part-time rate | Part-time workers / total graduates |
| Unemployment flag | Whether the unemployment rate exceeds 6% |
| Earnings spread | 75th-percentile earnings minus 25th-percentile earnings |
| College-level job rate | College-level jobs / employed graduates; blank when employed graduates equal zero |

## Key findings

| Finding | Result in the workbook |
|---|---|
| Most common major | Psychology, with 393,735 graduates |
| Highest and lowest median earnings | Petroleum Engineering: $110,000; Library Science: $22,000 |
| Highest average unemployment by category | Social Science: 9.6% |
| Lowest average unemployment by category | Physical Sciences: 4.7% |
| Majors above 6% unemployment | 103 of 172 majors |
| Largest earnings spread | Astronomy and Astrophysics: $77,500 between the 25th and 75th percentiles |
| Highest college-level job rate | Nursing: 83.8% of employed graduates |

Predominantly male majors have an average median earnings figure of approximately **$52,094**, compared with **$33,162** for predominantly female majors. This comparison describes differences across groups of majors; it does not establish a gender pay gap within the same occupation.

## Recommendations

1. **Prioritize career support in higher-unemployment fields.** Expand internships, employer partnerships, career fairs, and job-placement support, particularly for Social Science, Law & Public Policy, and Arts.
2. **Connect coursework with employer needs.** Explore practical training and relevant certifications in lower-earning fields to broaden graduates' career options.
3. **Use employment and earnings data in career advising.** Discuss salary ranges, employment outcomes, and alternative career paths alongside students' interests.

## Interpretation notes

- Category unemployment figures are unweighted averages of major-level rates, not unemployment rates calculated from pooled graduate counts.
- Earnings comparisons across groups use averages of each major's median, not a pooled median for all graduates.
- Low-wage job counts depend partly on the size of each major and should not be interpreted as individual risk without an appropriate denominator.
- This is a descriptive learning project. The workbook does not document the original data collection period or source URL, so its figures should not be presented as current labor-market estimates.

## Explore the workbook

Download the `.xlsx` file and open it in Excel to review the raw data, calculated fields, PivotTables, charts, and recommendations.

[View my Tableau Public portfolio](https://public.tableau.com/app/profile/nana.ekow.bryan.sackey)
