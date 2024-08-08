# prodigy-infotech-project3
Social Media Sentiment Analysis
Project Overview
This project leverages Power BI to analyze and visualize sentiment patterns in social media comments to understand public opinion and attitudes towards specific topics or brands. The analysis is based on two datasets (twitter_training and twitter_validation), each containing data on comments made on various social media apps. The goal is to identify which app receives the most comments, analyze the nature of those comments, and gain insights into the sentiment and public perception of the apps.

Data Source
The project uses two tables:

twitter_training:
Columns: id, app name, nature of comment, comment
twitter_validation:
Columns: id, app name, nature of comment, comment
Power BI Solution Overview
Using default Power BI tools, this analysis focuses on the following key steps:

1. Data Import and Integration
Data Import: Import the twitter_training and twitter_validation tables into Power BI.
Data Integration: Combine the two tables into a single dataset using the Append Queries feature in Power BI. This allows for a unified analysis across both training and validation datasets.
2. Data Cleaning and Preparation
Remove Duplicates: Ensure no duplicate comments or entries exist using the Remove Duplicates function.
Categorization: Use the nature of comment column to categorize comments into positive, negative, and neutral sentiments.
3. Sentiment Analysis
Sentiment Scoring: If available, use Power BI’s AI-driven Text Analytics feature (if premium license is available) to score the sentiment of each comment. Alternatively, categorize manually based on the nature of comment column.
Sentiment Classification: Classify each comment into positive, negative, or neutral based on sentiment scoring.
4. Visualization
Create the following visualizations to provide insights into sentiment patterns and public opinion:

Sentiment Distribution by App:

A stacked bar chart showing the distribution of positive, negative, and neutral comments across different apps.
Total Comments by App:

A bar chart displaying the total number of comments per app, allowing easy identification of the app with the most engagement.
Word Cloud of Comments:

A word cloud visualization highlighting the most frequently used words in the comments, filtered by sentiment to understand the tone of user feedback.
Sentiment Over Time:

A line chart showing how sentiment towards each app has changed over time, using date/time data if available.
