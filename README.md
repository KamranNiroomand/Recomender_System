# Recomender_System
This repository contains a collaborative recommender system implemented in Python for recommending answerers on Stack Overflow based on their scores. The recommender system utilizes collaborative filtering techniques, specifically Singular Value Decomposition (SVD), to predict the scores of answerers for individual questions. The system takes a dataset of Stack Overflow questioners and answerers, including features such as question score, question time, tags, number of views, number of answers, answer score, and answer time. It builds a model for each question, trains it using SVD, and evaluates its performance using hit rate. The system also considers similarity between the actual answerer and predicted answerer to account for potential good recommendations. The code is organized into sections for data preprocessing, model training, evaluation, and overall hit rate calculation. The original database can be found on ("https://www.brentozar.com/archive/ 2015/10/how-to-download-the-stack-overflow-database-via-bittorrent/")
