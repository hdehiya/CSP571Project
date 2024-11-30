# CSP571Project

# Group Details:
Group Number 10
Group Members:
1. Merlin Santano Simoes (A20531255)
2. Harneet Kaur Dehiya (A20548613)
3. Sana Samad (A20543001)
4. Owaiz Majoriya (A20546104)
5. Belthangady Akash V Narayana Pai (A20560317)

# Description:
This project involved data analysis and classification using the Adult Dataset from the UCI Machine Learning Repository. The objective is to predict whether an individual's income exceeds $50,000 based on various demographic and work-related attributes.  
The dataset contains approximately 48,000 observations and 14 features for a sample of the US population of adults. The demographic attributes in this dataset include age, educational attainment, and occupation, while financial variables pertain to capital gains/losses and hours worked per week. 

# Requirements:
In order to run the files in this project, the following packages are required:  
ucimlrepo, pandas, numpy, seaborn, matplotlib, scikit-learn, scipy, xgboost, umap-learn, tensorflow, keras, keras_tuner

# Loading the data:
The dataset can be loaded using the following:

from ucimlrepo import fetch_ucirepo  
adult = fetch_ucirepo(id=2)  
X = adult.data.features  
y = adult.data.targets  

The dataset is also available in this repository in case the above method does not work.

# Running the files:
Python 3 is required to run the code.

i. RandomForest.ipynb: Data analysis including Correlation Matrix, Independence Between Feature, PCA, t-SNE, UMAP along with Random Forest Classifier implementation  
ii. Gradient_Boosting.ipynb: Train XGBoost model with hyperparameter tuning using GridSearch and find importance of features  
iii. Hierarchical_clustering.ipynb: Unsupervised learning using hierarchical clustering to find clusters  
iv. Kmeans_clustering.ipynb: Implements KMeans clustering using the elbow and silouette method to find the optimal number of clusters  
v. Neural_Network.ipynb: Implements Neural Network model with dropout and early stopping to avoid overfitting. 
