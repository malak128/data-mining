# Crime Analysis Project

## Description
Analysis of San Francisco crime data including preprocessing, feature engineering, clustering, and Random Forest classification.

## Dataset
- File: `data/train.csv`

## Preprocessing & Feature Engineering
- Remove duplicates and null values
- Encode categorical variables
- Create datetime features (year, month, hour, day of week)
- Normalize numeric columns

## Clustering
- KMeans used to discover crime zones
- KMedoids used to refine geospatial clusters

## Modeling
- Random Forest classifier to predict clusters
- Feature importance visualization
- Evaluation metrics: Accuracy, Confusion Matrix, Precision, Recall, F1-Score, Cross-Validation

## GUI Screenshots
### Crimes by Hour
![Crime by Hour](images/crime_by_hour.png)
### Crimes by Day
![Crime by Day](images/crime_by_day.png)
### K-Medoids Clusters
![KMedoids Clusters](images/kmedoids_clusters.png)

## Requirements
Install dependencies:
```bash
pip install -r requirements.txt
