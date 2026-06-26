# Clustering Analysis of ECG Data for Arrhythmia Detection

Applied unsupervised learning project using clustering methods to analyze ECG heartbeat patterns from the MIT-BIH Arrhythmia Database.

## Project Overview

This project explores how clustering methods can be used to identify patterns in ECG heartbeat signals. Using the MIT-BIH Arrhythmia Database, K-means clustering and hierarchical clustering were applied to group ECG waveforms. The clustering results were then compared with the AAMI heartbeat classifications to evaluate how well the methods identified different heartbeat types.

## Research Question

How well can clustering methods identify meaningful patterns in ECG waveform data, and how closely do the resulting clusters match the standard AAMI heartbeat classifications?

## Methods

The following methods were used in this project:

- K-Means Clustering (K = 2)
- K-Means Clustering (K = 5)
- Hierarchical Clustering
- Principal Component Analysis (PCA)
- Gap Statistic (NbClust)

## Dataset

- **Dataset:** MIT-BIH Arrhythmia Database
- **Source:** PhysioNet
- **ECG Lead:** Lead II
- **Observations:** 1,000
- **Features:** 150 waveform variables
- **Heartbeat Classes:** Normal (N), Supraventricular (S), Ventricular (V), Fusion (F), and Unknown (Q)

## Key Results

- The Gap Statistic selected **K = 2** as the optimal number of clusters.
- K-Means with **K = 5** provided the best overall clustering results.
- The Fusion (F) heartbeat class was grouped into one cluster.
- The Normal (N), Ventricular (V), and Unknown (Q) heartbeat classes showed overlap across multiple clusters.
- Hierarchical clustering grouped most observations into one large cluster and was less effective than K-Means.

Overall, K-Means with **K = 5** produced the most meaningful clustering results because it better reflected the AAMI heartbeat classes.

## Skills Demonstrated

- Unsupervised Learning
- K-Means Clustering
- Hierarchical Clustering
- Principal Component Analysis (PCA)
- Gap Statistic
- Cluster Analysis
- Biomedical Data Analysis
- Data Visualization
- R Programming

## Repository Contents

- ECG_Analysis.Rmd
- ECG_Report.pdf
- ECG_Presentation.pptx

## Author

**Massogona Cisse**

Bachelor of Science in Mathematics–Statistics  
Accelerated Degree Program (ADP) in Statistics  
University of Central Oklahoma
