# Human Activity Recognition with Smartphones
## Overview
This project utilizes machine learning to classify human activities based on smartphone sensor data. Using a dataset collected from 30 volunteers performing activities ranging from static postures to dynamic movements, we employ various algorithms to accurately identify the activity type.

## Dataset
The dataset comprises 3-axial linear acceleration and 3-axial angular velocity data captured at a 50Hz sampling rate from a Samsung Galaxy S II smartphone worn by the subjects. Activities include six basic types, alongside postural transitions.

## Technologies Used
 **Programming Languages:** Python
- **Key Libraries:** 
  - NumPy
  - pandas
  - Matplotlib
  - seaborn
  - scikit-learn
  - statsmodels
  - ydata_profiling
- **Machine Learning Models:**
  - Random Forest
  - XGBoost
  - Linear SVM
  - KNN
  - Voting Classifier

# Loading the dataset
df_test = pd.read_csv('activity_test.csv')
df_train = pd.read_csv('activity_train.csv')

# Basic dataset information
df_train.info()
Feature Engineering
A comprehensive feature set is extracted using time and frequency domain variables, applying noise filters, and separating the acceleration signal into body and gravity components.

Model Training and Evaluation
We employ RandomForestClassifier for the initial model training, followed by PCA for feature dimensionality reduction. Model performance is evaluated using accuracy, precision, and recall metrics, supplemented by confusion matrix visualization.

Analysis and Results
The project includes an in-depth analysis of model performance, highlighting the importance of feature engineering and selection in improving classification accuracy.

Contributions
This project is open for contributions. Please refer to the contribution guidelines before making a pull request.

