# AI-Powered SMS Spam Detection System

## Project Overview
This project uses machine learning and natural language processing techniques to classify SMS messages as **Spam** or **Not Spam**. It helps identify unwanted messages and demonstrates a complete machine-learning workflow.

## Problem Statement
SMS spam messages can contain unwanted advertisements, scams, or misleading information. This project builds a classification model that predicts whether a message is spam based on its text.

## Dataset
- **Source:** UCI Machine Learning Repository — SMS Spam Collection
- **Records:** Approximately 5,574 SMS messages
- **Features:** Message text and label (`ham` or `spam`)
- **Target:** Spam (1) or Not Spam (0)

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- TF-IDF
- Multinomial Naive Bayes
- Google Colab

## Project Workflow
1. Load the SMS Spam Collection dataset.
2. Explore the data and check message distribution.
3. Convert labels into numeric values.
4. Split the dataset into training and testing sets.
5. Convert text into numerical features using TF-IDF.
6. Train a Multinomial Naive Bayes classifier.
7. Evaluate the model using accuracy, precision, recall, F1-score, and a confusion matrix.
8. Predict whether new SMS messages are spam or legitimate.
9. Save the trained model and TF-IDF vectorizer.

## Model
**Multinomial Naive Bayes** was used for SMS text classification.

## How to Run
1. Open `AI_SMS_Spam_Detection.ipynb` in Google Colab.
2. Run the notebook cells in order.
3. Enter a sample SMS message when prompted.
4. View the model's prediction.

## Project Files
- `AI_SMS_Spam_Detection.ipynb` — Complete project notebook
- `spam_detection_model.pkl` — Saved trained classifier
- `tfidf_vectorizer.pkl` — Saved TF-IDF converter

## Future Improvements
- Compare multiple classification algorithms.
- Improve text preprocessing.
- Build a simple web application for message detection.
- Test the model on additional SMS datasets.

## Author
Shruti Gupta
# AI-SMS-Spam-Detection
