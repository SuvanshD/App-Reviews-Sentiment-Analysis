# App Reviews Sentiment Analysis using Python

App Reviews Sentiment Analysis is the process of evaluating and understanding the sentiments expressed in user reviews of mobile applications. This project demonstrates how to analyze the sentiments of app reviews using Python.

## Table of Contents
- [Introduction](#introduction)
- [Process Overview](#process-overview)
- [Dataset](#dataset)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Sentiment Analysis](#sentiment-analysis)
- [Text Analysis](#text-analysis)
- [Usage](#usage)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction
App Reviews Sentiment Analysis helps app developers and businesses understand user feedback, prioritize feature updates, and maintain a positive user community. In this project, we classify app reviews into positive, negative, or neutral sentiments based on textual analysis.

---

## Process Overview
1. **Dataset Collection**: Gathered a dataset of app reviews.
2. **Exploratory Data Analysis (EDA)**: Analyzed:
   - Distribution of ratings.
   - Length of reviews.
3. **Sentiment Labeling**: Used TextBlob to label sentiments as Positive, Negative, or Neutral.
4. **Sentiment Analysis**: Examined the overall sentiment distribution and its relationship with ratings.
5. **Text Analysis**: Created word clouds to identify common themes within each sentiment category.

---

## Dataset
The dataset contains 702 app reviews, with the following columns:
- **Review**: Textual feedback from users.
- **Rating**: Numerical rating (1 to 5).

You can download the dataset from [here](https://statso.io/sentiment-analysis-case-study/).

---

## Exploratory Data Analysis (EDA)
### Key Insights:
- Distribution of ratings reveals the overall user satisfaction.
- Length of reviews can correlate with sentiment intensity.

### Visualizations:
1. Rating distribution.
2. Review length distribution.

---

## Sentiment Analysis
TextBlob was used to analyze the polarity of reviews:
- **Polarity > 0.1**: Positive
- **Polarity < -0.1**: Negative
- **Otherwise**: Neutral

### Results:
- Distribution of sentiments.
- Sentiment trends across different rating levels.

---

## Text Analysis
Generated word clouds to identify common themes or frequently used words in:
- Positive reviews.
- Negative reviews.
- Neutral reviews.

---

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/SuvanshD/App-Reviews-Sentiment-Analysis.git
   cd app-reviews-sentiment-analysis
