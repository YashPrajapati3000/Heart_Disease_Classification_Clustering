# Heart Disease Classification & Clustering Project

This repository presents a comprehensive analysis using classification and clustering techniques on the heart disease UCI dataset. The goal of the project is to demonstrate data pre-processing, exploratory analysis, and the application of both clustering (via k-means with PCA visualization) and classification (using k-nearest neighbors and Support vector machines) models.

## Project Overview

The project is divided into the following steps:
- **Data Integration & Exploration:** Loading the dataset and performing initial exploration.
- **Data Cleaning & Pre-processing:** Handling missing values, negative entries, and standardizing categorical variables.
- **Clustering Analysis:**  
  - Selecting relevant features and applying dummy variable transformation.
  - Using k-means clustering (with the elbow method) and visualizing clusters using PCA.
- **Classification Analysis:**  
  - Partitioning the dataset, balancing classes, and applying classification models.
  - Tuning and evaluating models (KNN and SVM) using cross-validation, ROC, and accuracy metrics.

## Repository Structure

- **data/heart_disease_uci.csv:** The dataset used for analysis.
- **analysis/Homework5.Rmd:** The R Markdown file with all code, commentary, and analysis steps.
- **analysis/Homework5.pdf:** The final PDF report produced from knitting the R Markdown file.
- **README.md:** This file is a project overview and instructions.

## How to Run the Project

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/YashPrajapati3000/Heart_Disease_Classification_Clustering.git
   cd Heart_Disease_Classification_Clustering

2. **Open the Project in RStudio:**
   - Open the analysis/Heart_Disease_Classification_Clustering.Rmd file.
   - Make sure the dataset (heart_disease_uci.csv) is located in the data/ folder.
   - Run the code chunks in the R Markdown file or click "Knit" to generate the PDF report.

3. **Review the Analysis:**
   - The knitted PDF (analysis/Heart_Disease_Classification_Clustering.pdf) contains the complete project report, including visualizations, model performance metrics, 
     and conclusions.

## Project Context
  - This project demonstrates a full pipeline of data analysis from pre-processing to model evaluation. It applies clustering to discover inherent groupings in the
    data and classification to predict the outcome using balanced, pre-processed data. The techniques showcased here are widely applicable to various datasets and
    serve as an example of practical data science workflow.

