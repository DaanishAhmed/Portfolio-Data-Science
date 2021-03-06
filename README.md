Daanish Ahmed's Data Science Portfolio
----------------

This portfolio contains some of the projects I have worked on while completing my M.S. in Data Analytics at the University of Maryland University College.  It showcases my experience using programs such as R, Python, SAS Enterprise Miner, SQL, and Tableau.  Many of these projects highlight multiple skills needed by data scientists, such as problem identification, data exploration, data cleaning, data sampling, building predictive models, comparing models, data storytelling (communication), creating visualizations, and providing solutions to business problems.  Some of these are group projects, for which they showcase my ability to effectively collaborate with others while developing data-driven solutions.


R
----------------

### Association Rules on Burn Injury Data

https://github.com/DaanishAhmed/R-Association-Rules

This project involves using R to examine a dataset containing information about burn victims. I analyzed the data to generate association rules, which offer insights about cases that frequently appear together. The goal is to understand some of the causes for certain burn cases and identify factors that influence burn severity.


### Logistic Regression on Heart Attack Data

https://github.com/DaanishAhmed/R-Regression

This project involves using R to examine a dataset containing information about heart attack cases. In my analysis, I generated a logistic regression model to predict the likelihood of a patient dying from a heart attack. I compared this model with a Naïve Bayes classification model to see which model is more accurate. The goal is to maximize the accuracy of my final model recommendation to ensure effective classification of heart attack cases.


### Decision Tree Classification on Bank Marketing Data

https://github.com/DaanishAhmed/R-Decision-Trees

This project involves the use of decision trees in R to examine a dataset containing bank marketing information. The goal is to determine the likelihood of a client subscribing to a term deposit. I implemented techniques such as oversampling and random forests to see if they improve the accuracy of my model.


### Neural Network Analysis on Heart Disease Data

https://github.com/DaanishAhmed/R-Neural-Network

This project involves using R to examine a dataset containing heart disease information. My analysis involves creating neural network models to predict a patient's vital status at the time of their last follow-up session (whether they are alive or dead). I will create three models and tune their parameters to produce the most accurate model possible.


### K-Means Clustering on Leaf Species Data

https://github.com/DaanishAhmed/R-Clustering

This project involves using R to examine a dataset containing leaf species information. My goal is to categorize leaf specimens into their correct species based on their characteristics. I will do this by using k-means clustering, an unsupervised classification method that finds shared characteristics between cases and groups them into appropriate clusters.


### [Group Project] Text Mining Analysis on President Donald Trump's Tweets

https://github.com/DaanishAhmed/R-Text-Mining-Group-Project

This is a group project where I collaborated with two other UMUC graduate students. The project is a text mining analysis where we analyzed the tweets sent by President (then candidate) Donald J. Trump during the 2016 presidential election. Our method involved finding terms that frequently appear together and determining the relationships between those words. We also used visualizations to determine the most prominent words and their significance. Our goal was to understand the important concepts and phrases of Trump's campaign and study what made his message resonate with voters.


### Text Mining Analysis on State of the Union Addresses

https://github.com/DaanishAhmed/R-Text-Mining-2

This project involves using R to perform a text mining analysis on the State of the Union addresses delivered each year between 1989 and 2017. The goal was to evaluate term frequencies and correlations between words to understand some of the most important issues facing the United States during this period. The project has similarities with the Text Mining Group Project on President Donald Trump's Tweets, since it involves methods such as word clouds and word association mining. However, it also incorporates additional approaches such as correlation plots and k-means clustering.


SAS Enterprise Miner
----------------

### Linear Regression on Vehicle Fuel Economy Data

https://github.com/DaanishAhmed/SAS-EM-Linear-Regression

This project involves using SAS Enterprise Miner to analyze a dataset containing vehicle fuel economy information. I will create several distinct linear regression models to predict the value of a vehicle's fuel economy. Each model will use different parameters and variable selection methods. I will then evaluate these models to determine which is the most accurate.


### Logistic Regression on Cellular Phone Company Churn Data

https://github.com/DaanishAhmed/SAS-EM-Logistic-Regression

This project involves using SAS Enterprise Miner to analyze a dataset containing customer churn information from a cellular phone company. I will create several distinct logistic regression models to predict whether a given customer will churn. Each model will use different parameters and variable selection methods. I will then evaluate the models to find not only the most accurate model, but also the one that can identify the highest number of churners. My goal is to create a model that can accurately identify likely churners and minimize financial losses for the company.


### Support Vector Machines on Vehicle Accident Data

https://github.com/DaanishAhmed/SAS-EM-SVM

