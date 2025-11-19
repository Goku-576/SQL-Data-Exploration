# COVID-19 Global Data Exploration and Visualization

![SQL](https://img.shields.io/badge/SQL-Database-blue)
![Tableau](https://img.shields.io/badge/Tableau-Visualization-orange)
![Status](https://img.shields.io/badge/Status-Complete-success)

## 📋 Project Overview

This project performs comprehensive data exploration and analysis on global COVID-19 data using SQL, with subsequent visualization in Tableau. The analysis examines infection rates, death percentages, and vaccination trends across 200+ countries using a dataset containing 89,000+ records from January 2020 onwards.

## 🎯 Objectives

- Analyze global COVID-19 trends including infection rates and mortality statistics
- Calculate death percentages and infection rates relative to population
- Track vaccination rollout progress across countries and continents
- Create reusable SQL views optimized for Tableau dashboard integration
- Identify countries with highest infection and death rates

## 🛠️ Technologies Used

- **Database:** Microsoft SQL Server
- **Visualization:** Tableau
- **Tools:** SQL Server Management Studio (SSMS), Excel (data preprocessing)
- **Skills Demonstrated:** 
  - Advanced SQL queries (JOINs, CTEs, Temp Tables, Window Functions)
  - Aggregate functions and data type conversions
  - View creation for BI integration
  - Data cleaning and transformation

## 📊 Dataset

**Source:** [Our World in Data - COVID-19 Dataset](https://ourworldindata.org/covid-deaths)

**Data Range:** January 1, 2020 - Present

**Key Fields:**
- Location, Date, Population
- Total Cases, New Cases
- Total Deaths, New Deaths
- Total Vaccinations, People Vaccinated

The dataset was split into two tables:
1. `CovidDeaths` - Infection and mortality data
2. `CovidVaccinations` - Vaccination data

## 🔍 Key Analyses Performed

### 1. Death Percentage Analysis
Calculated the likelihood of dying if contracting COVID-19 by country
