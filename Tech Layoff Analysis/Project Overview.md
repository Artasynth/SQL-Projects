# Layoffs.fyi Data Analysis

This repository contains an analysis of layoffs data sourced from [Layoffs.fyi](https://layoffs.fyi/). Layoffs.fyi is a platform that tracks layoffs in the tech industry, providing detailed insights on companies that have laid off employees.

## Overview

This project aims to analyze and visualize trends in the tech industry's layoffs using SQL to process the data, including:

- Number of layoffs over time
- Industries most affected
- Geographic distribution of layoffs
- Other key insights based on the available data

The dataset used in this analysis contains information on companies, the number of employees laid off, dates, and other relevant details. The analysis provides a deeper understanding of the current job market dynamics in the tech industry.

## Data

The data for this project was obtained from [Layoffs.fyi](https://layoffs.fyi/) and consists of publicly available information on layoffs across the tech industry. It includes columns such as:

- **Company**: The name of the company that has made layoffs.
- **Layoff Date**: The date the layoffs were announced.
- **Number of Layoffs**: The estimated or reported number of employees laid off.
- **Industry**: The sector or industry in which the company operates.
- **Location**: The geographical location of the company.
- **Raised**: The amount of fund raised by company.

### Dataset Format

The dataset is provided in CSV format. Each row represents an individual company's layoff announcement.

## Technologies

### SQL was used to clean, transform, and analyze the data. Key SQL queries include:

- **Data cleaning**: Removing missing values and normalizing data.
- **Aggregate queries**: Summing layoffs by company, date, or industry.
- **Time series analysis**: Identifying trends over time by grouping data by date.
- **Filtering**: Selecting companies by specific criteria, such as the number of layoffs or industry type).
