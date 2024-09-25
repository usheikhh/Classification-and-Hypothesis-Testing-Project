# ExtraaLearn Project

## Context

The EdTech industry has been surging in the past decade immensely, and according to a forecast, the Online Education market would be worth $286.62bn by 2023 with a compound annual growth rate (CAGR) of 10.26% from 2018 to 2023. The modern era of online education has enforced a lot in its growth and expansion beyond any limit. Due to having many dominant features like ease of information sharing, personalized learning experience, transparency of assessment, etc, it is now preferable to traditional education. 

In the present scenario due to the Covid-19, the online education sector has witnessed rapid growth and is attracting a lot of new customers. Due to this rapid growth, many new companies have emerged in this industry. With the availability and ease of use of digital marketing resources, companies can reach out to a wider audience with their offerings. The customers who show interest in these offerings are termed as leads. There are various sources of obtaining leads for Edtech companies, like

* The customer interacts with the marketing front on social media or other online platforms. 
* The customer browses the website/app and downloads the brochure
* The customer connects through emails for more information.

The company then nurtures these leads and tries to convert them to paid customers. For this, the representative from the organization connects with the lead on call or through email to share further details.

## Objective


ExtraaLearn is an initial stage startup that offers programs on cutting-edge technologies to students and professionals to help them upskill/reskill. With a large number of leads being generated on a regular basis, one of the issues faced by ExtraaLearn is to identify which of the leads are more likely to convert so that they can allocate resources accordingly. You, as a data scientist at ExtraaLearn, have been provided the leads data to:
* Analyze and build an ML model to help identify which leads are more likely to convert to paid customers, 
* Find the factors driving the lead conversion process
* Create a profile of the leads which are likely to convert


## Data Description

The data contains the different attributes of leads and their interaction details with ExtraaLearn. The detailed data dictionary is given below.


**Data Dictionary**
* ID: ID of the lead
* age: Age of the lead
* current_occupation: Current occupation of the lead. Values include 'Professional','Unemployed',and 'Student'
* first_interaction: How did the lead first interacted with ExtraaLearn. Values include 'Website', 'Mobile App'
* profile_completed: What percentage of profile has been filled by the lead on the website/mobile app. Values include Low - (0-50%), Medium - (50-75%), High (75-100%)
* website_visits: How many times has a lead visited the website
* time_spent_on_website: Total time spent on the website
* page_views_per_visit: Average number of pages on the website viewed during the visits.
* last_activity: Last interaction between the lead and ExtraaLearn. 
    * Email Activity: Seeking for details about program through email, Representative shared information with lead like brochure of program , etc 
    * Phone Activity: Had a Phone Conversation with representative, Had conversation over SMS with representative, etc
    * Website Activity: Interacted on live chat with representative, Updated profile on website, etc

* print_media_type1: Flag indicating whether the lead had seen the ad of ExtraaLearn in the Newspaper.
* print_media_type2: Flag indicating whether the lead had seen the ad of ExtraaLearn in the Magazine.
* digital_media: Flag indicating whether the lead had seen the ad of ExtraaLearn on the digital platforms.
* educational_channels: Flag indicating whether the lead had heard about ExtraaLearn in the education channels like online forums, discussion threads, educational websites, etc.
* referral: Flag indicating whether the lead had heard about ExtraaLearn through reference.
* status: Flag indicating whether the lead was converted to a paid customer or not.


**Content**
* Exploratory Data Analysis
    * Univariate analysis 
    * Bivariate analysis 
    * Comments on the visualization such as range of attributes, outliers of various attributes. 
    * Comments on the distribution of the variables 
    * Observations on individual variables and the relationship between variables

* Data Pre-Processing
    * Prepared the data for modelling 
    * Dropping insignificant variables 
    * Missing value Treatment 
    * Outlier Detection
    * Feature Engineering
    * Data split

* Model Building - Decision Tree
    * Built the model and commenedt on the model performance

* Model Performance evaluation and improvement
    * Tuned the model hyperparameters using GridSearchCV 
    * Evaluate the model based on appropriate metric 
    * Commented on model performance 
    * Checked the Feature Importance 
    * Commented on important features

* Model Building - Random Forest
    * Built the model and commented on the model performance

* Model Performance Evaluation
    * Tuned the model hyperparameters using GridSearchCV 
    * Evaluate the model based on appropriate metric 
    * Commented on model performance 
    * Checked the Feature Importance 
    * Commented on important features


## Skills:
* Data Preprocessing:
    * Cleaning and transforming data, including handling missing values, encoding categorical variables, and scaling features.
    * Splitting data into training and testing sets.

* Exploratory Data Analysis (EDA):
    * Understanding distributions, correlations, and relationships using descriptive statistics and visualizations (histograms, scatter plots).
    * Identifying important features for modeling.


* Feature Engineering:
    * Creating new features or modifying existing ones to improve model performance.
    * Techniques such as polynomial features or interaction terms might be used.

* Machine Learning:
    * Building classification models (e.g., using algorithms like logistic regression, decision trees, or random forests).
    * Model evaluation through metrics like accuracy, precision, recall, F1 score, and confusion matrices.
    * Hyperparameter tuning using grid search or random search techniques.
    * Cross-validation for reliable performance evaluation.

* Model Training and Prediction:
    * Fitting models to training data and using the model to predict potential customers.
    * Implementing validation and test predictions for model performance assessment.

* Data Visualization:
    * Visualizing model results (e.g., ROC curves, precision-recall curves).
    * Plotting feature importance to understand model behavior.

* Evaluation and Interpretation:
    * Interpreting the model results, such as understanding which features contribute most to customer prediction.
