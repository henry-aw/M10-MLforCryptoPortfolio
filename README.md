# *Module 10 Challenge*
## Using Machine Learning to Assemble Investment Portfolios Based on Cryptocurrencies

**Welcome to my Module 10 Challenge repository. Here, you can check out the Unsupervised Learning approach I took to assembling investment portfolios based on cryptocurrencies.**

---

## Background
This project clusters cryptocurrencies by their performance in different time periods, then shows visualizations to gain an undertsanding of the predictions.

This is divided into the following sections:
- Import the data
- Prepare the data
- Find the best value for k using the original data
- Cluster cryptocurrencies with K-means using the original data
- Optimize clusters with Principal Component Analysis (PCA)
- Find the best value for k using the PCA data
- Cluster the cryptocurrencies with K-means using the PCA data
- Visualize and compare the results

---

## Technologies & Usage
This project leverages scikit-learn, Python 3.7, and the Pandas library with the following requirements and dependencies:
- import pandas as pd
- import hvplot.pandas
- from path import Path
- from sklearn.cluster import KMeans
- from sklearn.decomposition import PCA
- from sklearn.preprocessing import StandardScaler
