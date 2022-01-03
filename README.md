## Project Overview

This project performs free form text analysis for CRISIS Survey conducted child mind institute to understand responses and experiences of participants during COVID-19 pandemic. Survey consists of textual free form data labelled as Crisislogger as well as Survey questionaire response consisting of categorical, numerical choices along with Textual data in ProlificAcademic folder. 
Exploratory data anlysis is conducted for univariate and bivariate analysis for ProlificAcademic data consisting of longitudinal Analysis of responses from adults across April 2020 to April 2021.
Natural Language processing techniques include  sentiment analysis, topic modelling, word count frequencies, n grams and tokeization of the responses.

____

## Techniques Applied

* Exploratory Data Analysis
  - EDA is performed on survey-adult notebook for prolific academic survey which includes basic summary statistics and visualtization techniques.
    Perform a merge across all 4 data to find common participants and common columns.
    Bar histogram to plot data distribution of age, education.
    Location longitudinal analysis to check for migration across pandemic.
    Mental health distribution is plotted across the survey duration.
    - Correlation heatmap is created to visualize correlation of financial associated data with mental health in financial_analysis.ipynb

* Sentiment Analysis
  - Predict response sentiments using textblob and vader performed for survay-adult on anything_else column common for April 2020 and April 2021 data and crisislogger transcripts

* Text pre processing    
    - Free text pre processing includes removing punctuation, stop words and tokenization using lemmatizer technique using nltk library

* Word count frequencies and plot word cloud

* Topic modeling using BERTopic

* Clustering using LDA technique


## Libraries Resources used
Analysis is computed on jupyter notebooks packages include numpy, pandas, matplotlib, seaborn, bertopic, nltk , textblob, gensim. Self contained html reports present in build directory.
