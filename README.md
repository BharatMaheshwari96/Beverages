# Beverages
## Dataset
The dataset contained in Beverage.csv refers to different physiochemical properties of a beverage
produced by a company. This dataset has 4898 observations, with 11 input variables (physiochemical
properties) and 1 target variable (quality).
\
Each row corresponds to a batch of produced beverage. Quality of each batch can be Poor, Normal or
Excellent, and one of these labels is assigned by a beverage expert after tasting a sample from a given
batch.
\
The beverage manufacturing company does not want to rely on the beverage expert to label the quality
of each batch and wants to build a classification (prediction) model that can predict batch quality on the
basis of physiochemical properties.
### Task 1
Construct a classification model using random forest in Python. The classification goal is to predict the
quality of the produced batch.
\
Perform all necessary data preparation steps that you may deem fit and choose an appropriate traintest split. Perform necessary hyperparameter tuning to construct an optimal model. Ultimately, arrive at your best random forest model that incorporates a subset of significant features.
\
Based on information obtained about predictive power of various features used in your final model (using feature_importances), what recommendations can you make to the production department of the company for producing high quality beverage? 
### Task 2
Implement PCA and K-Means clustering on the given dataset.
\
PCA Implementation to visualize dataset - How much variance is explained by the first two principal components? Is the resultant plot a good representation of data?
\
Elbow Plot Creation - What does the elbow plot tell you about the number of clusters (K)? K-Means Implementation - What do you reckon are the correct number of clusters in the dataset?
