This is a repository for the UofM Data Analytics Bootcamp Course Module 19 Unsupervised Learning challenge

The dataset we're using concerns cryptocurrency valuation changes over various time periods. For this challenge we had a few objectives to tackle:
  - Preparing the data for use (loading in the data set, then scaling it)
  - Finding the best value for k using the elbow method (this was done once here and then a second time when performing a PCA analysis)
    - Below is a composite of both elbow graphs that were generated
    - ![compositeelbowcurve_crypto](https://github.com/user-attachments/assets/f70ed163-7432-4e1a-9b1d-9e641ee72d73)
  - Cluster the cryptocurrencies using KMeans and make predictions based on our scaled dataset
    - Below is a scatter plot of the generated predictions
    - ![cryptopredictionplot_nopca](https://github.com/user-attachments/assets/58add28d-8834-4b7b-b111-eb76e57ac425)
  - Optimize the generated clusters using Principal Component Analysis, using a component amount of 3
  - Running an elbow method test again using the PCA results (see first image for the generated elbow plot)
  - Cluster the cryptocurrencies using KMeans and make predictions based on the PCA optimized data
    - Below is a scatter plot of the generated PCA predictions
    - ![cryptopredictionplot_pca](https://github.com/user-attachments/assets/f75241d2-94bc-4dd3-befb-590710db68b2)
    
I hope the analysis and visualizations offered here prove to be insightful and helpful.

Instructions for running this project on your local machine:
  - Clone this repository to your computer
  - Open Crypto_Clustering.ipynb in your code editor of choice (Jupyter Notebook, VSCode, etc)
  - Run the entire script or individual cells at your discretion