This project involves building Support Vector Machines (SVMs) using SAS Enterprise Miner on a dataset containing vehicular accident information. SVM is a classification method that involves separating two or more classes of data. To achieve perfect or near-perfect classification, the data may need to be transformed using a kernel function. My analysis involves using several different kernel functions to see which is the most accurate. Additionally, I will determine which method is the most effective at identifying fatal accidents in particular.


### Bagging, Boosting, and Random Forests on Vehicle Purchase Data

https://github.com/DaanishAhmed/SAS-EM-Ensemble-Models-1

This project involves using SAS Enterprise Miner to analyze a dataset containing vehicle purchase information. In this analysis, I will use ensemble models, which combine distinct models and average their outputs. I will create bagging, boosting, gradient boosting, and random forest models--all of which are ensemble variants of the decision tree. My goal is to determine which of these methods is the most accurate, and which is most effective at classifying bad vehicle purchases.


### Heterogeneous Models on Vehicle Accident Data

https://github.com/DaanishAhmed/SAS-EM-Ensemble-Models-2

This project involves using SAS Enterprise Miner to analyze a dataset containing vehicular accident information. I will use ensemble models, which combine distinct models and average their outputs. Heterogeneous models combine different types of predictive models (such as regression, neural networks, and SVM). By experimenting with different combinations of ensemble and individual models, I will determine which method is the most accurate and which can identify the highest number of fatal accidents.


### Capstone Project on Storm Events Data (Using Tableau, R, and SAS EM)

https://github.com/DaanishAhmed/SAS-EM-Capstone-Project

This is my capstone project, and it involves using Tableau, R, and SAS Enterprise Miner to analyze three datasets containing storm information from NOAA and the NWS during the year 2017. The project focuses on predicting the likelihood that a storm will produce fatalities. It involves using SAS EM to build five types of predictive models: logistic regression, neural network, support vector machine (SVM), random forest, and heterogeneous ensemble model. By experimenting with different types of models, I will select the method that can identify the highest number of storm casualties. Additionally, I use Tableau to create visualizations exploring the relationship between storm casualties, geographic location, and time of year. This helps to determine which states have the highest risk of casualties, and which months of the year are more likely to experience dangerous storms. Lastly, I use R to conduct a text mining analysis on the storm event narratives. I will create a word cloud that showcases the most frequent terms used to describe dangerous storms, which is helpful for gaining insights about these storms' characteristics.


Python
----------------

### Text Mining Analysis on Film Reviews (Using Python and Tableau)

https://github.com/DaanishAhmed/Python-Tableau-Text-Mining

This project involves using Python to analyze five film review texts written between 1934 and 2014. My goal is to perform a text analysis on these reviews to study how critics' word choices changed over time. I created a Python script that returns the 30 most common words in each document and how often those words appeared. The program filters out stop words (such as "and," "like," and "but"), removes punctuation, and handles stemming (i.e. words such as "write" and "writing" are listed as the same word). After running the program on all five reviews, I combined the results into a single spreadsheet and examined them using visualizations in Tableau. I used these visualizations to study whether these word choices reflect audiences' changing tastes in films over time.


SQL
----------------

### Querying and ERD Design on Airlines Data

https://github.com/DaanishAhmed/SQL-ERD-Querying-Project

This is a simple SQL project that showcases querying on an airlines dataset. It showcases queries such as select statement variations, inserting and removing data, manipulating records in tables, join statements, ordering and grouping, variable creation, filtering, and querying by date. The project contains 10 problems, which are all included in the file "Airlines Querying Exercise.xlsx".


### [Group Project] Extract, Transform, and Load (ETL) on Company Product Order Data

https://github.com/DaanishAhmed/SQL-ETL-Group-Project

This is a group project where I collaborated with two other UMUC graduate students. The project involves using SQL code to create an Extract, Transform, and Load (ETL) sequence on three separate product order datasets from 2012, 2013, and 2014. The goal is to combine these three files into a single spreadsheet so it can be loaded into our organization's new data mart.


Tableau
----------------

### [Video] Time Series Analysis on Countries Through Time

https://github.com/DaanishAhmed/Tableau-Time-Series-Presentation

This presentation was made using Tableau software, and it involves analyzing the Gross Domestic Product (GDP), life expectancy, and child mortality rate of five countries between 1960 and 2015. The data was collected from the United Nations for the following countries: the United States, China, Sweden, the Philippines, and Afghanistan. The goal is to determine the existence and strength of any relationship between GDP and life expectancy or mortality rate. Additionally, I used time series analysis to predict each country's life expectancy, mortality rate, and GDP up to the year 2020 and studied whether those predictions were reliable.


