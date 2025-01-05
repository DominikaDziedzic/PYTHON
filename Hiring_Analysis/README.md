# Data Analyst Hiring Analysis

## Project Overview

This project aims to analyze job offers for Data Analysts, Data Engineers, and Data Scientists by scraping data from the **pracuj.pl** platform. The goal is to provide insights into the hiring costs, salary ranges, available cities for employment, and whether it’s feasible to assemble a team in a single city.

The results will help HR understand the landscape of these roles, including key information such as:

- Estimated hiring costs for each role (in PLN - Polish złoty).
- Salary ranges for each position (in PLN).
- Possible cities for hiring (mainly in Poland).
- Whether a team can be based in a single city.

## Workflow

### Step 1: Data Collection (Selenium)
- We use Selenium to automate the process of scraping job listings from the **pracuj.pl** platform. The goal is to collect all relevant data such as job title, salary, city, and job description.

### Step 2: Data Processing (BeautifulSoup)
- After scraping the data, we use BeautifulSoup to parse the raw HTML content and extract meaningful data. The raw HTML will be transformed into a structured dataset (DataFrame) for easier analysis.

### Step 3: Data Transformation (Pandas)
- Pandas will be used to clean and transform the dataset, performing necessary calculations and filtering to get insights such as salary ranges, potential hiring locations, and expected hiring costs.

### Step 4: Data Visualization (Matplotlib)
- Matplotlib will be used to create visualizations of the findings, such as salary distributions, the number of job offers by city, and other relevant data points.

## Modules Used

- **Selenium**: Web scraping and automation.
- **BeautifulSoup**: HTML parsing and data extraction.
- **Pandas**: Data cleaning, transformation, and analysis.
- **Matplotlib**: Data visualization.

## Output

The output includes:
- **CSV files** with processed data.
- **Plots** displaying the analysis (e.g., salary distribution, hiring city distribution).

## Conclusion

This project will provide a detailed analysis of the job market for Data Analysts, Data Engineers, and Data Scientists in Poland, helping HR to make data-driven decisions about hiring. The results will include salary estimates in Polish złoty (PLN), the best cities for hiring, and insights into whether it is possible to create a team in one city.
