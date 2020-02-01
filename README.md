# Strategy-game-analysis

# Final Report: 
# Data Scource
Kaggle. Link: https://www.kaggle.com/tristan581/17k-apple-app-store-strategy-games

# Background
This is the data of 17007 strategy games on the Apple App Store. It was collected on the 3rd of August 2019, using the iTunes API and the App Store sitemap.

# Overview
The mobile games industry is worth billions of dollars, with companies spending vast amounts of money on the development and marketing of these games to an equally large market. Using this data set, insights can be gained into a sub-market of this market, strategy games. This sub-market includes titles such as Clash of Clans, Plants vs Zombies and Pokemon GO.

# What I did

1. Data cleaning

2. Data visualization: About 17,007 mobile games. Mapped market share & competition of different genres. Revealed trends of game size,
language versions and price policy of two groups of games (most reviewed & common games) by 10 years

3. Inference: Used multiple linear regression methods to determine factors that are significantly related to the number of reviews in log10
scale. Conducted statistical test (t.test & prop.test) to check whether two groups are significantly different by these factors

4. Prediction: Built machine learning models like GLM and logistic regression model with 14 predictors to predict the number of reviews
and most reviewed games

5. Text analysis: Analyzed game descriptions using word count and tf-idf methods. Extracted key words to attract users
