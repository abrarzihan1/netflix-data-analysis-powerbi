# 📊 Netflix Movies and TV Shows Analysis with Power BI

This project is a Power BI analysis of Netflix Movies and TV Shows data. It was created to demonstrate skills in data cleaning, transformation, and visualization.

## 🔍 Project Overview

Using a dataset of Netflix titles, this project aims to:
- Clean and preprocess raw data
- Perform exploratory data analysis (EDA)
- Create insightful visualizations to understand Netflix’s content library by type, genre, country, year, and more

## 📁 Dataset

The dataset contains metadata for Netflix Movies and TV Shows, including:
- Title, Type (Movie/TV Show), Director, Country, Date Added
- Duration, Release Year, and Categories (Listed In)

Source: [Netflix Movies and TV Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)

## ⚙️ Tools Used

- **Power BI Desktop** for data transformation and visualization
- **Power Query Editor** for cleaning and preprocessing

## 🔧 Data Loading & Cleaning

- Loaded data from a `.csv` file into Power BI
- Used Power Query to address:
  - Parsing errors
  - Missing values in `type`, `director`, and `country`
  - Inconsistent formats in `duration` and `date_added`

### Key Transformations:

- Converted `date_added` to proper Date type
- Converted `release_year` to Whole Number
- Handled multi-valued fields in `listed_in` by:
  - Splitting into multiple rows
  - Extracting the first genre category
- Imputed missing values using appropriate strategies (e.g. replacing with 'Missing' or mode)

## 📊 Exploratory Data Analysis

The dashboard includes insights like:
- Distribution of Movies vs TV Shows
- Top genres/categories by count
- Title trends by release year
- Country-wise content distribution
- Total titles and directors in dataset
- Earliest and latest release years

### Final Dashboard Preview:

![Screenshot 2025-06-09 154725](https://github.com/user-attachments/assets/c72e1b28-955f-4ffe-8edc-bb8e4070f268)

## ✅ Key Insights

- Majority of titles are **Movies** (~70%)
- **United States** dominates the content library
- Top genres include **International Movies**, **Dramas**, and **Comedies**
- Content release peaked in recent years (2018–2021)
- Data spans a wide time range from **1925 to 2021**

## 📌 What I Learned

- End-to-end Power BI project workflow
- Data cleaning techniques using Power Query
- How to build interactive visualizations and dashboards
