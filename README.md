# Team Asthma Project Analysis

## Project Overview
This project, conducted by Team Asthma, utilizes Synthea-generated datasets to mirror Medicaid and Medicare patients, focusing on asthma-related analysis. The findings and methodologies are detailed through R Markdown, which integrates R and SQL for a comprehensive data analysis experience.

## Files
The repository contains the following file:
- `Final_Project_Team_Asthma_code.Rmd` - An R Markdown document that includes all analyses, visualizations, and findings related to asthma. It incorporates SQL queries for data manipulation and analysis.

## Requirements
To run the R Markdown file with integrated SQL queries, you will need R, RStudio, and appropriate SQL database connection packages installed on your computer. Here’s how to set up your environment:

1. **Install R**:
   - Download and install R from [The Comprehensive R Archive Network (CRAN)](https://cran.r-project.org/).

2. **Install RStudio**:
   - Download and install RStudio from [RStudio's official website](https://www.rstudio.com/products/rstudio/download/).

3. **Install Required R and SQL Packages**:
   - Open RStudio and install the required packages by running the following commands in the R console:
     ```R
     install.packages(c("tidyverse", "lubridate", "ggplot2", "dplyr", "knitr", "DBI", "RSQLite"))
     ```
   - Ensure you replace `RSQLite` with the package that matches your SQL database system, such as `RMySQL`, `RODBC`, or others.

## Running the Analysis
To view and run the analysis:
1. Open RStudio.
2. Go to `File > Open File` and select the `Final_Project_Team_Asthma_code.Rmd` file.
3. Run the R Markdown file by clicking on `Knit` or use the shortcut `Ctrl + Shift + K` to generate a document that includes both content and output, such as plots and SQL query results.

## Contributing
Contributions to this project are welcome. Here are some ways you can contribute:
- Enhancing the analysis through more complex SQL queries or R scripts.
- Improving visualizations and data interpretations.
- Updating and maintaining the SQL database connections.

## Authors
- Aizhan Uteubayeva

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments
- Thanks to all the data providers and supporters of asthma research.
- Special thanks to our academic and industry mentors who guided this project.
- Acknowledgment to the Synthea team for providing a realistic synthetic data generator used to mirror Medicaid and Medicare patient data.
