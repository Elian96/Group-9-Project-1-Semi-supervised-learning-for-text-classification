# Group-9-Project-1-Semi-supervised-learning-for-text-classification
Group 9 : Project 1 Semi-supervised learning for text classification

The project is a solution for the IKT-450: Deep Neural Networks for the Autumn semester of 2020.

Team Members: Ali Al-Talab, Teklemariam Weldehawriat, Pavel Ibrahim.

Supervisor: Morten Goodwin

The Link For The Code: https://www.dropbox.com/s/49f0mjxhjv6hrm9/Group-9-Project-1-Semi-supervised-learning-for-text-classification-Ali_Altalab-Pavel-Ibrahim-Teklemariam-Weldehawriat.zip?dl=0

Date: 02.12.2020
-------------------------------------------------------------------------------------------------
#The is both python files and notebook files

#20news-group contains the datasets which are   updated by k-means clustering

#directoryToextract contains the original train and testing data

#KMeans_unsupervised is the algorithm which groups the datasets into clusters and added the predicted cluster into the dataset's text

#KMeans-semi-supervised is the model which used the updated 20news-group datasets and trained in a supervised RNN model

#Psuedo-Labeling-semi-supervised is the algorithm where the model is trained over a small labeled data and predicted for a large unlabeled data. At the end, it combines the labeled and pseudo-labeled data together and retrain the RNN model.

#supervised-learning is the algorithm where the RNN model is trained with only labeled datasets.
