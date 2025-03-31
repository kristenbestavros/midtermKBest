## Midterm Submission

This repository contains the code, data, and report for my midterm project in MA415 (Data Science in R). The assignment focuses on analyzing USDA data on strawberry production in California and Florida, with an emphasis on chemical usage and organic farming metrics.

## Project Description

The analysis explores two main areas:

1. **Chemical Usage (Conventional Strawberries)**  
   I selected three chemicals—Abamectin, Cyprodinil, and Fludioxonil—for comparison. These were chosen due to their presence in both states and their divergent usage patterns. The project examines total usage, proportional use, changes over time, and correlation between chemicals commonly applied together.

2. **Organic Strawberry Production and Sales**  
   I compare key metrics such as yield per acre, price per CWT, and revenue per acre for organic strawberries in California and Florida. Derived metrics were calculated from reported acres, volume, and sales data.

The final report includes commentary, plots, and tables addressing trends, potential explanations, and data limitations.

## Repository Contents

| File                          | Description                                                               |
|-------------------------------|---------------------------------------------------------------------------|
| `USDA-NASS strawberries.qmd`  | Quarto source file containing code, analysis, and written commentary.     |
| `USDA-NASS strawberries.html` | Rendered HTML version of the full report.                                 |
| `class 15 - Mar 20.Rproj`     | RStudio project file for opening the workspace.                           |
| `my_functions.R`              | Helper functions used for data cleaning and display.                      |
| `strawb_mar6.csv`             | Dataset based on USDA NASS strawberry data.                               |
| `README.md`                   | This file.                                                                |
| `.gitignore`                  | Standard Git ignore rules for R and Quarto projects.                      |
