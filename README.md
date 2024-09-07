# Project Overview
This repository contains the analysis and prediction of crop yield using linear regression models. The project is part of an academic assignment that focuses on the application of statistical methods in agriculture, specifically predicting crop yield based on fertilizer usage data. The analysis is done using R programming and applies fundamental concepts from statistics, including linear regression.

# Contents
## Data: 
Crop yield dataset provided as part of the assignment.
## R Scripts:
First version: An exploratory attempt at performing the regression analysis and deriving insights.
Second version: A revised version based on the correct statistical approach.
##Reports:
First version: Initial report generated from the first script, including incorrect formatting and calculations.
Final version: Final report with corrections, following proper statistical guidelines.

# Key Concepts Covered
Linear Regression: The project involves building a linear regression model to predict crop yield based on fertilizer use.
Exploratory Data Analysis (EDA): The initial analysis includes data visualization and exploration to understand relationships between variables.
Model Evaluation: The model's performance is evaluated using metrics such as R-squared, residual analysis, and significance tests.

# Files Structure

Statistics_LinearRegressionModel_AgriculturalYieldPrediction/
│
├── data/
│   └── CropYieldData.csv          # Input dataset for analysis
│
├── scripts/
│   ├── InitialAnalysis.Rmd        # First version of the regression analysis (R Markdown)
│   ├── FinalAnalysis.Rmd          # Corrected version of the regression analysis (R Markdown)
│
├── reports/
│   ├── InitialReport.docx         # Word document report based on the first version
│   └── FinalReport.docx           # Word document report based on the final version
│
├── README.md                      # Project overview and details
└── LICENSE.md                     # Licensing information (if applicable)

# How to Run the Project
1. Install R and RStudio (if not already installed).
2. Clone this repository to your local machine git clone https://github.com/StellaZhang-Dev/Statistics_LinearRegressionModel_AgriculturalYieldPrediction.git
3. Open the .Rmd files in RStudio and knit the documents to see the analysis.
4. Alternatively, open the reports directory to view the pre-generated Word reports.

# Requirements
## R version: 4.3.3 or higher
## Packages:
ggplot2 for data visualization
dplyr for data manipulation
broom for tidying model outputs
lmtest for statistical tests
You can install these packages by running:
install.packages(c("ggplot2", "dplyr", "broom", "lmtest"))

# Insights from the Project
The linear regression model demonstrates a significant relationship between fertilizer use and crop yield. However, residual analysis reveals the need for further model refinements, potentially exploring non-linear relationships or additional variables.
The initial analysis contains formatting errors and misinterpretations, while the final version correctly applies statistical techniques to ensure a valid and interpretable model.

# License
This project is licensed under the MIT License - see the LICENSE.md file for details.

