# Family Height Analysis

## Overview
This repository contains data and analysis related to family heights, exploring the relationship between parental heights and the heights of their children. It includes datasets, scripts for data analysis, and visualizations.

## Dataset Used
The primary dataset used in this analysis is from Galton's observations on children's and their parents' heights, sourced from [https://www.kaggle.com/datasets/jacopoferretti/parents-heights-vs-children-heights-galton-data]. The dataset file (GaltonFamilies.csv) is included in this repository.

## Table of Contents
- [Introduction](#Introduction)
- [Features](#Features)
- [Data](#Data)
- [Requirements](#Requirements)
- [Prodigy Infotech Internship](#Prodigy_Infotech_Internship-Task_2)
- [License](#license)

## Introduction
The analysis focuses on understanding how parental heights influence the heights of their offspring. It calculates midparental height as an estimate and examines the distribution of heights among children by gender and birth order within families.

## Features
- Calculation of midparent height to estimate genetic potential.
- Analysis of height distributions among children based on gender and birth order.
- Visualizations such as scatter plots, histograms, and heatmaps to illustrate height relationships.
  
## Data
The data used in this notebook is located in the [data](GaltonFamilies.csv) directory. The dataset includes the following variables:

- family: Family identifier.
- father: Father's height.
- mother: Mother's height.
- midparentHeight: Calculated mid-parent height.
- children: Number of children in the family.
- childNum: Order of the child by height.
- gender: Gender of the child.
- childHeight: Height of the child.

## Requirements
To run the analysis scripts and visualize the data, ensure you have the following installed:

- Python (version 3.7)
- Streamlit (version 0.60)
- Pandas
- NumPy
- Seaborn
- Matplotlib

You can install Python packages using pip:
pip install streamlit==0.60 pandas numpy seaborn matplotlib

## Prodigy_Infotech_Internship-Task_2
This Exploratory Data Analysis (EDA) is conducted as Task 2 of the Prodigy Infotech internship. The objective was to perform data cleaning and exploratory analysis on a dataset of choice, focusing on understanding relationships between variables and identifying patterns and trends in family height data.

## License
This project is licensed under the [MIT License](LICENSE).



