# HR-Analytics-Job-Change-of-Data-Scientists
predict the probability of a candidate to look for a new job or will work for the company, as well as interpreting affected factors on employee decision.

# Introduction
For this project, I used a standard imbalanced machine learning dataset referred to as the “HR Analytics: Job Change of Data Scientists” dataset. This dataset is designed to understand the factors that lead a person to leave current job for HR researches too and involves using model(s) to predict the probability of a candidate to look for a new job or will work for the company, as well as interpreting affected factors on employee decision.

# Data Source.
I got my data for this project from kaggle. Here is the link: https://www.kaggle.com/datasets/arashnic/hr-analytics-job-change-of-data-scientists

# Dataset description
The whole data is divided into train and test. Target isn't included in test but the test target values data file is in hands for related tasks. The dataset is imbalanced and most features are categorical (Nominal, Ordinal, Binary), some with high cardinality. 

#EDA
And some of the insights I could get from the analysis include:

1. The number of men is higher than the women and others.
2. There are more than 70% people with relevant experience.
3. There are around 73% of people with no university enrollment.
4. 60% of people are graduates.
5. The number of STEMs is quite high compared to others. When creating our model, it may override others because it occupies 88% of total major discipline.
6. 75% of people's current employer are Pvt. Ltd.

#Feature Engineering
Prior to modeling, it is essential to encode all categorical features (both the target feature and the descriptive features) into a set of numerical features. So I performed Label Encoding to convert these features into a numeric form. This dataset contains a typical example of class imbalance, This problem is handled using SMOTE (Synthetic Minority Oversampling Technique).
 
#Machine Learning Classifiers
I used seven different type of classification models for this project and after modelling the best is the XG Boost model.




