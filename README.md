# Segmentation-using-kmeans-algorithm 
# Task 
From the given 'iris' dataset predict the optimim number of clusters and present it visually 
# Tools 
python  3 
## Librairies 
Numpy sklearn statsmodels matplotlib seaborn scipy  
## Task outline  
checking K-means input data requirements : 
  * duplicates 
  * missing data 
  * Outliers 
  * Data skewness using qq-plit and shapiro walk test  
  * Variables multicolinearity 
  * Data scale 
We removed dependent (highly correlated) variables (PetalLengthCM) 
Run Kmeans algorithm 
Choose K using ELbow method 
Run kmeans again 
Visualization of the clusters

# Result 
![cluster](https://user-images.githubusercontent.com/49712115/153066958-c3309ca5-dce8-4e0e-8dc9-e7bd8460144a.png)
![elbow](https://user-images.githubusercontent.com/49712115/153066963-a906dc9a-dddc-4ddf-83be-edfde9e9a182.png)
