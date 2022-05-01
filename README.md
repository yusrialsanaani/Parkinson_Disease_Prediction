# Parkinson Disease Prediction
The goal of this project is to predict the Parkinson's Disease using different machine learning algorithms and then compare thier performance using different classification metrics.
## Libraries used:
- NumPy, Panadas, matplptlib, seaborn
- sklearn
- Keras/Tensorflow
- mlxtend
- xgboot

## Dataset
The dataset used in this project is Parkinsons Data Set taken from https://archive.ics.uci.edu/ml/datasets/parkinsons.
- This dataset is based on voice measures in frequency. 
- It was produced and released by the University of Oxford, available in the UCI ML Repository. 
- The dataset consists of 22 features and 1 result column of the diagnosis. 
- There are a total of 195 rows. Moreover, the dataset has been created from a measure of dysphonia and pitch period entropy.


## Exploratory Data Analysis (EDA)
- Univariate Analysis 
  - Histogram & Boxplot
- Bivariate analysis
- Maultivariate analysis
  - Correlations between all the features.
## Data Preprocessing and Feature Engineering:
- Check and treat the null and missing values and treatment them.
- Check and treat the duplicates.
- Check and treat the outliers using Inter-Quartile Range (IQR).
- Check class imbalance and treat it using oversampling technique.
- Normalize the dataset.
- Encode the categorical variables if exist.
## Model Development
- **Machine Learning Algorithms**:
  - KNN (K-Nearest Neighbours)
  - Support vector machines (SVM)
  - Decision Tree (DT)
  - XGboost classifiers
  - Ensemble Method:
    - Ensemble Hard Voting (EHV)
    - Ensemble Soft Voting (ESV) using a majority voting approach to predict class label using KNN (k=5), SVM (kernel = rbf), DT (with optimal tree), and XGboost classifiers based on a soft voting.
- **Artificial Neural network**

## Models Evaluation and Comparison
Comparison of models performance in terms of the following criteria: precision, recall, accuracy, and F-measure.

![image](https://user-images.githubusercontent.com/89004966/166133710-58d69269-622f-45f8-87dc-3a46ad2445e4.png)

![image](https://user-images.githubusercontent.com/89004966/166133712-bf2282f7-6ddd-4e08-8793-7b4da4d979c1.png)

![image](https://user-images.githubusercontent.com/89004966/166133716-e37634d9-fe0b-4f03-95a2-8f279dc7a00a.png)

![image](https://user-images.githubusercontent.com/89004966/166133717-f4cf2a62-e251-4fa2-9808-1f061157ea30.png)

![image](https://user-images.githubusercontent.com/89004966/166133719-1ed16a7f-c239-4b0d-9b40-16dfa5ba7c6b.png)






