# CryptoClustering
<h1> Background </h1>
<p> In this challenge, unsupervised machine learning was adopted to predict the effect of 24-hour and 7-day price changes of cryptocurrencies by using Python <code>scikit-learn</code>. </p>
<h1> Technical Process </h1>
<p> The initial part of the analysis involved the loading of the <code>crypto_market_data.csv</code> into a DataFrame. The data was then normalized using the <code>StandardScaler()</code> module. Followed by identifying the best value for <code>k</code> by using the elbow method, clusters were created with the optimal <code>k</code> value.</p>
<p>The second part of the analysis involved the use of Principle Component Analysis (PCA) to optimize the clusters. Similar process was implemented.</p>
<p>Lastly, the elbow plot and the cluster analysis of the non-normalized and normalized data were compared to evaluate the impact of using fewer features to cluster the data with the use of K-means.</p>