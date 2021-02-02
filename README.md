# Clustering of the Stack Overflow related research papers  

* Research papers related to the famous Q&A site **Stack Overflow** are listed in [this link](https://meta.stackexchange.com/questions/134495/academic-papers-using-stack-exchange-data)  
* **70 papers** are collected in the pdf format from there
* The paper contents are parsed
* The parsed contents are sanitized for clustering by **removing the common English words**
* Also removed two most obvious words, 'Stack' and 'Overflow'
* The content has been **vectorized**
* Unsupervised clustering algorithm was applied on the vectorized content
* **K-means algorithm** has been used for the clustering
* **Elbow method** has been used to find a good value for the K
* The clusters and cluster details are plotted
* **A web page** has been constrcted with the plots and the description
