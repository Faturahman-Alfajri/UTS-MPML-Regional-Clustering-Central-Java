# UTS-MPML-Regional-Clustering-Central-Java
Midterm exam project for Modern Prediction and Machine Learning: regional clustering analysis of districts/cities in Central Java using BPS 2025 data.

# Regional Clustering Analysis of Districts/Cities in Central Java Province

This repository contains the Midterm Exam Project for the Modern Prediction and Machine Learning course.

## Student Information

Name: Faturahman Alfajri  
Student ID: 24611042  
Class: A  
Course: Modern Prediction and Machine Learning  

## Project Description

This project aims to perform regional clustering analysis using district/city-level data from Central Java Province. The analysis uses education, economic, poverty, and demographic indicators to identify socio-economic patterns across regions.

## Data Source

The data were obtained from Badan Pusat Statistik Provinsi Jawa Tengah, specifically from *Provinsi Jawa Tengah Dalam Angka 2025*. The selected indicators refer to 2024 data.

## Variables Used

1. Average Years of Schooling
2. GRDP per Capita at Current Market Prices
3. Poverty Rate
4. Population Density

## Methods

The analysis applies two clustering methods:

1. Hierarchical Clustering
2. K-Means Clustering

The clustering results were evaluated using:

1. Silhouette Score
2. Davies-Bouldin Index

## Main Result

Both Hierarchical Clustering and K-Means Clustering produced two clusters. The evaluation results showed a Silhouette Score of 0.5898 and a Davies-Bouldin Index of 0.7242 for both methods.

The two clusters can be interpreted as:

1. High Education–High Income Urban Region
2. Developing and Economically Vulnerable Region

## Repository Files

- `MIDTERM_EXAM_PROJECT_REPORT_Faturahman_Alfajri_24611042.pdf`  
  Final project report.

- `UTS_MPML_Regional_Clustering_Central_Java.ipynb`  
  Jupyter Notebook / Google Colab file containing the full analysis process.

- `01_cleaned_central_java_clustering_2024.csv`  
  Cleaned dataset used in the analysis.

- `02_standardized_central_java_clustering_2024.csv`  
  Standardized dataset after z-score standardization.

- `03_hierarchical_clustering_result.csv`  
  Hierarchical clustering result.

- `04_final_clustering_results_central_java_2024.csv`  
  Final clustering result containing Hierarchical and K-Means cluster labels.
