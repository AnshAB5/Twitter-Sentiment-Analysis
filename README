# Twitter Sentiment Analysis using Space NER: Exploratory Data Analysis and Modeling

This repository contains the code for a Twitter sentiment analysis project titled "Twitter Sentiment Analysis using Space NER: Exploratory Data Analysis and Modeling". The project utilizes Space NER for modeling and incorporates exploratory data analysis (EDA) techniques to gain insights from the dataset.

## Dataset Overview

The project utilizes a dataset consisting of Twitter data for sentiment analysis. Before starting the analysis, one null value in the training dataset is removed.

## Exploratory Data Analysis (EDA)

EDA is performed to explore and analyze the dataset. The following steps are undertaken:

1. Data Cleaning and Preprocessing
2. Statistical Analysis
3. Visualizations

The EDA provides insights into the distribution of tweets in the train set, categorized by sentiment (neutral, positive, negative).

## Jaccard Similarity Analysis

The Jaccard similarity is computed between the original text and the selected text for each tweet in the dataset. The Jaccard similarity score measures the overlap between two sets of words. The results of the Jaccard similarity analysis are stored in the `results_jaccard` list.

## Analysis of Jaccard Scores

The Jaccard scores are analyzed through the creation of density plots and distribution plots. The trends observed include high kurtosis for positive and negative tweets, indicating a concentration of values around similarity score 1. Neutral tweets show a bump in density near values of 1.

## Conclusion of EDA

Based on the Jaccard score plot, it is observed that certain clusters of tweets exhibit high similarity between text and selected text. The idea of analyzing tweets with a word count of less than 3 in the text segment is proposed, as these tweets may have the entire text used as the selected text. This information is utilized in subsequent model building.

## Cleaning the Corpus

The corpus is cleaned by removing common words that appear in all three segments (text, selected text, sentiment). Words such as "get," "go," "dont," "got," "u," "cant," "lol," and "like" are identified as common. Further insights on the correctness of data labeling are explored through N-gram analysis.

## Unique Words in each Segment

The unique words present in each segment (text, selected text, sentiment) are examined to gain insights into the distinct vocabulary associated with different segments.

## Modelling the Problem as NER

The problem of sentiment analysis is framed as a Named Entity Recognition (NER) task. NER involves identifying and categorizing named entities (such as people, places, organizations) from text into predefined categories. The use of Space NER for sentiment analysis modeling is explored.

This repository contains the code necessary to replicate the analysis and explore the various stages of the project. The code is organized into logical sections, making it easy to follow and understand.

Please refer to the code files for detailed implementation and step-by-step analysis.

Enjoy exploring the fascinating world of Twitter sentiment analysis and NER!
