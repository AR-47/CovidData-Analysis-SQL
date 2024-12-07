# CovidData-Analysis-SQL

## Project Overview
This project analyzes COVID-19 data using SQL. The analysis focuses on key metrics like total cases, total deaths, population data, and vaccination rates across various countries and continents. The goal is to explore the trends, compare death rates, and study the impact of vaccinations on the population.

## Data Sources
The datasets used in this project are sourced from [Our World in Data](https://ourworldindata.org/covid-deaths) and include:
- **CovidDeaths**: Contains data on COVID-19 cases and deaths by country and date.
- **CovidVaccines**: Contains data on COVID-19 vaccination counts by country and date.

Both datasets allow for analysis of:
- Death rate per population
- Infection rate compared to population
- Vaccination progress vs population
- And more...

### Dataset Files:
- `CovidDeaths`: [Description of data structure]
- `CovidVaccines`: [Description of data structure]

**File Sizes:**
- `CovidDeaths`: 17 MB
- `CovidVaccines`: 8 MB

## Setup Instructions

### Prerequisites:
- SQL Server or a similar database management system to run the queries.
- The dataset files (`CovidDeaths` and `CovidVaccines`) are provided directly in this repository.

### Running the Queries:
1. Download or clone this repository to your local machine.
2. Import the datasets (`CovidDeaths` and `CovidVaccines`) into your SQL Server database.
3. Open your SQL management tool (e.g., SQL Server Management Studio) and execute the SQL queries provided in the repository.

### Sample SQL Queries:
- **Total Cases vs. Total Deaths**: To analyze the likelihood of death if infected with COVID-19.
- **Total Cases vs. Population**: To examine the percentage of the population infected.
- **Highest Infection Rate**: To find the countries with the highest infection rates.
- **Vaccination Impact**: To compare vaccination rates with the population.

## How to Contribute:
Feel free to fork this project, make improvements, and create a pull request. Contributions are welcome!

## License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments:
- The datasets used in this project are sourced from [Our World in Data](https://ourworldindata.org/covid-deaths).
- Thanks to the open-source community for tools and libraries that made this analysis possible.

