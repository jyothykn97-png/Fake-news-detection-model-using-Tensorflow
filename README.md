# Fake-news-detection-model-using-Tensorflow

## Description 
Fake news detection is a machine learning–based project that aims to classify news articles as Real or Fake using Natural Language Processing (NLP) and TensorFlow.
The model analyzes textual content and learns patterns that differentiate genuine news from misleading or fabricated information.
This project uses deep learning techniques to automatically detect fake news, helping reduce misinformation spread on digital platforms.

--------

## objectives

- Identify whether a news article is Real or Fake
- Apply text preprocessing and tokenization
- Train a TensorFlow deep learning model
- Evaluate model performance using accuracy and loss
- Provide predictions on new, unseen news articles

  --------
  
## Dataset Description

The dataset consists of news articles with the following fields:
Text – Full news article content
Label –
0 → Real News
1 → Fake News
The dataset is preprocessed to remove noise such as punctuation, stopwords, and unnecessary symbols.

--------
## Technologies Used
- Python 
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- Natural Language Processing (NLP)
--------
 ## Model Architecture
- Text Tokenization
- Dense Neural Network
- Dropout Layer (to reduce overfitting)
- Sigmoid Activation Function for binary classification
-------
## Workflow
- Load and explore the dataset
- Clean text data (lowercase, remove punctuation & stopwords)
- Convert text to sequences using Tokenizer
- Pad sequences for equal length
- Split data into training and testing sets
- Build TensorFlow model
- Compile model using:
Loss: binary_crossentropy
Optimizer: Adam
Train the model
-Evaluate accuracy and loss
-Predict fake or real news
------
## Output
- Model predicts:
 REAL 
 FAKE 
- Displays prediction probability
---------
## Benefits of the Project
- Helps combat misinformation
- Automates news verification
- Can be extended for social media monitoring
- Useful for journalism, media houses, and research
---------
##  Conclusion
This Fake News Detection model demonstrates how TensorFlow and NLP can be used to identify misinformation efficiently. The model achieves reliable accuracy and can be further improved with advanced deep learning architectures and larger datasets.
