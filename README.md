# Fake News Detection Using Text Analytics

## Introduction
This project aims to develop a novel text analytics-driven approach for detecting fake news and reducing the spread of misinformation. By utilizing advanced modeling techniques, the system focuses on detecting fake topics to identify deceptive news articles.

## System Design
![System Design](/img/systemdesign.jpg)

## Dataset
The model was trained using legitimate news datasets obtained from Kaggle. These datasets have been classified as reliable by a reputable group of scientists and are widely circulated among a large audience. Additionally, a separate dataset from Kaggle specifically designed for verifying fake news was used. The datasets include class labels indicating whether the news articles are fake or real.

## Implementation
The implementation of the fake news detection system involved the following steps:

1. **Data Split**: The dataset was divided into a training set (65% of the data) for model training.
2. **Data Preprocessing**: Data preprocessing techniques were applied to clean and prepare the text data.
3. **Feature Extraction**: Features were extracted from the preprocessed data using TF-IDF vectorization.
4. **Topic Clustering**: K-Means clustering was applied to group similar topics into clusters.
5. **Topic Modeling**: Topic modeling techniques were employed to reduce the number of clusters and create ground truth information.
6. **Comparison and Evaluation**: Deceptive topics were compared against the ground truth topics using evaluation metrics to detect fake news.
7. **Credibility Metrics**: Credibility metrics were calculated, and information about the news articles was displayed based on a threshold.

This framework utilizes fake topic detection to classify fake news and provides better credibility evaluation and classification accuracy.

## Conclusion
By leveraging text analytics techniques and topic modeling, this project offers an effective solution for identifying fake news and evaluating its credibility.
