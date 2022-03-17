# Compilation of Projects

## Project: Machine-Learning---Regression-Analysis--Medical-Insurance Dataset

**Business Understanding**
The business under review is a Medical insurance company which is faced with the challenge of proper estimation of medical expenses that is caused by the diverse health conditions of its payees as some conditions are more common within some segments of its population. The objective of this business is to accurately forecast the medical expenses of its payees so that the right annual premium can be collected based on their health conditions. The aim is to answer three major business questions which are: 
•	How does the smoking lifestyle of an individual affect the cost of their healthcare
•	Does the number of Children covered by health individual affect their Medical expenses?
•	How accurately can the given factors estimate an individual’s medical expenses?


**Data Understanding** 
the dataset to be analysed is a CSV file of medical insurance dataset alongside the application of the CRISP-DM methodology while the tool being used for this task is the Python’s Jupyter Notebook because of its ease of use and simplicity. The goal of this analysis is to build a prediction model to predict with an acceptable level of accuracy, the medical cost for individuals based on their Age, BMI, number of children covered, if Smoking or not and their Region of domiciliation in the US. 
The medical insurance dataset has 1338 observations, 6 predictors which are the age, bmi, children, smoker_yes, smoker_no, and region and one dependent variable – medical cost. This is a supervised machine learning task because the target variable to be predicted is being provided which is medical cost (y label) and the best use in this analysis is the linear regression because the outcome is a numerical and a continuous variable. In this analysis, the correlation between each predictor and the medical cost would be studied, the correlation analysis would be used to select 3 best predictors to build a simple linear regression model for each predictor. The performance of the R2 would be evaluated and hypothesis testing would be used to evaluate the statistical significance of the results. Two multivariate regression models would be built using the three best predictors and all the predictors in the dataset with the dataset, then the two models would be compared and evaluated. The Polynomial regression would be applied and the result would be evaluated in terms of performance improvement.

## Project: Machine learning-Classification Model---Census Income
**Business Understanding**
The objective of the Census Bureau is to use attributes like an individual’s age, work-class, education, level of education, marital-status, occupation, relationship, biological sex, capital loss, capital gain, hours they work per week, native country, and the number of people the entry presents to determine if an adult earns more or less than $50,000 a year. 

**Data Understanding**
The dataset is the census income dataset from the census bureau, available from the UCI machine learning Repository. The objective of this analysis is to build a classification model that would predict if an adult would more than $50,000 a year or not based on a number of attributes.
The attributes are age, work class, final weight (fnlwgt), education, education-num, marital status, occupation, relationship, sex, capital-gain, capital-loss, hours-per-week and native-country which are the input variables (X) and income as the output variable (Y).
This data analysis is being done the tool for this task is the Python’s Jupyter Notebook which is simple to use and allowing for the easy building of machine learning models. This is a supervised machine learning task because the labels are known and classification is being used because the labels are discrete and already assigned to a class. Five classification models would be used for these analysis and they are the K’s nearest neighbour (KNN), Support Vector Machine, Decision Tree, Logistics Regression, Neural Networks and Logistic Regression.  The model would be evaluated using the 60%, 40% single split and the Kfold validation with K=5. The features would also be ranked using the feature ranking with recursive feature ranking with recursive feature elimination algorithm with a goal of identifying the optimal features. The investigations would firstly be done using all the features without selection, then with feature selection based on the findings. 


## Project: Applied Data Analysis and Visualization of Offences in the UK for 2014 and 2015

* Downloaded, refined and integrated datasets from a twenty-four month period of Crown Prosecution Service Case Outcomes by Principal Offence Categoryfrom the data.gov.uk website (link: https://data.gov.uk/dataset/89d0aef9-e2f9-4d1a-b779-5a33707c5f2c/crown-prosecution-service-case-outcomes-by-principal-offence-category-data).

* With the use of Python, data analytics tools and techniques related to descriptive and predictive analytics were applied on the integrated dataset, a prediction model using one linear regression technique, one clustering technique and one classification technique were developed.

* Prepared a report containing: a.Definition of, at least, two different hypothesis based on the currentdataset; b. Explained and justified cleaning / integration techniques used in the dataset; c. Analysed and interpretated results using descriptive analytics; d.Implemented a prediction model using one linear regression technique, one clustering technique and one classification technique; e. Critically reviewed the data analytics tools and techniques used. Analysed the effectiveness of the techniques used, discussed alternative solutions and compare strengths and weakness between them; f. Critically reviewed the visualisation tools used, analysed the effectiveness of the visualisation tools used, discussed alternative solutions and compared strengths and weakness between them.

## Project: Business Case Study
## Customer Acquisition and Retention improvement Using Data Analysis Techniques

* Chose four data analysis techniques (Data Collection, Data Processing, Data Cleaning and Data Management), analysed and evaluated them.

* Discussed the theoretical aspect of these techniques and the tools that can be used

* Critically analysed and evaluate the applications of these techniques

* Reviewed the available commercial and open-source data analysis software appropriate for the business issues.

* Selected a business case with the data analysis requirements, synthesised a plan for addressing the probelms with the suggestions of the technique and the available software.
