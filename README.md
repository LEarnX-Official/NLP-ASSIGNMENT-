# Wikipedia Text Classification

This repository contains Python scripts for a text classification project using Wikipedia articles. The project involves training a logistic regression model on a pre-existing dataset and making predictions on user input. The trained model and TF-IDF vectorizer are then saved for later use.

## Files

- `train_model.py`: Script to load a pre-existing dataset, preprocess the text, use TF-IDF for feature extraction, train a logistic regression model, evaluate the model, and save both the trained model and TF-IDF vectorizer.

- `predict.py`: Script to load the saved model and vectorizer, define text preprocessing and prediction functions, and make predictions on user input.

## Dependencies

- `pandas`: For handling data in DataFrame format.
- `scikit-learn`: For machine learning tools, including the logistic regression model and TF-IDF vectorizer.
- `wikipedia-api`: For accessing Wikipedia content.
- `joblib`: For saving and loading the trained model and vectorizer.

## Usage

1. Run `train_model.py`, This script will load the dataset, preprocess the text, train a logistic regression model, evaluate the model, and save the model and vectorizer.

2. Run `predict.py` to load the saved model and vectorizer, input a text, and get a prediction for the category of the text.

## Notes

- Make sure to install the required dependencies using `pip install -r requirements.txt`.

- Update the user agent in `get_wikipedia_content` function with your own user agent.

- Ensure that the pre-trained model and vectorizer files (`classifier_model.joblib` and `vectorizer.joblib`) are available for the prediction script.


