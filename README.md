# college-roi-analysis
A data-driven analysis of college return on investment (ROI) across 1,173 U.S. universities using R, evaluating long-term financial returns and the impact of regional economic conditions.
 
## Overview

A longer description.

## Repository Structure
- 
- `data/`
  - `school_data.RData`
  - `state_info.csv`

A quick breakdown of what your files are so people can navigate your repository:

## Tools & Technologies
- **Languages:**
- **Environments & Tools:**

How to Use This Repo

Brief instructions if someone wants to clone your code or look at your work.


# Finding the Best Schools for Your Money: A Data-Driven Analysis of College ROI

## Overview
- **Context:** Compiled and analyzed a comprehensive dataset combining institutional demographic and financial data with state economic contexts. Evaluated short- and long-term financial returns across 1,173 four-year U.S. universities and examined the impact of regional employment rate on college return on investment (ROI).
- **Languages & Tools:** R — `tidyverse` (`dplyr` for data manipulation & `ggplot2` for scatter plot regression visualizations), `knitr` for LaTeX summary tables, and Quarto for reproducible reporting.
- **Methodologies:** Long-Term Financial Metric Modeling, Macro-Environmental Control Analysis, and Bivariate Ordinary Least Squares Regression.
- **Outcome & Impact:** Developed a multi-tier financial framework calculating 1-year baseline payback periods, 5-year and estimated 10-year wage premiums, and 5-year cumulative returns on investment. Uncovered a stark contrast in the types of institutions at opposite ends of the financial returns gap. Affordable public institutions achieved the highest cumulative returns on investment, while in the bottom tier, expensive private liberal arts colleges experienced negative early-career returns. Using regression analysis, I found that ROI is largely independent of state employment rate and is much more likely impacted by institutional traits.

## Repository Structure
* `Hannah_Rozenbaum_Final.qmd`: The core Quarto document containing the R code, data cleaning, financial metric engineering, and regression analysis.
* `Hannah_Rozenbaum_Final_2.pdf`: The finalized, compiled report detailing the findings and visualizations.
* `school_data.RData`: Institutional demographic and financial dataset.
* `state_info.csv`: Macroeconomic dataset containing state-level employment and income data.

## How to Run
1. Clone this repository to your local machine.
2. Ensure you have [R](https://cran.r-project.org/) and [RStudio](https://posit.co/download/rstudio-desktop/) installed.
3. Open `Hannah_Rozenbaum_Final.qmd` in RStudio.
4. Ensure the required libraries (`tidyverse`, `readr`, `knitr`, `ggplot2`, `gridExtra`) are installed. 
5. Click **Render** to execute the code and generate the PDF report.