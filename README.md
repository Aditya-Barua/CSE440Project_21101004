#CSE440 - Natural Language Processing (NLP) Project

This project implements token-level multi-class classification for Part-of-Speech (POS) tagging using **POS Dataset 2**. The objective is to build deep learning models that assign a grammatical label (e.g., noun, verb, adjective) to each token in a sentence. The dataset is provided as training (80%) and testing (20%) CSV files. The training set is used for model development and validation, while the testing set is used strictly for final performance evaluation. 
The workflow of the project includes:

* **Exploratory Data Analysis (EDA)** to understand token and POS tag distributions
* **Text preprocessing**, including token encoding and sequence padding
* Implementation of four sequence models:

  * **Recurrent Neural Network** (**RNN**)
  * **LSTM**
  * **GRU**
  * **Bidirectional LSTM (BiLSTM)**

Hyperparameters such as **learning rate, batch size, and epochs** are tuned based on validation performance. Model performance is evaluated using:

* **Accuracy**
* **F1-score**
* **Confusion Matrix**
* **Classification Report**

The results are compared to determine which architecture performs best for POS tagging on **POS Dataset 2**. 


## Repository Contents

* **Notebook** – Model implementation and experiments
* **Report (PDF)** – Detailed explanation of methodology and results
* **Project documentation**


