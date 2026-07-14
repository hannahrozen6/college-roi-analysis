# college-roi-analysis
A data-driven analysis of college return on investment (ROI) across 1,173 U.S. universities using R, evaluating long-term financial returns and the impact of regional economic conditions.
 
## Overview
Compiled and analyzed a comprehensive dataset combining institutional demographic and financial data with state economic contexts. Evaluated short- and long-term financial returns across 1,173 four-year U.S. universities and examined the impact of regional employment rate on college return on investment (ROI).

## Repository Structure
- `College-ROI.qmd`: The core Quarto document containing the R code, data cleaning, financial metric engineering, and regression analysis.
- `College-ROI.pdf`: The finalized, compiled report detailing the findings and visualizations.
- `data/`
  - `school_data.RData`
  - `state_info.csv`

## Tools & Technologies
- **Languages & Tools:** R — `tidyverse` (`dplyr` for data manipulation & `ggplot2` for scatterplot regression visualization), `knitr` for LaTeX summary tables, and Quarto for reproducible reporting
- **Methodologies:**  Long-Term Financial Metric Modeling, Macro-Environmental Control Analysis, and Bivariate Ordinary Least Squares Regression

How to Use This Repo
1. Clone this repository to your local machine.
2. Ensure you have [R](https://cran.r-project.org/) and [RStudio](https://posit.co/download/rstudio-desktop/) installed.
3. Open `Hannah_Rozenbaum_Final.qmd` in RStudio.
4. Ensure the required libraries (`tidyverse`, `readr`, `knitr`, `ggplot2`, `gridExtra`) are installed. 
5. Click **Render** to execute the code and generate the PDF report.

