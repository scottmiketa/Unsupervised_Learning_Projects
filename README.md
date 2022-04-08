# Unsupervised_Learning_Projects

Includes k-means clustering to reach information gain based distinctive terms, and principal component analysis to explore a dataset of beer ratings and reviews.

## PCA_Beer.ipynb
#### Found optimal number of k to capture minimum 95% variance
#### Created a PCA heatmap
#### Generated a PCA biplot of 1st and 2nd component
Each row of the dataset corresponds to one beer review.

Each beer is reviewed on a scale from 1 to 5 using these variables:

review_appearance :: How appealing is the color, clarity of the beer?

review_aroma :: How appealing is the aroma?

review_palate :: How appealing is the "palate": the combination of carbonation, mouthfeel, alcohol profile and texture?

review_taste :: How appealing is the taste - e.g. is there a good balance of sweet and bitter?

review_overall :: How appealing is the overall experience of drinking this beer?

## Clustering_textdata.ipynb
#### Found optimal number of k to minimize Davies-Bouldin score while maximizing the Calinski-Harabsz score
#### Calculated information gain to help distinguish one cluster from another
#### Discovered distinctive terms in each cluster that maximized information gain
