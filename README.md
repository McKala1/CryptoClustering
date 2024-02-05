
# Crypto Clustering 📈🔍

## Introduction
Welcome to the Crypto Clustering project! 🎉 In this exciting journey, we explored clustering cryptocurrencies using the powerful K-means algorithm. Through this project, we gained valuable insights into the world of cryptocurrency markets and clustering techniques. Let's dive into what we've accomplished! 💼💡

## Instructions Completed ✅

### Renaming Files
I've renamed the `Crypto_Clustering_starter_code.ipynb` file as `Crypto_Clustering.ipynb`, keeping everything organized and tidy. 📝🔖

### Loading and Preparing Data
Data loading and preprocessing are essential steps. I've successfully loaded the `crypto_market_data.csv` into a DataFrame, set the index to the “coin_id” column, and normalized the data using `StandardScaler()`. 📊💻

### Finding the Best Value for k
Using the elbow method, I found the optimal value for k. The best value turned out to be 3 after visualizing the inertia values across different k values. 📉🤔

### Clustering Cryptocurrencies with K-Means
I've performed K-means clustering on the original scaled data, grouping cryptocurrencies based on their features. The scatterplot I created beautifully illustrates the clusters based on "price_change_percentage_24h" and "price_change_percentage_7d". 🌐🛠️

### Optimizing Clusters with Principal Component Analysis (PCA)
PCA helps in dimensionality reduction and better visualization. After applying PCA and analyzing the explained variance, I proceeded to cluster the cryptocurrencies using the PCA-transformed data. 🧮🔍

### Analyzing Results 📊📈
Analyzing the results, I found that the impact of using fewer features (PCA) for clustering was significant. Additionally, I determined the weights of each feature on each principal component, identifying features with the strongest positive or negative influence. 💡🔎

## Conclusion 🎓🚀
Completing the Crypto Clustering project has been an enriching experience! 🌟 Through this journey, I've not only learned valuable skills in data preprocessing, clustering, and dimensionality reduction but also gained insights into the fascinating world of cryptocurrency markets. 🚀📊 Now equipped with these techniques, I'm ready to tackle more complex data analysis tasks with confidence. Onwards and upwards! 💪📈
