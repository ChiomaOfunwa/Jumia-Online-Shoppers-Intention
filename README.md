# Jumia-Online-Shoppers-Intention
Data Analytics Journey Task2

**ONLINE SHOPPERS’ INTENTION PREDICTION USING MACHINE LEARNING* 

**# OVERVIEW**

Predicting Online Shopper’s Intention is the goal for this project to help Jumia get insightful knowledge on the intentions of their customers which will in turn help their business grow by knowing their customer status, interest, and their purchase intention.
Machine Learning is a powerful tool for data prediction, and it has been widely used in various industries, such as finance, healthcare, and marketing.
Machine Learning Involves processes to get accurate results, from Data collection to cleaning, preprocessing, model selection, training, evaluation then deployment.

**# OBJECTIVE**

The data used in this analysis is an Online Shoppers Purchasing Intention data set provided by a top e-commerce site. The data set was formed so that each session would belong to a different user in a 1-year period to avoid any tendency to a specific campaign, special day, user profile, or period.
The primary purpose of the data set is to predict the purchasing intentions of a visitor to this particular store’s website. This dataset has very few missing values and all features of the dataset are relevant to the purchasing intention based on inference.

**# RESOURCES**

•	Data Source: 10alytics Data Bank

•	Tool: Google Colab

•	Package: Pandas, Numpy, Seaborn, Matplotlib, and Machine Learning Algorithms

**# DATASET FEATURES DESCRIPTIONS**

Administrative: This is the number of pages of this type (administrative) that the user visited.

Administrative_Duration: This is the amount of time spent in this category of pages.

Informational: This is the number of pages of this type (informational) that the user visited.

Informational_Duration: This is the amount of time spent in this category of pages.

ProductRelated: This is the number of pages of this type (product related) that the user visited.

ProductRelated_Duration: This is the amount of time spent in this category of pages.

BounceRates: The percentage of visitors who enter the website through that page and exit without triggering any additional tasks.

ExitRates: The percentage of pageviews on the website that ends at that specific page.

PageValues: The average value of the page averaged over the value of the target page and/or the completion of an eCommerce transaction.

SpecialDay: This value represents the closeness of the browsing date to special days or holidays (eg Mother's Day or Valentine's day) in which the transaction is more likely to be finalized. 

Month: Contains the month the pageview occurred, in string form.

OperatingSystems: An integer value representing the operating system that the user was on when viewing the page.

Browser: An integer value representing the browser that the user was using to view the page.

Region: An integer value representing which region the user is located in.

TrafficType: An integer value representing what type of traffic the user is categorized into.

VisitorType: A string representing whether a visitor is a New Visitor, Returning Visitor, or Other.

Weekend: A boolean representing whether the session is on a weekend.

Revenue: A boolean representing whether or not the user completed the purchase.

**# STEPS TAKEN**

DATA COLLECTION: I collected the data with the use of the pandas’ tool.

DATA PREPROCESSING: This includes data cleaning and EDA.

Some duplicate values found were dropped, analysis and visualization of features of the dataset was carried out.

This helped understand the data structure and distribution before modeling.

Correlation of all features was also carried out to show the relationship between the features and see the best fit in terms of their relationship.

Some of the graphical representation of the Exploration done on the data frame.

 ![Screenshot 2023-04-25 150555](https://user-images.githubusercontent.com/125756661/234339939-6118f120-db7a-47c6-b9dd-3f19534bfa5e.png)

![Screenshot 2023-04-25 150631](https://user-images.githubusercontent.com/125756661/234340400-70df5fd8-24f7-4992-b4b8-6f28c7f74a81.png)

 ![Screenshot 2023-04-25 150701](https://user-images.githubusercontent.com/125756661/234340438-478f7883-422a-4cf7-8e9a-69fe71237d94.png)

![Screenshot 2023-04-25 153236](https://user-images.githubusercontent.com/125756661/234340490-d9356c95-43b6-4170-9bf7-d67549651692.png)

Data Encoding and scaling were performed on some of the features.

MODELLING AND EVALUATION: This involved the splitting of the dataset into the test and train model, also identifying the target.

Machine learning Algorithms were used to evaluate the model. These algorithms are the Naïve Bayes model, Decision Tree, and Logistics Regression to evaluate the model.

**# CHALLENGES**

The dataset has very few missing values and duplicate values which had to be dropped during the cleaning. This could have influenced the accuracy of the result.

**# SUMMARY/CONCLUSIONS**

From the exploratory Data Analysis and machine learning algorithms used for modeling and evaluation, some insights were drawn.

•	Visitors visit more during the weekend than the weekdays.

•	There are no specialdays effect on the visitors.

•	More returning visitors to the website with a percentage of 85%, however, these returning visitors are more for the Informational and Product-Related features as the administrative feature has higher new visitors.

•	Although returning visitors are higher than new visitors yet new visitors tend to purchase more than returning visitors.

•	Only 15% of the total visitors to the website led to purchases of which new visitors’ input was higher than that of the returning visitors.

•	After the evaluation, the naïve Bayes algorithm prove to be the most accurate to be used with a 74% accuracy score and 93% precision score.


