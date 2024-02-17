# Recommendation-System-Project
Course Projects

![Pipeline](https://github.com/shgupta1461/Recommendation-System-Project/assets/64950073/f57aae2b-af68-48d7-b441-e2a3938befb1)

## Data Analysis

In the above file the data was not in appropriate formate. we convert it into pandas dataframe After that we removed null values and deleted duplicate rows. After cleaning data we got to know that the first dataset is about user, item and it's ratings and reviews. here many users have pechased multiple items.And the second dataset is about users and it's rating on book and description about the book. 

## Feature Extraction and NLP
First we removed unwanted features on reviews we made each word in lower case. after that we removed "english" stopwords and also we removed punctuations and html patterns.

# Representing reviews and mapping them with the users
The reviews in our dataset are represented in reviews or comments attribute. They are directly mapped to the users in the dataset.

## Designing the content-based system
The content based-recommendation system is designed using the unique combination of Frequency-based Embedding, TF-IDF and Prediction-based Embedding Word2Vec. The system is than evaluated using Precision, Recall and F1-score.

## Novelties/ Contributions
Combined the formulations of tf-idf along with pre-trained word2vec model for training and vector formation of word embeddings. used three matrics for evaluation namely Precision, Recall and F1-score. Worked on two different large scale datasets.

NOTE: the code has been tested on limited part of datasets due to computational constraints.

# Contributions:-

Epinions.txt converted to suitable form by Kavisha Madani
Reviews.txt pre-processed by Shashwat Parikh
EDA and data analysis done by Kavisha Madani and Mayan Bhut
Feature Extractions and Vectorization done by Shashwat Parikh and Shubham Gupta
Model mapping with user done by Shashwat Parikh
Recommendation system evaluation done in group

## Dependencies
Choose the latest versions of any of the dependencies below:
pandas : for data analysis 
numpy : for data analysis
matplotlib : for plotting the graphs
sklearn : for model training
nltk 
random
