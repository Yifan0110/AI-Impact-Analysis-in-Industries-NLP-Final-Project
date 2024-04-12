# AI Impact Analysis in Industries: NLP Final Project

## Overview
This repository contains the code and presentation slides for the final project of the Natural Language Processing (NLP) course. The project focuses on analyzing the impact of Artificial Intelligence (AI) on various industries and job lines over the next several years, based on a collection of news articles related to Data Science, Machine Learning, and Artificial Intelligence.

## Objective
The objective of this project is to extract meaningful insights from unstructured text data, identify industries and job lines most likely to be impacted by AI, and provide actionable recommendations for leveraging AI to automate tasks and improve productivity.

## Data
The dataset consists of approximately 200K news articles (about 900 MB) related to Data Science, Machine Learning, and Artificial Intelligence. The data has been preprocessed to clean up noise, eliminate irrelevant articles, and detect major topics.

## Executive Summary
### Background
- Predictions indicate that by 2032, the AI market in the United States will soar to $594 billion.
- Goldman Sachs predicts that 25% of tasks in the US and Europe could be automated by AI, with administrative (46%) and legal (44%) sectors being highly exposed.

### Problems
- Identify susceptible jobs and industries to AI-driven disruption and promising prospects.
- Offer recommendations to expedite the advancement of transformative capabilities.

### Next Steps
- Conduct topic analysis, sentiment analysis, entity analysis, and timeline analysis to address these questions.

## Data Processing
- Cleaned article texts by tokenizing, removing stopwords, making bigrams and trigrams, and lemmatizing.
- Filtered data by taking 10% randomly, dropping non-English results, articles with less than 20 words, and irrelevant articles.
- Removed duplicate values and cleaned special characters, newlines, tabs, and links.

## Topic Detection (LDA)
- Identified six major topics:
  1. Market and business intelligence
  2. AI technology and business solutions
  3. Recent news and events
  4. AI in the stock market
  5. Healthcare and communication
  6. General discussion about AI

## Sentiment Analysis
- Trained sentiment analysis models using open-source data from Yelp.
- AI discussions surged since 2023, but so did the divide in opinions.
- SVM model achieved the highest accuracy.

## Entity Identification
- Identified organizations, locations, persons, and products mentioned in AI articles.

## Targeted Entity Sentiment Identification
- Prevalence of negative sentiments across organizations and products.
- Some entities like Claude and Llama 2 have very negative sentiment scores.

## Timeline Analysis
- From 2023, a surge of new AI technologies and solutions like GPT4 and Llama 2.
- Increasing corporate engagement with prominent companies like Tesla, Nvidia, Apple, and Samsung.
- Samsung emerging as a key player in 2024, alongside technologies like GPT.

## Conclusion
- Ongoing ethical concerns and societal apprehensions about AI's impact.
- Lesser disruption in employment expected in the Media, Telecommunications, and Finance sectors.
- Need for stakeholders to prioritize ethical frameworks and collaborative efforts for responsible AI development.
- Tech giants like Microsoft, Google, Apple, Amazon, and Nvidia leading AI development, with emerging players like Samsung quickly making their mark.


## Repository Structure
- `code/`: Contains the Jupyter Notebook (`NLP_Final_Project.ipynb`) with the code for data preprocessing, analysis, and visualization.
- `presentation/`: Contains the PowerPoint presentation (`NLP_Final_Project_Presentation.pptx`) summarizing the project findings.
- `README.md`: Provides an overview of the project, methodology, results, and repository structure.

## Dependencies
- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- scikit-learn
- nltk
