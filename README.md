# Google Play Store Data Analysis & Feature Engineering

## Project Overview/Business Problem

Today, 1.85 million different apps are available for users to download. Android users have even more from which to choose, with 2.56 million available through the Google Play Store. 
These apps have come to play a huge role in the way we live our lives today.  Businesses and developers need data-driven insights to understand Key Metrics and take further actions to improve business

---

# Business Questions/Metrics

- What is the most popular app category
- Which category has largest number of installations
- Top 5 most insatalled apps in each category
- How many apps are there on google play store with 5 star ratings.

---

# Objectives

- Perform data cleaning and preprocessing
- Conduct exploratory data analysis (EDA)
- Engineer useful features for analysis and future predictive modeling
- Identify trends and patterns.

---

# Dataset Information

The dataset contains information about Google Play Store applications including::

- App Name
- Category
- Rating
- Reviews
- Size
- Installs
- Price
- Content Rating
- Genres
- Last Updated
- Android Version

---

# Data Cleaning Performed

The following preprocessing steps were carried out:

- Removed duplicate records
- Handled missing/null values
- Converted data types
- Cleaned install count formatting
- Standardized price values
- Processed app size columns
- Cleaned inconsistent categorical values

---

# Exploratory Data Analysis (EDA)

Performed detailed analysis on:

## App Categories
- Most popular app categories
- Distribution of apps across categories

## Ratings Analysis
- Average ratings by category
- Rating distribution patterns

## Installs Analysis
- Most installed app categories
- Relationship between installs and ratings

---

# Feature Engineering

Created and transformed features including:

- Numeric install counts
- Categorical install counts
- Univariate and Multivariate analysis of numerical and categorical columns

---

# Visualizations Used

The project includes multiple visualizations such as:

- Bar Charts
- Histograms
- Pie chart

---

# Key Insights

- Out of all the categories "GAME" has the most number of Installations.With almost 35 Billion Installations GAME is the most popular Category in Google App store.
- Family category has the most number of apps with 18% of apps belonging to it, followed by Games category which has 11% of the apps.
- Least number of apps belong to the Beauty category with less than 1% of the total apps belonging to it.
- Most popular game is Subway Surfers.
- Most popular communication app is Hangouts.
- Most popular communication app is Hangouts.
- Most popular productivity app is Google Drive.
- Most popular social app is Instagram.
- Number of 5 Star rated apps is 271

---

# Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# Suggestions/Way forward:

- Sentiment Analysis: Suggest performing NLP (Natural Language Processing) on the 'Reviews' text column to understand why users give 5 stars versus 1 star.
- Predictive Modeling: Mention that the next phase involves building a Random Forest Regressor to predict an app's rating based on its category, size, and price.
- Monetization Analysis: Propose a study on the correlation between "Price" and "Installs" to find the "Sweet Spot" pricing for paid apps in the 'Family' category.
- Update Recency: Analyze if apps updated within the last 6 months have significantly higher ratings than those not updated in over a year

