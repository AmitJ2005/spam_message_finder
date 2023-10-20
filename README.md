# Email/SMS Spam Classifier

This is a Spam Message Classifier hosted on a Streamlit server. It is designed to classify messages as either "Spam" or "Not Spam."

## Code Overview

The code is written in Python and utilizes several libraries, including Streamlit, NLTK, and Pickle. Let's break down the main components of the code:

### Preprocessing and NLP

1. The code uses the NLTK library to perform natural language processing (NLP) tasks.

2. It tokenizes the input message, converts it to lowercase, and removes non-alphanumeric characters.

3. It also removes common English stopwords and punctuation.

4. Finally, the code applies stemming to reduce words to their root form.

### Classification

1. The code loads a pre-trained TF-IDF vectorizer and a machine learning model from pickle files (vectorizer.pkl and model.pkl).

2. When the user enters a message and clicks "Predict," the following steps occur:

   a. The message is preprocessed using the same techniques described earlier.

   b. The preprocessed message is vectorized using the TF-IDF vectorizer.

   c. The machine learning model predicts whether the message is "Spam" (1) or "Not Spam" (0).

3. The result is displayed to the user on the Streamlit interface.

## Usage

To run this code, you need to have the necessary Python libraries installed, including Streamlit and NLTK. Ensure that the 'vectorizer.pkl' and 'model.pkl' files are in the same directory as this code.

To predict whether a message is spam or not, enter the message in the text area and click the "Predict" button.

## Acknowledgments

This project uses NLTK for natural language processing and Streamlit for creating the user interface. The machine learning model used for classification is pre-trained.

Feel free to ask me questions related project's.

## link 


<a href="https://spammessagefinder.streamlit.app/">Visit this project</a>

