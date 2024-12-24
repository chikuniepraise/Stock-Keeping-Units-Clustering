Clustering is an unsupervised machine learning technique used to group data points into clusters based on their similarity (Ester, 1996). This method is particularly effective in exploratory data analysis, where it reveals hidden patterns or groupings within datasets. Unlike classification, clustering does not depend on labeled data, making it useful in a variety of fields such as customer segmentation, anomaly detection, and market analysis (MacQueen 1967).
This report explores the application of clustering algorithms to a dataset, focusing on identifying meaningful clusters and providing insights into the underlying data structure. Using widely adopted clustering techniques such as K-Means and DBSCAN Clustering, the analysis aims to segment the data and uncover valuable patterns (Liao,2005).

Dataset Description and Exploratory Data Analysis
The dataset was gotten form the UCI repository. It consisted of 2279 observations with 7 features. The features of this dataset is only numerical. The features dated from 2017-02-06 to 2018-02-13. The columns of this dataset include ID, Unitprice, Expire date, Outbound number, Total outbound, Pal grossweight (pallet weight), Pal height (pallet height), Units per pal (number of units per pallet).
The dataset was analyzed and found that it contains several features representing characteristics of the entities under consideration. Initial exploratory data analysis (EDA) was performed to understand the distribution of features, detect missing values, and identify correlations as this step was critical for ensuring the quality and reliability of subsequent clustering analysis (Liao,2005).