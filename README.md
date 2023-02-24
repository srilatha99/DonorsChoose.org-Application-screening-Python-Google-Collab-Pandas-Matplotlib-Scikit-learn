# DonorsChoose.org-Application-screening-Python-Google-Collab-Pandas-Matplotlib-Scikit-learn
Built a model that uses classification to determine if the project can be offered funding. Automated the process of screening large number of applications received by DonorsChoose.org using classification. Used KNN, Naive Bayes and Linear Regression classifiers for the model and the dataset used is from Kaggle.

1. Business Understanding
DonorsChoose.org receives a number of project proposals each year for classroom projects that are 
in need of funding. Right now, we need a large number of volunteers. These volunteers must manually 
screen each submission before it's approved to be posted on the DonorsChoose.org website. Next 
year there will be around 500,000 applications that need to be screened manually. It is not 
economically scalable to hire all these volunteers and screen the projects manually. 

1.1 Business problem
We have three major problems that we need to resolve. 
• We must scale the current manual process and the resources. We must automate the 
entire process so that the projects can be screened quickly and efficiently so that they can 
be posted on DonorsChoose.org as soon as possible.
• We must increase the consistency of the project vetting across different volunteers to 
improve the experience for teachers
• We need to focus the energy of the volunteers on the applications that need the most 
assistance. 

1.2 Dataset: 
• The dataset we used to predict whether a DonorsChoose.org project proposal submitted 
by a teacher will be approved is from Kaggle.
• We are using two data sets which we will be using together for our project. Train.csv and 
resources.csv. There are 15 descriptive features in train.csv and 3 descriptive features 
resources.csv. Many projects require multiple resources. The ‘id’ value in resources.csv 
corresponds to ‘project_id’ in train.csv and it will be used as a key to retrieve resources. 
• There are a total of 109248 rows in our dataset
• ‘project_is_approved’ attribute is our target variable

1.3 Proposed Analytics Solution
We plan on applying three different classifiers to our proposed project namely K-Nearest 
Neighbor classifier, Naïve Bayes Classifier, Linear regression classifier. After training the data with 
all the three classifiers we will then choose the one that has highest accuracy for our data. 

2. Data Exploration and Preprocessing

2.1 Data quality Report
The dataset that we chose has 17 features out of which 3 of them are Continuous and 14 of them 
are Categorical. Most of these categorical features are string data type and some are nominal 
data scale and some of them are ordinal data scale. 2 out of 3 continuous features have int data 
type and one is float datatype
