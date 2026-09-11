# 🛍️ Customer Experience Analytics : An Exploratory Analysis of Amazon Fine Food Reviews

##
## 👨🏻‍💻 Project Overview

The aim of the project is to mine the data available in the Amazon Fine Food Reviews dataset to gain insights into customer ratings, review helpfulness, product performance, reviewer behavior, and reviews trends over time. In the process of making the analysis, Python, Pandas, NumPy, and Matplotlib have been utilized. Data exploration, data processing, feature engineering, and data visualization have been employed to analytically answer eight business questions and acquire useful insights from raw customer review data.
##

## 📌 Objectives
- Take a look at the ratings given by consumers.
- Go after the products that are given a lot of positive votes.
- Check if there is any relation between the length of reviews and a review's usefulness for customers.
- Check how great reviews provided by different reviewers correspond to their scores.
- Find out the main reviewers judging by the reviews they wrote.

##
## 📈 Dataset

The dataset contains information about Amazon Fine Food Reviews, Including:

- Id - Integer
- ProductId - String
- UserId - String
- ProfileName - String
- HelpfulnessNumerator - Integer
- HelpfulnessDenominator - Integer
- Score - Integer
- Time - Integer/Unnix Timestamp
- Summary - String
- Text - String

Source: [Kaggle - Amazon Fine Food Reviews] (https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)

##

## 📊 Exploratory Data Analysis (EDA) Insights 
Key insights extracted from the dataset:

- **Review Score Distribution :**
  - Customer reviews and scores indicate overall consumer satisfaction as well as whether opinions are mostly positive, negative, or neutral.
 
- **Product Performance :**
  - A product with a high average rating and considerable number of reviews proves the high level of customer satisfaction.
    
- **Review Usefulness :**
  - The length and score of the review affect consumer perception of the review itself, enabling the identification of the patterns of useful feedback.
    
- **Influence of Reviewers :**
  - Some customers leave reviews more often and get higher responses regarding usefulness than others, therefore becoming influential reviewers.
    
- **Time Trends :**
  - The amount of reviews and their average ratings change over time allowing to show patterns in customer engagement levels and satisfaction.
 
---
##
## 📋 Project Pipeline
1️⃣ **Data cleansing** : Which is the beginning step in data handling, is the process of cleaning Amazon Fine Food Reviews data. This includes missing and redundant data troubleshoot, score-checking of reviews, and Time attribute conversion into a readable date format. 

2️⃣ **Feature extraction** : It is the process of generating new features such as ReviewDate, Year, Month, ReviewLength, and Helpfulness ratio based on the already existing data. The new features will help understand what is the customers' behavior, the usefulness of reviews, and how successful the product is. 

3️⃣ **Exploratory Data Analysis** : The eight business questions raised different tools such as those belonging to Python and Pandas are utilized. Rating distribution, the success of products, the usefulness of reviews, and the influence of reviewers are the focus of analysis. 

4️⃣ **Results evaluation** : Obtained results and images are analyzed in order to know important patterns and insights. Later meaning of results is used to analyze the customers' behavior patterns while giving feedback.

##

## 🗝️ Key Insights 
- Rating distribution gives a good insight into customer satisfaction.
- It helps in understanding if the reviews are more positive, negative, or moderate.
- At product level, rating score and number of reviews should be taken into account when searching for successful products.
- Analysis at reviewer level allows for identifying those customers who write a lot of reviews and whose reviews generate high usefulness.

##

## 🗣 Business Recommendations  
Following this examination, the business must:

1. Evaluating products with good ratings and reviews is one of the best ways to get information about the particular product of your interest.
2. At the same time, it would be wise to think about the products that received bad reviews as this will help point out their weaknesses and flaws.

##

##  🤖 Technologies Used

- Python 3.13
- Pandas & NumPy
- Ploty & Matplotlib
- Scikit-learn
- Jupyter Notebook

##
## 🚀 Getting Started
1. Clone this repository
```bash
git clone https://github.com/dharak07/AI-and-Application.git
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Open the Jupyter notebook
```bash
jupyter notebook jupyter/Project.ipynb
```
##
## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.
