# Neural-Network-SMS-Text-Classifier
SMS Spam Classification: A machine learning project that classifies SMS messages as "ham" or "spam" using TF-IDF vectorization and Logistic Regression. Includes a predict_message() function returning the spam probability and predicted label, with evaluation using accuracy and a confusion matrix.
This project demonstrates a machine learning solution for classifying SMS messages as either "ham" (normal messages) or "spam" (unsolicited/advertisement messages). The project uses the SMS Spam Collection dataset and implements a Logistic Regression model with TF-IDF vectorization for text preprocessing.

The main goal is to predict whether a given SMS message is spam, and also provide the probability of it being spam.
Features
Text Preprocessing: Converts SMS messages into numerical vectors using TF-IDF.
Model: Trains a Logistic Regression classifier for binary classification (human vs. spam).
Evaluation: Measures performance using accuracy and confusion matrix.
Predict Function: Includes a reusable function predict_message(message) that returns:
Probability of the message being spam (0–1)
Predicted label: "human" or "spam"
Example Usage: Provides predictions for sample messages to verify model performance.

Dataset
Source: SMS Spam Collection Dataset
Format: Tab-separated values (TSV)

Columns:
label: 'human' or 'spam'
message: Text content of the SMS

Requirements
Python 3.x

Libraries:
pandas
numpy
scikit-learn
matplotlib
seaborn
Jupyter Notebook or Google Colab

Results

The model achieves high accuracy (~98%) on the test set.
The confusion matrix provides insight into true vs predicted classifications.
The predict_message() function can classify new SMS messages effectively.

License

This project is open source and available under the MIT License.
