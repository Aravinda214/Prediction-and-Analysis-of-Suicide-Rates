# Prediction-and-Analysis-of-Suicide-Rates

# Abstract and Scope of the Project

In this digital age, the pressure to perform and succeed can often lead to depression and, in extreme cases, death. Suicide is defined as the deliberate act of causing one's death. They are increasing at an alarming rate all over the world, and it is important to reduce the number of suicides taking place. Suicide attempts have serious emotional, physical, and financial ramifications. Although a single factor cannot be pinpointed, among the common factors leading towards taking the extreme step, some of them can be analyzed through this project. A visualization of these could give us a better understanding of the causes of their suicide. A prediction plot of the overall rate of suicides in the future years is found using regression algorithms. A culminated model was created to predict the total count of suicide based on various factors including state, age group, and Year. These results would be helpful to reduce the number of suicide rates in the world and create awareness among people. 

## Steps to Run the Application

Download the repository and extract it.
<br>
Open ```ui.R``` and ```server.r``` in your local Rstudio application. A ```Run App``` option will be displayed. Click on that to execute the shiny dashboard.

## Data Source

Link: https://www.kaggle.com/rajanand/suicides-in-india

## Language 
The ```R``` language was used to perform Data Analytics and Machine Learning. ```R Markdown``` is used for knitting the file into Html

## Tools
->R studio <br>
->Plotly <br>
->Ggplot 2


## Techniques
->Dataset Cleaning <br>
->Data Visualization <br>
->Data Analysis <br>
->Machine Learning <br>

# Proposed Methodology

-> Support Vector Machine 
The Support Vector Machine (SVM) is a supervised learning technology that is used to handle classification and regression issues. The SVM algorithm's goal is to identify the best line or decision boundary for dividing n-dimensional space into classes so that additional data points may be easily placed in the proper category in the future. A hyperplane, also called the best decision boundary.

-> Linear Regression
Linear regression is a supervised learning machine learning technique. It performs a regression task. Regression models provide a goal prediction value based on independent variables. It is mostly utilized in predicting and finding correlations between variables.


-> Multi Linear Regression
It is a statistical technique that uses multiple predictor variables to formulate a final target answer. This algorithm's purpose is to simulate the linear relationship between the independent and dependent variables

-> Lasso Regression
Logistic regression is a statistical analysis approach for predicting a data value based on previous data set observations. In the area of machine learning, logistic regression has become an important tool. The technique helps a machine learning application to classify incoming data using an algorithm based on historical data. 

-> Logistic regression
 It is a classification algorithm that uses shrinkage in simple models, including models with fewer parameters. During this procedure, the data values are shrunk towards a center point, similar to a mean.

# Proposed System

![image](https://user-images.githubusercontent.com/65520755/149009157-d7014ad6-7e35-4562-b9c5-855df382c81a.png)

# Snippets of the Shiny Dashboard

![image](https://user-images.githubusercontent.com/61049979/149012752-e079f6b1-56c5-40ef-bdd1-92e1cfa4ad1e.png)

![image](https://user-images.githubusercontent.com/61049979/149012788-835e1ab3-20a5-43f0-b157-b1fee70d7a50.png)

![image](https://user-images.githubusercontent.com/61049979/149012838-a80fc1bc-75de-4697-bcea-94fe0e6ee904.png)

![image](https://user-images.githubusercontent.com/61049979/149012877-62d84d83-e89e-427f-8f05-c31df883e54d.png)

![image](https://user-images.githubusercontent.com/61049979/149013165-bc518327-923d-48f8-af7c-154648ee6da8.png)


# Conclusion 

i) Various machine learning models were implemented and arrived at the following conclusions by looking at the results and visualization. The number of suicide cases are escalating year by year. A cause of concern observed during data cleaning is that many suicides are unclassified. <br>
ii) Males tend to end their lives as compared to females. <br>
ii) People belonging to the age group of 15-44 constitute for most suicide cases. <br>
iv) Maharashtra, Andhra Pradesh and West Bengal are the states having the most number of suicides in India. <br>
v) The major factors include family problems, prolonged illness, and insanity. <br>
vi) Education is an essential factor in combating suicide, as with increase in education level, the suicide count drops. <br>

The culminated machine learning model indicates that the suicide count varies based on state and age group, but the factor that remains constant is that the suicide count is predicted to go higher and higher every year. Hence immediate actions have to be taken to bring awareness to the general public about mental health issues, ensure that they stay in a healthy state of mind and are able to stay strong when faced with problems so that they never consider the act of suicide.


