Repository with my TDs + project for my NLP class at ENSAE Paris.

Project
-----
The project can be found in the Project folder. It is composed of the notebook which contains the entire code, and the PDF file which contains the report.

The goal of the project is to develop an NLP pipeline for fake news detection, comparing the results between 5 different types of features (BoW counts, TD-IDF vectorization, Word2Vec embeddings, BERT embeddings and 32 linguistic cues) trained with 4 different models (Random Forest, Gradient Boosting, Logistic Regression and Adaboost). The dataset used is composed of fake news articles, predominantly addressing american politics, created by ISOT.
The second part of the project consists of testing the models' generalizability to different datasets. We perform cross-evaluation on the Fake or Real dataset from Kaggle, another political news articles dataset.
The results show excellent results for intra-dataset testing, but every feature-model combination demonstrates a significant drop in performance when evaluated on new data. Hinting that building robust fake news detectors, adapted to multiple domains, requires more diverse training data and possibly more sophisticated, domain-adaptive approaches.
