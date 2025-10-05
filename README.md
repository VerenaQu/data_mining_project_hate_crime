# Project: Hate Crime Data Analysis
This project analyzes FBI hate crime data to identify patterns, clustering potential, and implications for prevention programs.

# Table of Contents
1. Project Goals
2. Data
3. Requirements
4. Project structure
5. How to run
6. Notes

# Project Goals
- Explore patterns in hate crime incidents across US states
- Evaluate clustering approaches to group incidents meaningfully
- Assess data limitations
- Derive actionable recommendations for potential hate crime prevention programs

# Data
- The data used for the analysis has been downloaded from FBI Crime Data Explorer: https://cde.ucr.cjis.gov/LATEST/webapp/#/pages/home
- No filters set
- Remark: Updated data for 2024 has been provided on August 5, 2025

# Requirements
You should have installed Python along with the following libraries:
- pandas
- matplotlib
- seaborn
- scikit-learn
- numpy
- plotly
- missingno

# Project structure
```
project-root/
├── data/
│   └── hate_crime.csv
├── notebooks/
│   └── hate_crime_clustering.ipynb
├── README.md
├── requirements.txt
```


# How to Run
- Download the FBI hate crime dataset (or use provided sample)
- Open notebooks/hate_crime_clustering.ipynb in JupyterLab or VS Code
- Run all cells step-by-step to reproduce the results

# Notes
- PCA was used for dimensionality reduction
- Clustering algorithms applied: k-Means and DBSCAN 
- Clustering quality was assessed using silhouette scores
- Visualizations include t-SNE plots, heatmaps and state-level summaries
- Since clustering results were weak, a goal-driven segmentation approach turned out to be more useful than purely technical clustering















