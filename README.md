Video Game Sales Analysis
Exploring Global Gaming Trends Through Data Visualization and Machine Learning
Overview

This project explores historical video game sales data to uncover trends in the gaming industry, including genre performance, platform lifecycles, regional preferences, and publisher success.

Using a dataset of video games that sold over 100,000 copies worldwide, the analysis investigates what drives commercial success in gaming and how player preferences differ across markets.

The goal of this project was not only to visualize trends, but to combine business insight, statistical analysis, and clustering techniques to better understand the global gaming landscape.

Dataset

The dataset used in this project contains historical video game sales records sourced from VGChartz, including:

Game title
Platform
Release year
Genre
Publisher
North America sales
Europe sales
Japan sales
Other regional sales
Global sales
Data Cleaning

Before analysis:

Removed rows with missing release years
Limited analysis to games released up to 2016 to avoid incomplete later-year data
Removed redundant ranking columns
Checked for duplicates and missing values
Standardized fields for visualization and modeling
Tools & Technologies
Tableau

Tableau was used for:

Interactive visualizations
Trend analysis
Genre vs sales comparisons
Platform dominance over time
Publisher performance dashboards
Regional comparison charts
Storytelling and presentation-ready graphics

Tableau served as the primary tool for transforming raw data into clear visual insights.

Python (Google Colab)

Python was used for deeper analytical work, including:

Data preprocessing with pandas
Numerical analysis with NumPy
Statistical correlation analysis
K-Means clustering with scikit-learn
Heatmaps and supporting visualizations using Matplotlib / Seaborn
Validation of findings beyond visualization alone

Python was mainly used where statistical modeling and machine learning methods were needed.

Research Questions

This project focused on four key questions:

1) Genre vs Revenue

To what extent does the number of games released in each genre relate to total global sales?

Explored:

Genre popularity
Total genre revenue
Correlation between release frequency and sales performance
Whether more frequently produced genres generate proportionally higher revenue
2) Platform Dominance Over Time

How has platform dominance changed over time?

Explored:

Console lifecycle trends
Market leadership shifts between Sony, Nintendo, and Microsoft
Peaks in major platforms such as:
PlayStation 2
Wii
Xbox 360
Nintendo DS
3) Regional Preferences & Clustering

Can games be grouped based on regional sales behavior?

Using K-Means clustering, games were grouped into market-driven clusters:

North America dominant
Japan dominant
Europe / Western balanced market

This analysis revealed strong regional genre preferences, such as:

North America → Action / Sports
Japan → RPG / Adventure
Europe → Strong Sports market (ex: football/soccer titles)
4) Publisher Success

Do certain publishers consistently produce higher-selling games, and why?

Explored publisher performance through:

Total sales
Average sales per title
Franchise strength
Innovation
Platform leadership
Production quality and marketing reach

Top performers included publishers such as:

Nintendo
Electronic Arts
Microsoft
Key Findings

Some major insights:

More games released in a genre generally leads to higher total sales, but not always proportionally
Platform success is cyclical and heavily influenced by console innovation
Regional gaming preferences are strongly distinct
Publishers with strong franchises, innovation, and marketing consistently outperform competitors
The gaming industry evolves rapidly, with new technology continually reshaping market trends
