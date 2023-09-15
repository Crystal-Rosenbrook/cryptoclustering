# cryptoclustering
Cryptocurrency Clustering Analysis
Table of Contents
Homework Files
Introduction
Prerequisites
Installation
Usage
References
Dataset

Homework Files
Crypto_Clustering.ipynb and crypto_market_data.csv

Introduction
The Cryptocurrency Clustering Analysis project aims to provide an insight into the cryptocurrency market by grouping similar cryptocurrencies. The project employs K-means clustering algorithm and Principal Component Analysis (PCA) for dimensionality reduction.

Prerequisites
Python 3.x
Pandas
Matplotlib
scikit-learn
HoloViews
hvPlot

Installation
Clone the repository:
git clone https://github.com/Crystal-Rosenbrook/cryptoclustering.git
Navigate to the project directory:
cd your_project_name
Install the required packages:
pip install -r requirements.txt

Usage
Load your data by replacing crypto_market_data.csv with your own dataset. Make sure that the dataset contains at least coin_id, price_change_percentage_24h, and price_change_percentage_7d columns.

Run the main Python script to perform the clustering analysis:
python main_script.py

Observe the plotted graphs for the Elbow Method to determine the optimal value of K for clustering.

Check out the clustered cryptocurrencies visually in the scatter plot.

References
Referenced course files, Stack Overflow, Slack, scikit-learn.org, geeksforgeeks.org and ChatGPT to complete this homework

Dataset
Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.

