# :moneybag: CryptoClustering
> In this challenge, you’ll use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

# :pushpin: Requirements
## Find the Best Value for k by Using the Original Data
![image](https://github.com/asosatrejo/CryptoClustering/assets/135572871/77f84226-1fae-43fc-91c1-ab4f1fdd2175)

- [ ] Code the elbow method algorithm to find the best value for k. Use a range from 1 to 11.
- [ ] To visually identify the optimal value for k, plot a line chart of all the inertia values computed with the different values of k.
- [ ] Answer the following question: What’s the best value for k?
## Cluster the Cryptocurrencies with K-Means by Using the Original Data 
![image](https://github.com/asosatrejo/CryptoClustering/assets/135572871/74fc469b-ec8b-45d5-873b-3988b48b1461)

- [ ] Initialize the K-means model with four clusters by using the best value for k. 
- [ ] Fit the K-means model by using the original data. 
- [ ] Predict the clusters for grouping the cryptocurrencies by using the original data. Review the resulting array of cluster values.
- [ ] Create a copy of the original data, and then add a new column of the predicted clusters. 
- [ ] Using hvPlot, create a scatter plot by setting x="price_change_percentage_24h" and y="price_change_percentage_7d". Color the graph points with the labels that you found by using K-means. Then add the crypto name to the hover_cols parameter to identify the cryptocurrency that each data point represents. 
## Optimize the Clusters with Principal Component Analysis 
- [ ] Create a PCA model instance, and set n_components=3. 
- [ ] Use the PCA model to reduce the features to three principal components. Then review the first five rows of the DataFrame. 
- [ ] Get the explained variance to determine how much information can be attributed to each principal component. 
- [ ] Answer the following question: What’s the total explained variance of the three principal components? 
- [ ] Create a new DataFrame with the PCA data. Be sure to set the coin_id index from the original DataFrame as the index for the new DataFrame. Review the resulting DataFrame. 
## Find the Best Value for k by Using the PCA Data 
![image](https://github.com/asosatrejo/CryptoClustering/assets/135572871/12ed0d58-dcfb-470b-8c46-0cdc45beaa1c)

- [ ] Code the elbow method algorithm, and use the PCA data to find the best value for k. Use a range from 1 to 11. 
- [ ] To visually identify the optimal value for k, plot a line chart of all the inertia values computed with the different values of k. 
- [ ] Answer the following questions: What’s the best value for k when using the PCA data? Does it differ from the best value for k that you found by using the original data? 
## Cluster the Cryptocurrencies with K-means by Using the PCA Data 
![image](https://github.com/asosatrejo/CryptoClustering/assets/135572871/68136b4b-953e-48dc-8267-62c50abbb656)

- [ ] Initialize the K-means model with four clusters by using the best value for k. 
- [ ] Fit the K-means model by using the PCA data. 
- [ ] Predict the clusters for grouping the cryptocurrencies by using the PCA data. Review the resulting array of cluster values. 
- [ ] Create a copy of the DataFrame with the PCA data, and then add a new column to store the predicted clusters. 
- [ ] Using hvPlot, create a scatter plot by setting x="PC1" and y="PC2". Color the graph points with the labels that you found by using K-means. Then add the crypto name to the hover_cols parameter to identify the cryptocurrency that each data point represents. 
## Visualize and Compare the Results 
- [ ] Create a composite plot by using hvPlot and the plus sign (+) operator to compare the elbow curve that you created from the original data with the one that you created from the PCA data. 
- [ ] Create a composite plot by using hvPlot and the plus (+) operator to compare the cryptocurrency clusters that resulted from using the original data with those that resulted from the PCA data. 
- [ ] Answer the following question: Based on visually analyzing the cluster analysis results, what’s the impact of using fewer features to cluster the data by using K-means? (5 points)
## Coding Conventions and Formatting 
- [ ] Place imports at the top of the file, just after any module comments and docstrings, and before module globals and constants. 
- [ ] Name functions and variables with lowercase characters, with words separated by underscores. 
- [ ] Follow DRY (Don't Repeat Yourself) principles, creating maintainable and reusable code. 
- [ ] Use concise logic and creative engineering where possible. 
## Deployment and Submission 
- [ ] Submit a link to a GitHub repository that’s cloned to your local machine and that contains your files. 
- [ ] Use the command line to add your files to the repository. 
- [ ] Include appropriate commit messages in your files. 
## Code Comments 
- [ ] Be well commented with concise, relevant notes that other developers can understand. 

# 📂 Files
- :file_folder: Resources
   - :page_facing_up: crypto_market_data.csv
- :page_facing_up: Crypto_Clustering_starter_code.ipynb
- :page_facing_up: README.md
