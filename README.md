# Customer Segmentation for an Online Retailer using Clustering

**MIS 451 – Machine Learning for Business** · Group Project: *Clustering - Business Pattern Discovery and Segmentation*

We group customers of a UK online retailer by their purchasing behaviour using three clustering models (K-Means, Hierarchical, Autoencoder + K-Means), then turn each segment into business recommendations.

## Open in Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DuongvuBBS20/MIS451-Customer-Segmentation/blob/main/notebooks/MIS451_Customer_Segmentation.ipynb)

The notebook reads the data directly from this repo. Click the badge, then **Runtime → Run all**.

## Repository structure
```
├── data/
│   └── online_retail_II.csv.gz            # dataset (both Excel sheets combined, compressed)
└── notebooks/
    └── MIS451_Customer_Segmentation.ipynb # full project notebook
```

## Dataset
Online Retail II - UCI Machine Learning Repository
https://archive.ics.uci.edu/dataset/502/online+retail+ii

1,067,371 transactions from 01/12/2009 to 09/12/2011, 8 columns. After cleaning and aggregation: 5,852 customers with 7 features.

## Team
| Member | Role | Notebook sections |
|---|---|---|
| Dương (Team leader) | Business & Data Analyst | 1-4: Business context, data collection, EDA |
| Như | Data Engineer | 5-6: Data cleaning, feature engineering |
| Ngọc | ML Modeler | 7-8: Models and evaluation |
| Bảo | Business Insight & Tools | 9-11: Cluster profiling, tool comparison, limitations |
