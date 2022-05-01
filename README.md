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
- Comparison of models performance in terms of the following criteria: precision, recall, accuracy, and F-measure.
- In all terms, XGB model was able to achieve the highest values.

**Abbreviations**:
    
>**EHV:** Ensemble Hard Voting

>**ESV:** Ensemble Soft Voting

>**ANN:** Artificial Neural Network

>**XGB:** Extreme Gradient Boosting

>**RFC:** Random Forest Classifier


![image](https://user-images.githubusercontent.com/89004966/166134833-31f518c9-28c7-4579-89fb-be1872601c05.png)

![image](https://user-images.githubusercontent.com/89004966/166134836-018db7a5-4c67-4931-8792-0665740f249a.png)

![image](https://user-images.githubusercontent.com/89004966/166134839-60c2266b-9608-46bf-8a33-2c561ce4d15e.png)

![image](https://user-images.githubusercontent.com/89004966/166134841-c1da838f-8229-4e6c-8c36-82e029d33748.png)

![image](https://user-images.githubusercontent.com/89004966/166134846-1d3cc785-cc68-4697-b0a8-6d61c450f015.png)







