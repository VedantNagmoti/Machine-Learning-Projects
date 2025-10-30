# Principal Component Analysis (PCA) 
is a dimensionality reduction technique that transforms a large dataset into a smaller set of new variables called principal components, which capture the most variance in the original data. It helps simplify complex datasets for easier analysis, visualization, and preprocessing by finding new, uncorrelated variables that are linear combinations of the original features. PCA is widely used in exploratory data analysis, signal processing, and as a preprocessing step for machine learning algorithms.  


### How PCA works
+ Transforms data: PCA uses linear algebra to transform the original features into new features, or "principal components," that are not correlated with each other. 
+ Finds new axes: It finds the directions (eigenvectors) in the data that have the most variance and projects the data onto these new axes. 
+ Prioritizes variance: The first principal component (PC1) is the new axis that accounts for the largest possible variance, the second component (PC2) is orthogonal to PC1 and accounts for the next largest variance, and so on. 
+ Reduces dimensions: By keeping only the first few principal components, you can significantly reduce the number of dimensions while retaining most of the original information. 


### Key applications
+ Data visualization: PCA can reduce data to two or three dimensions to create scatter plots, revealing relationships and patterns in the data that might be hidden otherwise. 
+ Data preprocessing: It helps to reduce redundancy and improve the efficiency of machine learning models by creating a more compact dataset. 
+ Feature extraction: It can identify the most important original variables that contribute most to the principal components, providing insights into the data. 


### Important considerations
+ Numeric data: PCA only works with numerical features. 
+ Sensitivity to scale: PCA is sensitive to the scale of the original variables. It is a best practice to standardize the data before applying PCA to prevent variables with larger values from dominating the analysis. 
+ Outliers: Outliers can heavily influence the results, so it may be necessary to remove or constrain them before running PCA. 
