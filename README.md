# Cryptocurrencies

### Introduction
This analysis uses unsupervised machine learning and principal components analysis (PCA) to decide which cryptocurrency to invest in.  

### Results

#### PCA
The analysis is done with three principal components. However, all three principal components explained the overall variances poorly.   The 1st principal component accounts for 2.7% of the overall variability; the 2nd principal component accounts for 2.1% of the overall variability; and the 3rd principal component accounts for 2.0% of the overall variability (see figure below). 

![Screen Shot 2022-11-29 at 1 39 52 PM](https://user-images.githubusercontent.com/108419097/204617446-515475d5-1489-4c58-bb7f-7587072afb4e.png)

#### K-Means

Based on the Elbow curve below, the best value for k is 4, meaning that 4 clusters are ideal.  

![Screen Shot 2022-11-29 at 1 56 57 PM](https://user-images.githubusercontent.com/108419097/204621065-8232a4c3-eb59-45f6-a0d6-60e78c42b452.png)

#### 3D-scatter with clusters

3D-scatter plot shows there are four distinct clusters. 
![Screen Shot 2022-11-29 at 1 58 34 PM](https://user-images.githubusercontent.com/108419097/204621363-ca60632d-d8d9-4455-95fd-39185030d8e8.png)

