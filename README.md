# Covid-19 Data Exploration
## Overview
This project involves in-depth data exploration and analysis of COVID-19 data using SQL. Various SQL techniques and functions are applied to derive valuable insights and visualize key metrics related to the pandemic.

## Skills Utilized
- Joins
- Common Table Expressions (CTE)
- Temporary Tables
- Window Functions
- Aggregate Functions
- Creating Views
- Converting Data Types
  
## Data Validation
To ensure data completeness, the project begins by checking the dataset for completeness in SQL Server Management Studio. This step helps identify any missing or erroneous data.

## Data Exploration
### 1. Selecting Initial Data
The project starts by selecting essential COVID-19 data, including location, date, total cases, new cases, total deaths, and population. This initial dataset forms the basis for subsequent analyses.

### 2. Analyzing Total Cases vs. Total Deaths
A comparison of total COVID-19 cases to total deaths is performed to assess the likelihood of death if contracting COVID-19 in a specific location, such as Poland.

### 3. Examining Total Cases vs. Population
This analysis determines the percentage of the population infected with COVID-19 in a specific location, such as Poland.

### 4. Identifying Countries with High Infection Rates
Countries with the highest infection rates compared to their population are identified, shedding light on the most severely affected regions.

### 5. Finding Countries with High Death Counts per Population
This analysis identifies countries with the highest death counts per population, offering insights into regions with severe COVID-19 impact.

### 6. Analyzing Data by Continent
Data is further broken down by continent, revealing continents with the highest death counts per population.

### 7. Global COVID-19 Numbers
Global statistics for new cases, total cases, and the death percentage are calculated, providing an overview of the pandemic's impact on a global scale.

### 8. Examining Population vs. Vaccinations
This section explores the percentage of the population that has received at least one COVID-19 vaccine dose, using rolling calculations to track progress over time.

### 9. Using Common Table Expressions (CTE) for Calculations
CTEs are employed to perform calculations on the partitioned data, making the analysis more efficient and organized.

### 10. Utilizing Temporary Tables for Data Processing
Temporary tables are created to perform calculations on the partitioned data, enhancing data processing capabilities.

### 11. Creating Views for Later Visualizations
A view is generated to store data for future visualization and reporting purposes.

## Data Generation for Tableau
The project concludes by generating data sets suitable for visualization in Tableau, providing opportunities for further exploration and reporting.

