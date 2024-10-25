# California Housing Analysis - Regression, Clustering, and Classification with R

Welcome to the California Housing Analysis project! This repository is a comprehensive study on the California housing dataset, applying various machine learning techniques to explore and model housing characteristics.

## Project Overview
This project uses California census data to:
- **Explore correlations and descriptive statistics**

<p align="center">
    <img width="400" alt="Screenshot 2024-10-25 at 14 33 33" src="https://github.com/user-attachments/assets/486d4deb-1f53-4f83-84c9-ea247df5117b">
</p>

  
- **Build regression models** to predict housing prices

<p align="center">
    <img src="https://github.com/user-attachments/assets/fa414e58-b5b1-41d3-b25f-5eef3ab19571" alt="description" width="500"/>
</p>
  
- **Apply clustering techniques** to identify patterns in housing data
Following the elbow method, we selected three clusters as the optimal number for our analysis:

<p align="center">
    <img src="https://github.com/user-attachments/assets/edd08f10-5321-4e54-9a95-94c9716f42c8" alt="Description of the image" width="500">
</p>


<p align="center">
    <img src="https://github.com/user-attachments/assets/cd65c601-f753-4380-9828-81bf061aa768" alt="Description of the image" width="500">
</p>


  
- **Classify housing age categories** as "old" or "new" using supervised classification

<p align="center">
    <img src="https://github.com/user-attachments/assets/c6c38f92-5848-405c-bc40-131e31801688" alt="Description of the image" width="500">
</p>



## Repository Contents
- **Data Preprocessing**: Loading and cleaning California housing data
- **Descriptive Analysis**: Basic statistics and visualizations
- **Regression Analysis**: Linear and weighted least squares regression models
- **Clustering**: Hierarchical and k-means clustering on housing data
- **Classification**: Supervised classification to categorize housing based on age

## Key Files
- **`housing_analysis.Rmd`**: Main R Markdown file with code for the project
- **`README.md`**: Project description and documentation
- **`housing.csv`**: Dataset used in this project (available upon request or found online)

## Getting Started
To run the analysis, clone this repository and run the `housing_analysis.Rmd` file in an R environment.

## Project Highlights
- **Regression**: Linear and log transformations to improve model fit.
- **Clustering**: Identification of natural groupings within housing data.
- **Classification**: Successful supervised classification of housing based on median age.

## Requirements
Install the following R libraries:
```r
library(tidyverse)
library(caret)
library(datarium)
library(ggplot2)
library(ggpubr)
library(pastecs)
library(dplyr)
library(cluster)    
library(factoextra)
library(mlbench)
library(lmtest)
library(randomForest)
