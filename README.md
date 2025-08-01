# Tech Layoffs Data Analysis with MySQL

This project focuses on cleaning and analyzing a real-world dataset of global tech layoffs using **MySQL**. The goal is to derive meaningful insights about the impact, trends, and patterns of layoffs across the tech industry.

## 📊 Dataset
- **Source**: [layoffs.csv](https://github.com/alex1198/Tech-Layoffs-EDA/blob/main/layoffs.csv)
- **Fields**: Company, Location, Date, Number of Laid Off Employees, Total Employees, Industry, etc.

## 🧹 Data Cleaning
Performed comprehensive data cleaning using MySQL:
- Removed duplicates and NULL values.
- Standardized column formats and data types.
- Fixed inconsistent entries (e.g., company names, dates).
- Handled missing values logically (e.g., imputation, removal).
- Created a clean, normalized table for analysis.

Script: [`Data Cleaning.sql`](https://github.com/alex1198/Tech-Layoffs-EDA/blob/main/Data%20Cleaning.sql)

## 📈 Exploratory Data Analysis (EDA)
Analyzed cleaned data to extract insights:
- Layoffs trends over time and by industry.
- Countries and companies with the highest layoffs.
- Impact on startups vs. large tech companies.
- Analysis of funding rounds in relation to layoffs.

Script: [`Exploratory Data Analysis.sql`](https://github.com/alex1198/Tech-Layoffs-EDA/blob/main/Exploratory%20Data%20Analysis.sql)

## 🛠️ Tools Used
- **MySQL** – for data cleaning and EDA.
- **CSV** – raw data format.
- **GitHub** – version control and collaboration.

## 📊 Key Insights
- Peak layoff periods identified during 2022–2023.
- Startups experienced higher layoff percentages relative to workforce size.
- Major layoffs concentrated in U.S.-based companies.

## 🚀 How to Run
1. Clone the repository.
2. Load the CSV into your MySQL environment.
3. Run the cleaning script first.
4. Execute EDA queries for insights.

