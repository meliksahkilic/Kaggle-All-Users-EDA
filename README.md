# Kaggle-All-Users-EDA
Exploratory Data Analysis / Kaggle All Members Dataset

🏅 Kaggle Country Medal Analysis

This repository contains a detailed data analysis of Kaggle users' medal counts, grouped and ranked by country. It focuses on uncovering insights about participation levels in data science competitions across different countries and highlights issues related to data quality and consistency.

📊 Project Overview

Analyzes medal distribution (gold, silver, bronze) across countries.

Highlights top-performing countries on Kaggle.

Cleans inconsistent country labels such as "Turkey" vs "Türkiye", "United States" vs "USA", etc.

Visualizes country rankings and identifies Türkiye's true position after correcting for inconsistent naming.

🔧 Key Features

Data Cleaning:
Standardizes inconsistent country names using a custom mapping dictionary.

Country Ranking:
Calculates total medal counts per country and ranks them accordingly.

Visualization:
Generates clear bar charts showing the top 22 countries by total medals, with Türkiye highlighted.

📁 Files

kaggle_country_medals.ipynb: Jupyter Notebook containing all the data processing, cleaning, analysis, and visualizations.

README.md: Project documentation (this file).

📌 Notable Insights

Many countries were misrepresented due to inconsistent or missing country names.

Türkiye was split into "Turkey" and "Türkiye" entries — combining them changed its position in the global ranking significantly.

Users without a country assigned (e.g., None) collectively contributed a notable number of medals.

📉 Visual Outputs

Horizontal and vertical bar charts for medal rankings.

Highlighted position of Türkiye post-cleaning.

Optional breakdown by medal type available.
