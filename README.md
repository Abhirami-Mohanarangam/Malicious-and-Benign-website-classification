# Malicious-and-Benign-website-classification

Identify Website Characteristics for both malicious and benign website and classify them using various Machine Learning Models

Malicious websites are clearly a threat to the Internet users and are to be avoided, if not eradicated completely. This project aims to draw the distinction between Malicious and Benign websites by identifying their key characteristic differences using various analysis and plots.

The dataset has been taken from kaggle and has cleaned and preprocessed it. Since the data is highly biased, SMOTE analysis has been applied to oversample the datapoints in the minority class.

XG Boost(eXtreme Gradient Boosting) algorithm has been used to classify the dataset. For the sake of comparison we have also implemented Random Forest Classifier and Logistic Classifier to compare the accuracy measures and the AUC value.