Spark
----------------

### Logistic Regression on Titanic and Low Birth Weight Data

https://github.com/DaanishAhmed/Spark-Logistic-Regression

This project involves using Spark to create predictive models for analyzing two datasets: a Titanic survivors dataset, and a low birth weight infants dataset. The first part of the analysis involves using logistic regression and Naive Bayes to categorize Titanic victims based on whether they survived. The second part of the analysis involves using logistic regression, Naive Bayes, and decision trees to predict whether babies will be born with low birth weight. In this part, I will evaluate each model's performance to determine which technique is most effective for this dataset.


Db2 Warehouse on Cloud
----------------

### Sentiment Analysis on Claritin Side Effects Twitter Data (Using SQL and R)

https://github.com/DaanishAhmed/Db2-Warehouse-Sentiment-Analysis

This project utilizes IBM's Db2 Warehouse on Cloud service to analyze a Twitter dataset on user sentiment towards Claritin. The goal of the analysis is to determine which factors (such as gender or current symptoms) contribute the most towards low user sentiment. The first component of the analysis involves loading the data into the warehouse and performing exploratory data analysis using SQL. The rest of the project consists of analyzing the data in R. Some of the methods include pie charts, bar graphs, logistic regression, word clouds, k-means clustering, and hierarchical clustering.


Watson Analytics
----------------

### Exploratory Data Analysis on Employee Attrition Data

https://github.com/DaanishAhmed/Watson-Analytics-Exploratory-Analysis

This project involves the use of Watson Analytics to analyze a dataset containing employee attrition information. My goal is to conduct an exploratory data analysis (EDA) to understand the trends and relationships between variables in the data. I do this by creating visualizations and dashboards that explore the connections between important variables. The results should offer some insights regarding the causes of employee attrition.


### Decision Tree Analysis on Categorical and Continuous Data

https://github.com/DaanishAhmed/Watson-Analytics-Decision-Trees

This project involves the use of Watson Analytics to analyze two datasets: a customer churn dataset with a categorical target, and a sales profits and costs dataset with a continuous target. I used decision trees to classify the outcomes for both datasets. My goal in the churn dataset is to predict whether a customer will churn, whereas my goal in the sales dataset is to maximize the gross profit. I then evaluated whether the solutions provided by the decision trees were attainable by my organization.


### Display Development on Employee Attrition and Sales Data

https://github.com/DaanishAhmed/Watson-Analytics-Display-Development

This project involves the use of Watson Analytics to analyze two datasets: an employee attrition dataset and a sales profits and costs dataset. My goal is to analyze these datasets using visualizations and see how the results can help my company. I will then communicate my findings using displays and storybooks. Additionally, I will incorporate social media data from Twitter that is relevant to my two datasets. I will explore and present this data in visual format to provide useful insights for my organization.


### Complete Data Analysis on Vehicle Accident Data

https://github.com/DaanishAhmed/Watson-Analytics-Complete-Analysis

This project involves the use of Watson Analytics to analyze a dataset containing vehicle accident information. In my analysis, I explored the data using an exploratory data analysis (EDA), leveraged visualizations, built decision trees to classify accident severity, communicated my findings using dashboards and storybooks, and implemented social media data to enhance my findings.


Watson Conversation
----------------

### Chatbot Implementation on Ice Cream Shop Transactions

https://github.com/DaanishAhmed/Watson-Conversation-Chatbot

This project involves using IBM Watson Conversation to build a chatbot that manages an online store for a fictional ice cream shop. The goal of the chatbot is to process transactions and answer user questions about products, order methods, or store locations. The chatbot is designed to simulate a more human level of transaction, which it achieves by remembering the user's name, storing their existing order information, and using variations of each response. The bot allows for the user to order online or visit a physical store. If the user wants to shop online, the bot will ask for their order, compute the order price, and ask for order confirmation. If the user wants to visit an actual store, the bot will ask for their state of residence and list all open locations in that state.


DecisionsFirst
----------------

### Decision Requirements Analysis on Customer Loyalty Programs

https://github.com/DaanishAhmed/DecisionsFirst-Decision-Requirements

This project involves using DecisionsFirst software to frame the decision making process for a retail company regarding its customer loyalty program. My goal is to create a Decision Requirements Diagram (DRD) that focuses on determining which reward to offer a customer. In my analysis, I break down the factors that contribute towards making this decision--such as sub-decisions, requirements for each decision, and policies that dictate each decision. Finally, I propose solutions on how to maximize the effectiveness of my organization's customer loyalty program.

