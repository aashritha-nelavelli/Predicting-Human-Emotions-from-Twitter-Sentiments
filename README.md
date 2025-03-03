# 🧠💬 Human-Emotion-Recognition-Using-Twitter-Sentiment-Analysis

> ![Sentiment Analysis](https://user-images.githubusercontent.com/83130336/188488944-4e879e77-0c56-4bb8-bf83-844e2fcdca7d.jpg)

## 🌍📱 Introduction
With the rise of social media platforms, people are expressing their views, opinions, and engaging in conversations globally. Twitter, one of the most popular platforms, allows users to share thoughts in real time. This project's main goal is to predict and understand the emotions behind a given text. We achieve this by creating a machine learning model that classifies tweets as either positive or negative in sentiment. Understanding and classifying human emotions from text can be incredibly useful in various fields.

## 📊🤖 Business Problem
<p>Given a text, classify whether it conveys a positive or negative emotion.</p> This is a classic binary classification problem where the model determines the sentiment of the text.


## Dataset
> https://www.kaggle.com/datasets/kazanova/sentiment140 </br>
<p>The model is trained on a dataset containing 1.6 million tweets to predict sentiment effectively.</p>
Shape of the dataset: (1600000, 6)

Key Attributes:

target: The polarity of the tweet (0 = negative, 4 = positive)
ids: The tweet's unique identifier
date: The date the tweet was posted
flag: The query (lyx). If no query, the value is NO_QUERY.
user: The user who tweeted
text: The tweet content
For training the model, only the 'text' and 'target' columns are used:

'text' ➔ independent variable
'target' ➔ dependent variable


## 🏢📊 Real-Time Applications
By analyzing the sentiment behind tweets, businesses and organizations can derive valuable insights:

Businesses: Understand customer preferences, dislikes, and pain points, helping in crafting marketing strategies and improving products.
Political Parties: Track voter opinions and sentiments to gauge public response and adjust strategies accordingly.
    
## ⚙️💻 Implementation
This project is implemented using Python. </br> The Jupyter Notebook for the implementation is available in this repository: </br>
> [Jupyter Notebook](https://github.com/aashritha-nelavelli/Predicting-Human-Emotions-from-Twitter-Sentiments/blob/main/.ipynb) </br>

Hope this repository was helpful! </br>
Do star the repository incase you liked it. </br>
Thank You :)
