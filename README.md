# machine-learning-algorithms

### Clustering Techniques
K-Means clustering is applied with K=2,3,4,5,6,7,8,9,10 for all 56 datasets and the optimal value of clusters is found using `Silhouette Coefficient` and `Davies–Bouldin` index. The respective scores for various K values are visualised using boxplots.

<img src="https://i.imgur.com/Vkz2SuE.jpg" title="Silhouette Score" width="300"/>    <img src="https://i.imgur.com/MgFoJgq.jpg" title="Davies–Bouldin Score" width="300"/> 

### Feature Selection Techniques
The best features are found using `gini-split`, `rank-sum test`, and `PCA`. Their dimensionality is reduced for further classification.

<img src="https://i.imgur.com/w3bhJKD.jpg" title="Accuracy" width="300"/>    <img src="https://i.imgur.com/BYPZ3yz.jpg" title="F measure" width="300"/> <img src="https://i.imgur.com/ngcawbZ.jpg" title="Area under curve" width="300"/> 

### Classification Techniques
For classification, three variants of `naïve bayes classifiers` (Bernoulli, Multinomial and Gaussian), and two variants of `decision tree` are applied on the data. Box plot diagrams are obtained to compare the accuracy and f-measure of the various classifier models.

<img src="https://i.imgur.com/gDBRjNY.jpg" title="Accuracy" width="300"/>    <img src="https://i.imgur.com/C2bEHbk.jpg" title="F measure" width="300"/> <img src="https://i.imgur.com/iqTVAze.jpg" title="Area under curve" width="300"/> 
