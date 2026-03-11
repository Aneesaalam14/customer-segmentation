# Customer Segmentation using K-Means Clustering

Segments customers into distinct groups based on purchasing behavior using K-Means Clustering and RFM Analysis.

## Overview

This project applies unsupervised machine learning to group 5,000 customers into 4 segments: Champions, Loyal Customers, At Risk, and Lost Customers. Each segment is profiled using RFM (Recency, Frequency, Monetary) analysis to support targeted marketing strategies.

## Tech Stack

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

## Project Structure

- customer_segmentation.ipynb — Main notebook with full pipeline
- data/raw/customer_data.csv — Raw customer dataset
- data/processed/customer_segments.csv — Segmented customer data
- models/kmeans_model.pkl — Trained K-Means model
- models/scaler.pkl — Feature scaler
- requirements.txt — Required libraries

## Pipeline

1. Data generation and loading
2. Exploratory Data Analysis
3. RFM feature engineering
4. Optimal cluster selection using Elbow Method and Silhouette Score
5. K-Means clustering
6. Cluster profiling and segment naming
7. Visualizations using PCA and box plots
8. Model saving and reusable prediction function

## Segments Discovered

| Segment | Behavior |
|---|---|
| Champions | High spend, frequent, recent buyers |
| Loyal Customers | Regular buyers with medium spend |
| At Risk | Previously active, now inactive |
| Lost Customers | Long inactive, low spend |

## How to Run

1. Open customer_segmentation.ipynb in Google Colab
2. Run all cells from top to bottom

## Author

Aneesa Alam
GitHub: github.com/Aneesaalam14
