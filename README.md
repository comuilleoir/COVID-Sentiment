# Sentiment Analysis During the Late Stages of the COVID-19 Pandemic

## Project Overview
This project aims to analyze public sentiment during the late stages of the COVID-19 pandemic through Twitter data. Utilizing a combination of an Apache Spark cluster for data processing, Python for analysis, Tweepy for Twitter API interactions, and Socket programming for data streaming, this study provides a comprehensive view of public discourse and emotional reactions on social media. Our methodology integrates advanced machine learning models for sentiment analysis and topic modeling, offering unique insights into public sentiment trends.

## Methodology
- **Data Collection**: Utilizing the `Twitter Stream Socket` script, we collect Twitter data in real-time, leveraging Tweepy and Socket programming for efficient data streaming.
- **Data Processing and Analysis**: The `Twitter Spark Streaming` script processes the streamed data using Apache Spark. This involves data cleaning, preprocessing, and structuring for analysis.
- **Sentiment Analysis and Topic Modeling**: Employing machine learning models, we conduct sentiment analysis to classify tweets into various emotional categories. Additionally, Latent Dirichlet Allocation is used for topic modeling to identify prevalent themes in the dataset.
- **Data Source**: Analysis of 137,918 tweets, providing a broad spectrum of public opinion.

## Results
- **Performance Metrics**: The project achieved high accuracy in sentiment classification and topic relevance, demonstrating the effectiveness of our analytical approach.
- **Key Findings**: Our analysis revealed diverse public sentiments and a range of topics discussed in relation to COVID-19. This includes public concerns, misinformation trends, and emotional reactions, providing valuable insights into public discourse during the pandemic.

## Technologies Used
- **Python**: For scripting and data analysis.
- **Apache Spark**: Cluster for large-scale data processing.
- **Tweepy**: To interact with Twitter API for data streaming.
- **Socket Programming**: For establishing network connections and streaming data.
- **Machine Learning Models**: For sentiment analysis and topic modeling.

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


## Limitations and Future Work
- **Language Bias**: The current dataset is limited to English-language tweets, which may not represent the global sentiment accurately.
- **Future Directions**: Future iterations could include multi-language support, incorporating more advanced sentiment analysis techniques, and expanding the dataset to cover a wider range of topics and timeframes.