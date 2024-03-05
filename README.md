# Election-Sentiment-Analysis-Dashboard
Twitter Setimental Analysis
# Nigeria 2023 Presidential Election Sentiment Analysis Dashboard

## Introduction

Nigeria’s 2023 Presidential Election is being anticipated by Nigerians and others around the world. The 2023 election has drawn close attention and people are eager to follow every happening around the 2023 presidential election in Nigeria.

Social media has been a medium where people express their opinions about each candidate in the presidential elections. There are different social media platforms including Twitter. Twitter is a large community where people around the world discuss different topics and share ideas and opportunities.

In this work, we are interested in the discussions that are pertaining to the top 3 presidential candidates on the Twitter platform.
## Motivation

This project was initiated as a learning opportunity to gain hands-on experience with data engineering tools. The absence of a similar sentiment dashboard for Nigeria's presidential candidates prompted the development of this project.

## Objective

- Implement a live sentiment analysis dashboard for the top 3 presidential candidates.
- Utilize Tweepy and Apache Kafka for Twitter data extraction and streaming analytics.
- Connect Power BI to visualize data from Google BigQuery.

## Data Source and Extraction

Twitter data was streamed using Tweepy, with specific queries created to filter tweets related to the top 3 presidential candidates: Atiku Abubakar, Asiwaju Bola Ahmed Tinubu, and Peter Gregory Obi.

## Connecting the Stream to Kafka

Apache Kafka was employed for real-time data processing. A Kafka cluster was set up on Confluent Cloud, with producers streaming tweets and consumers performing stream processing using Python.

### Project workflow overview
![Sentiment Dashboard](https://miro.medium.com/v2/resize:fit:828/format:webp/1*Ft3Cyd66rigyvcikVAJ03A.jpeg)

## My Contribution

### BigQuery

- Implemented data preprocessing and cleaning tasks.
- Designed queries to filter relevant tweets for the top 3 candidates.
- Set up and managed the Google BigQuery dataset.

### Power BI

- Integrated Google BigQuery data into Power BI for visualization.
- Designed and developed the sentiment analysis dashboard.
- Ensured automatic data refresh for near real-time updates on the dashboard.
  
#### Power BI Dashboard
![Sentiment Dashboard](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*c6iWpi3ys8C-kX_lt0v9ig.png)



## Results

The sentiment analysis dashboard provides real-time insights into public sentiment towards the presidential candidates. Continuous data flow from Twitter to BigQuery enables up-to-date visualization on the Power BI dashboard.

## Future Improvements

- Enhance data quality and verification checks using dbt
- Implement advanced sentiment analysis techniques.
- Explore options for faster data refresh rates on Power BI.

## Contributors

- [OLANBIWONINU WALIULAHI AYOMIDE](https://github.com/ayomidecode)
- [Muhammad King Yakub](https://github.com/Omotade-MY)

## References

- [Tweepy Documentation](https://docs.tweepy.org/en/stable/)
- [Apache Kafka](https://kafka.apache.org/)
- [Google BigQuery](https://cloud.google.com/bigquery)
- [Power BI Documentation](https://docs.microsoft.com/en-us/power-bi/)

