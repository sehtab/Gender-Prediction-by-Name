# Gender-Prediction-by-Name


Links:
https://colab.research.google.com/drive/1JazzJ3ZSB8Fj2BsgXuj840Fe1NOXhl-U?usp=sharing

https://colab.research.google.com/drive/1J5mBl0EIemnlRQUaQhuVAfg3cRpRLKoB?usp=sharing

# Objective:

The objective of this ICP is to detect gender from sentences and optional project is to classifying new documents into categories.

# Approaches

From nltk names -file is downloaded and foe male and female names .txt files are attached with the colab file. Then classifiers are used to classify the names and estimate the error of the classifiers. At first, Naive Bayes theorem is used and accuracy is estimated. Then feature extraction is improved with function and SVC, random Forest and Maximum Entropy Classifier is used and accuracy, precision, Recall and F-1 Score are estimated.

# Datasets

For this ICP from nltk female.txt and male.txt are used as datasets for male female reference names.

# Results:

Results are generated from nltk library function and sklearn they are working good. I am getting maximum accuracy from SVC classifier which is of 82%
# Challenges

Using sklearn most frequent word can not be obtained.

# Planned Work

From nltk male.txt and female.txt are downloaded and attached with the colab file.Then labels are created for classification and featureset is being created. After splitting the dataset in train and test with 20% in test set classifiers are implemented and classifiers are performance are evaluated through Accuracy, Recall, Precision and F1 -score.
