# CodeClause_Ai_Intern_Sentimental_analysis_Project
Detailed Description of Sentiment Analysis on Amazon Reviews

Objective:
The goal of this project is to perform sentiment analysis on Amazon product reviews to understand the distribution of sentiments (positive, neutral, and negative) and how they correlate with the star ratings provided by the users.

Steps Involved:

#Importing Necessary Libraries:

Libraries such as pandas, numpy, matplotlib, seaborn, and nltk are imported.
NLTK (Natural Language Toolkit) is specifically used for natural language processing, including sentiment analysis.

#Loading and Inspecting the Dataset:

The dataset is loaded from a CSV file containing Amazon product reviews.
The dataset is initially displayed to understand its structure and the types of information it contains.

#Subset of Data:

For faster processing and demonstration purposes, a subset of the dataset (first 500 rows) is used.

#Sentiment Analysis Using VADER:

VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analyzer is used to compute sentiment scores.
VADER is a lexicon and rule-based sentiment analysis tool specifically attuned to sentiments expressed in social media.
For each review in the dataset, the sentiment scores are computed and stored in a dictionary.

#Combining Sentiment Scores with Original Data:

The sentiment scores are converted into a DataFrame and merged with the original dataset to include metadata such as product id, review text, and star ratings.

#Visualizing Sentiment Scores:

Seaborn is used to create bar plots that visualize the distribution of sentiment scores (compound, positive, neutral, and negative) against the star ratings.
The compound score is a normalized, weighted composite score that summarizes the overall sentiment of the text.
