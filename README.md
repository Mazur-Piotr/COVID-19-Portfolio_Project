# Covid-19 Data Exploration
## Overview
This project involves in-depth data exploration and analysis of COVID-19 data using SQL. Various SQL techniques and functions are applied to derive valuable insights and visualize key metrics related to the pandemic.

## Dataset
Dataset Source: OurWorldinData
https://ourworldindata.org/covid-deaths

The dataset consists of the global data on confirmed COVID-19 deaths and vaccinations. 

## Skills Utilized
- Joins
- Common Table Expressions (CTE)
- Temporary Tables
- Window Functions
- Aggregate Functions
- Creating Views
- Converting Data Types
  
## Project Structure  
### 1. Data Validation
To ensure data completeness, the project begins by checking the dataset for completeness in SQL Server Management Studio. This step helps identify any missing or erroneous data.

### 2. Data Exploration
- Selecting Initial Data
The project starts by selecting essential COVID-19 data, including location, date, total cases, new cases, total deaths, and population. This initial dataset forms the basis for subsequent analyses.

- Analyzing Total Cases vs. Total Deaths
A comparison of total COVID-19 cases to total deaths is performed to assess the likelihood of death if contracting COVID-19 in a specific location, such as Poland.

- Examining Total Cases vs. Population
This analysis determines the percentage of the population infected with COVID-19 in a specific location, such as Poland.

- Identifying Countries with High Infection Rates
Countries with the highest infection rates compared to their population are identified, shedding light on the most severely affected regions.

- Finding Countries with High Death Counts per Population
This analysis identifies countries with the highest death counts per population, offering insights into regions with severe COVID-19 impact.

- Analyzing Data by Continent
Data is further broken down by continent, revealing continents with the highest death counts per population.

- Global COVID-19 Numbers
Global statistics for new cases, total cases, and the death percentage are calculated, providing an overview of the pandemic's impact on a global scale.

- Examining Population vs. Vaccinations
This section explores the percentage of the population that has received at least one COVID-19 vaccine dose, using rolling calculations to track progress over time.

- Using Common Table Expressions (CTE) for Calculations
CTEs are employed to perform calculations on the partitioned data, making the analysis more efficient and organized.

- Utilizing Temporary Tables for Data Processing
Temporary tables are created to perform calculations on the partitioned data, enhancing data processing capabilities.

- Creating Views for Later Visualizations
A view is generated to store data for future visualization and reporting purposes.

![image](https://github.com/Mazur-Piotr/COVID-19-Portfolio_Project/assets/138219323/30711c00-6b0a-41c4-9d29-635f67fba935)

### 3. Loaded Data to Tableau 
The project concludes by generating data sets suitable for visualization in Tableau, providing opportunities for further exploration and reporting.
### 4. Data Visualization
- Utilized data visualization tools such as Tableau to create insightful visualizations (not included in this code snippet).

![image](https://github.com/Mazur-Piotr/COVID-19-Portfolio_Project/assets/138219323/8425a594-e473-4c8f-a9bb-a2dbab0cbdd9)

## Usage
This project provides a foundational understanding of the data cleaning and transformation process required for subsequent data analysis and visualization tasks related to Covid-19 data

