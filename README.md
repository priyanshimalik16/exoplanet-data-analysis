# exoplanet-data-analysis
Data cleaning and EDA on Nasa Exoplanet archive data
# Exoplanet Data analysis- Week 1 project
Data cleaning and exploratory data analysis (EDA) on NASA's Exoplanet Archive (planetary systems composite table), covering 6,336 confirmed exoplanets across 84 original variables.
# Overview
This project was completed as part of a Data Science internship task. It walks through the full data preparation pipeline, acquiring a real public dataset, assessing and cleaning missing data and extracting insights through exploratory visualization.
# What I did
- Loaded and inspected a row,84 column dataset using pandas
- Identified columns with over 65% missing data (mostly measurement uncertainty fields) and removed them, reducing the dataset to 75 columns.
- Imputed remaining missing values in key physical columns using the median, chosen for robustness against outliers common in astronomical data.
- Created 3 visualizations: a missing-values heatmap, a discovery-year histogram, and a correlation heatmap of planet properties.
# Key findings
- Exoplanet discoveries spiked sharply around 2014-2016, coinciding with confirmed batches of NASA's Kepler mission data.
- Planet radius and planet mass show a moderate positive correlation (0.44).
- Steller radius and stellar mass are similarly connected (0.43).
- orbital period shows little correlation with other physical properties in this data set.
# Tools
Python, pandas, matplotlib, seaborn, Jupyter notebook (VS Code).
# Data source
[NASA Exoplanet Archive} (https://exoplanetarchive.ipac.caltech.edu/) —Planetary Systems composite Table

