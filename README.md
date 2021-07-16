# Heart-Failure-Using-Clinical-Record-Set
In this project, we will develop and evaluate the performance and the predictive power of a model trained and tested on data collected from using academic performance data. The list of tasks below : 
1) Data Preparation and Exploration 
2) Data standardization 
3) Splitting the dataset into Train and Test (8:2 Combinations and use 10 –fold cross validation) 
4) Predict the accuracy of classifier and evaluate them. 
5) plot the graph 
6) Calculate the computational complexity of the model

# Source of dataset:
 Heart failure is a common event caused by CVDs and this dataset contains 12 features that can be used to predict mortality by heart failure.Most cardiovascular diseases can be prevented by addressing behavioural risk factors such as tobacco use, unhealthy diet and obesity, physical inactivity and harmful use of alcohol using population-wide strategies.People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.

Dataset link: https://www.kaggle.com/andrewmvd/heart-failure-clinical-data

Dataset features:
0   age                       299 non-null    float64
 1   anaemia                   299 non-null    int64  
 2   creatinine_phosphokinase  299 non-null    int64  
 3   diabetes                  299 non-null    int64  
 4   ejection_fraction         299 non-null    int64  
 5   high_blood_pressure       299 non-null    int64  
 6   platelets                 299 non-null    float64
 7   serum_creatinine          299 non-null    float64
 8   serum_sodium              299 non-null    int64  
 9   sex                       299 non-null    int64  
 10  smoking                   299 non-null    int64  
 11  time                      299 non-null    int64  
 12  DEATH_EVENT               299 non-null    int64  


# Data Preparation and Exploration 
Sex- Gender of patient Male=1,Female=0
Age-Age of patient

Diabetes- 0=No,1=Yes

Anaemia- 0=No,1=Yes

High_blood_pressure- 0=No,1=Yes

Smoking- 0=No,1=Yes

DEATH_EVENT- 0==No,1=Yes

# Data standardization
Data Standardization is a data processing workflow that converts the structure of disparate datasets into a Common Data Format. In this notebook , i have used standard scalar technique for standardization.
Heat map shows correlation between different features:
![image](https://user-images.githubusercontent.com/65977290/125961342-9ea8eb26-f8b6-45fa-a421-f44baeb06237.png)


# Splitting the dataset into Train and Test
I have split the dataset into 80:20 with 10 fold cross validation.

#  Predict the accuracy of classifier and evaluate them.

Different Regression Algorithm on dataset
![image](https://user-images.githubusercontent.com/65977290/125961433-0af1a0f4-9cb1-4f94-9359-dcd45d6a13ac.png)

Different Classifiacrion Algorithm on dataset

![image](https://user-images.githubusercontent.com/65977290/125961741-e74e0a18-efe6-42f2-972c-f8d0a5f40a08.png)

# Calculate the computational complexity of the model

For regrssion:
Time complexity of different model:

![image](https://user-images.githubusercontent.com/65977290/125961842-031f7b7e-26ff-4d65-894c-cdf9f6af14f2.png)

for classifiaction:
Time complexity of different model:
![image](https://user-images.githubusercontent.com/65977290/125961905-6eb683b8-a08e-47a6-b05d-e739b66bd2b3.png)





