# Sentiment-Analysis Based Recommendation System Using Machine Learning Models
Sentiment analysis, also known as opinion mining, is a natural language processing (NLP) technique used to determine the sentiment or subjective tone expressed in a piece of text. It involves analyzing text data, such as customer reviews, social media posts, or survey responses, to classify the sentiment as positive, negative, or neutral.

The goal of sentiment analysis is to understand the underlying sentiment or attitude conveyed by the text. By using machine learning algorithms or lexicon-based approaches, sentiment analysis can automatically categorize text into different sentiment categories based on the emotional tone or polarity of the language used.

## Problem :-

Day by day, demand in e-commerce is increasing. With the increasing demand in online stores, the voice of customer concepts such as reviews and customer experiences are getting more important because customers buy products without seeing or touching them. If the company fails to meet this need of customers, it loses money because of not taking strategic decisions.

## Aim :-

Protect company from losing money with increasing customer satisfaction and giving importance to their feedback.

## Solution :-

Define good or bad products as quick as possible according to reviews and take action for this. For this solution, I worked on sentiment analysis with different models. The model predicts reviews as positive or negative from text.

Recommend customers related products to increase satisfaction with decreasing search time for suitable product. I have built recommendation system in this project for this solution.

## What Will These Solutions Bring to The Company?

Easy Product Comparison <br>
Defining Dislikes Easily <br>
Saving Time <br>
More Money with Selling More Products <br>
Happier Customers = More Customers = More Money <br>
Less Time on Server = Less Problem

## Data :-

In this project, I worked on sentiment analysis of Kindle Store reviews in Amazon. I choose this dataset because it is more easy to buy and read a book with Kindle. Going to the book store, finding a book which you like need more time than reaching every book from your tablet.

## Process :-

* Data Collection: Gather data that includes both user feedback (reviews, ratings, comments) and item information (descriptions, features) for the recommendation system. This data will be used for training and evaluation.

* Data Preprocessing: Clean and preprocess the collected data. This typically involves removing noise, such as special characters and punctuation, tokenizing the text into individual words, removing stopwords, and performing stemming or lemmatization to reduce words to their base form.

* Sentiment Analysis: Train a sentiment analysis model using machine learning algorithms. This involves labeling the data with sentiment values (positive, negative, neutral) and extracting relevant features from the preprocessed text. Distribute review ratings into days, months and years to analyse deeply is the most efficient technique.

* Sentiment Integration: Integrate the sentiment analysis model into the recommendation system. This can involve assigning sentiment scores to user feedback or reviews, or categorizing them into sentiment categories.

* User-Item Matrix: Create a user-item matrix that represents the interactions between users and items. Each entry in the matrix can include sentiment scores or sentiment labels associated with user feedback for a particular item.

* Recommendation Algorithm: Select or design a recommendation algorithm that suits the specific requirements of the system. Collaborative filtering, content-based filtering, or hybrid approaches are commonly used in recommendation systems. Here in this, I have used Collaborative Filtering Method.

* Training and Testing: Split the data into training and testing sets. Use the training data to train the recommendation model, considering both user-item interactions and sentiment information. Evaluate the model's performance on the testing set using appropriate evaluation metrics such as accuracy, precision, recall, or user satisfaction. I have used various machine learning models for this such as Logistic Regression, Decision Trees, Extra-Tree, and Random Forest.

* Optimization and Refinement: Iterate and refine the model by fine-tuning the sentiment analysis algorithm, optimizing the recommendation algorithm, and incorporating user feedback. Continuously evaluate and improve the performance of the system.

* Deployment: Once the model is trained and evaluated, deploy the sentiment analysis-based recommendation system in a production environment. Monitor its performance, gather user feedback, and make necessary updates and improvements as required.

## Note:
I have upload my Jupyter Notebook for both sentiment analysis and recommendation model for your reference.<br>
Moreover, I have uploaded sample data - both raw and cleaned data.
