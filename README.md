# Sentiment Analysis During the Late Stages of the COVID-19 Pandemic

## Project Overview
This project analyzes Twitter data to understand public sentiment during the late stages of the COVID-19 pandemic. By leveraging Apache Spark for data processing and Python for analysis, it aims to decipher the public discourse and sentiment trends related to COVID-19.

## Methodology
- **Data Sources:** Twitter API v2 for collecting 137,918 tweets.
- **Data Preprocessing:** Filtering relevant COVID-19 related tweets, cleaning data for analysis.
- **Models Used:** Sentiment analysis models and Latent Dirichlet Allocation for topic modeling.
- **Analysis Techniques:** Natural Language Processing for text analysis, sentiment scoring, and topic identification.
- **Evaluation Metrics:** Sentiment polarity scores and topic coherence scores.

## Results and Observations
- **Performance Metrics:** High accuracy in sentiment classification and topic relevance.
- **Key Findings:** The analysis uncovered diverse sentiments and multiple topics in public tweets about COVID-19, highlighting the varied public opinion during the pandemic.

## Repository Contents
- `Data`: Folder containing a processed dataset sample.
- `Scripts`: Source code for data streaming, preprocessing, analysis, and visualisation scripts.
- `Project Images`: Features charts and plots providing insights from the analysis.

## Images and Visualizations
- **Topic Modelling (n=3)**:
  ![Topic Modelling (n=3)](https://github.com/comuilleoir/COVID-Sentiment/blob/main/Project%20Images/Topic%20Modelling%20n%3D3.png)

- **Top 10 word/wordpairs per topic**:

  ![Top 10 word/wordpairs per topic](https://github.com/comuilleoir/COVID-Sentiment/blob/main/Project%20Images/Topic%20Top%2010%20words%20v2.png)

- **Tweets per Sentiment per topic**:
  ![Tweets per Sentiment per topic](https://github.com/comuilleoir/COVID-Sentiment/blob/main/Project%20Images/Tweets%20per%20Sentiment%20per%20Topic.png)

- **Tweets per Emotion per topic**:
  ![Tweets per Emotion per topic](https://github.com/comuilleoir/COVID-Sentiment/blob/main/Project%20Images/Tweets%20per%20emotion%20per%20topic.png)


## Conclusion and Future Work
- **Conclusion:** The study provides a comprehensive view of public sentiment and discussions on Twitter during the late stages of COVID-19.
- **Future Work:** Future research could focus on multi-lingual sentiment analysis and real-time monitoring of public opinion on various topics.