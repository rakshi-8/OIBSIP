# Unveiling the Android App Market – Google Play Store Analysis

## AICTE Oasis Infobyte Internship – Data Analytics

**Name:** Rakshitha S  
**Track:** Data Analytics  
**Task:** Level 2 – Task 4  
**Project:** Google Play Store Analysis

## 📌 Project Overview

This project analyzes Google Play Store data to understand Android app market dynamics.

The analysis focuses on app categories, ratings, popularity, installs, pricing, and user sentiment. Data cleaning, exploratory data analysis, visualization, and sentiment analysis were performed using Python.

## 🎯 Objectives

- Clean and prepare Google Play Store data
- Explore app distribution across categories
- Analyze ratings and popularity
- Study app installs and reviews
- Compare free and paid applications
- Analyze pricing trends
- Perform user sentiment analysis
- Identify useful market insights

## 📊 Datasets

Two datasets were used:

1. **Google Play Store Apps dataset**
2. **Google Play Store User Reviews dataset**

The Apps dataset contains information such as:

- App
- Category
- Rating
- Reviews
- Size
- Installs
- Type
- Price
- Content Rating
- Genres
- Last Updated
- Current Version
- Android Version

The User Reviews dataset contains:

- App
- Translated Review
- Sentiment
- Sentiment Polarity
- Sentiment Subjectivity

## 🧹 Data Preparation

The following preprocessing steps were performed:

- Removed unnecessary index columns
- Converted Reviews into numeric format
- Cleaned Installs by removing commas and `+`
- Converted Installs into numeric values
- Removed `$` from Price values
- Converted Price into numeric format
- Handled missing ratings using the median
- Removed rows with missing essential information
- Removed duplicate records

## 📈 Analysis Performed

### Category Analysis

Analyzed the number of applications across different categories and identified the most common categories.

### Ratings Analysis

Analyzed:

- Average rating
- Minimum and maximum rating
- Rating distribution
- Average rating by category

### Popularity Analysis

Used installs and reviews to understand app popularity and user engagement.

### Pricing Analysis

Compared:

- Free applications
- Paid applications
- Paid app prices
- Average price by category

### Sentiment Analysis

Analyzed user reviews using the sentiment information provided in the dataset.

Sentiments were categorized as:

- Positive
- Negative
- Neutral

Sentiment polarity was also analyzed.

### Sentiment by Category

The reviews dataset was combined with app category information to analyze positive and negative sentiment across different categories.

## 📊 Visualizations

The project includes visualizations for:

- App category distribution
- Top app categories
- Rating distribution
- Top installed apps
- Reviews vs installs
- Free vs paid apps
- Paid app price distribution
- Positive sentiment by category
- Negative sentiment by category
- Interactive sentiment visualization

## 💡 Key Insights

1. Some app categories contain significantly more applications than others, indicating differences in market competition and saturation.

2. Free applications represent the dominant pricing model in the analyzed dataset, while paid applications form a smaller portion.

3. User sentiment provides additional information about customer satisfaction beyond numerical app ratings.

4. Installs and reviews provide useful indicators of app popularity and user engagement.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

## 📁 Project Structure

```text
DataAnalytics-L2-GooglePlayStore/
│
├── apps.csv
├── user_reviews.csv
├── Google_Play_Store_Analysis.ipynb
└── README.md