 **Task 1: NLP Preprocessing Engine (Advanced)**
 Overview
This project builds a robust NLP preprocessing engine to clean and transform messy real-world text into structured, meaningful tokens suitable for machine learning models.

🎯 Features
Text cleaning (punctuation, emojis, noise removal)
Lowercasing
Removal of numbers, URLs, and emails
Handling repeated characters (e.g., soooo → so)
Tokenization
Stopword removal
Lemmatization
Removal of short words (≤2, except "no", "not")
Extra space removal
Error handling (empty input, emojis, numbers)
🔄 Pipeline
Raw Text → Cleaning → Tokenization → Stopword Removal → Lemmatization → Model-ready Data
🧪 Testing
Tested on real-world noisy inputs:
Emojis 😍
URLs
Numbers
Repeated characters
Mixed case text
📊 Analysis
Token count
Unique tokens
Average token length
Word frequency using Counter
🛠️ Tech Stack
Python
NLTK
Regular Expressions (re)
Jupyter Notebook
✅ Conclusion
This project demonstrates how raw, noisy text can be converted into clean, structured data, forming a strong foundation for NLP and machine learning tasks.

**Task 2: Sentiment Analysis using NLP Pipeline & ML Models**
Overview
This project builds an end-to-end Sentiment Analysis system using NLP techniques and Machine Learning models. The goal is to transform raw text into meaningful features and classify sentiments as positive or negative.

🎯 Objectives
Perform text preprocessing on raw data
Convert text into numerical features
Train multiple ML models
Evaluate and compare model performance
🔄 Pipeline
Raw Text → Preprocessing → Feature Engineering → Model Training → Evaluation → Comparison

🧹 NLP Preprocessing
Lowercasing
Removing punctuation & special characters
Stopword removal
Tokenization
Stemming
⚙️ Feature Engineering
Bag of Words (BoW)
TF-IDF Vectorization
🤖 Models Used
Logistic Regression
Naive Bayes
Decision Tree
📊 Evaluation Metrics
Accuracy
Precision
Recall
F1 Score
📈 Results & Insights
Logistic Regression performed best overall
TF-IDF gave better results than BoW
Preprocessing improved model accuracy
Decision Tree showed slight overfitting
🛠️ Tech Stack
Python
NLTK
Scikit-learn
Jupyter Notebook
✅ Conclusion
The project demonstrates how NLP preprocessing and feature engineering significantly impact sentiment classification. Among all models, Logistic Regression with TF-IDF provided the best performance.

**Task 3:Build a Chatbot using Hugging Face Transformers**
* Overview
This project builds a simple chatbot that interacts with users and generates responses using basic NLP techniques. The chatbot simulates conversation flow and handles multiple user queries.
Objective
To develop a conversational chatbot that accepts user input and provides meaningful responses.
* Features
User input handling
Response generation
Continuous conversation
Exit condition (exit / quit)
*Workflow
User Input → Processing → Response → Loop
💬 Sample Output
You: hello  
Bot: Hello! Nice to meet you.
You: what is ai  
Bot: Artificial Intelligence is the simulation of human intelligence by machines.
You: exit  
Bot: Goodbye!
Limitation
Due to environment limitations (transformers not supported), a rule-based chatbot is implemented.
🛠️ Tech UsedPython
Jupyter Notebook
Regular Expressions
✅ Conclusion
The chatbot demonstrates basic NLP concepts and provides simple interactive responses.

**NLP Assignment 4: Fine-Tuning BERT on IMDB Dataset**

## 📌 Objective

The objective of this assignment is to understand and implement fine-tuning of a pre-trained BERT model for text classification using a real-world dataset.

## Dataset

* Dataset used: **IMDB Movie Reviews**
* Source: Kaggle / Hugging Face Datasets
* Total samples: 25,000 (reduced subset used for faster training)

## 🔄 Workflow

### 1. Data Loading

The dataset was loaded using the Hugging Face `datasets` library and converted into a pandas DataFrame.
### 2. Data Preprocessing

* Converted text to lowercase
* Removed HTML tags
* Removed special characters
* Cleaned the dataset for better model performance

### 3. Data Splitting

The dataset was divided into:

* Training set
* Validation set
* Test set

### 4. Tokenization

* Used `bert-base-uncased` tokenizer
* Converted text into token IDs
* Applied padding and truncation

### 5. Model Building

* Used `AutoModelForSequenceClassification`
* Loaded pre-trained BERT model
* Configured for binary classification

### 6. Fine-Tuning

* Optimizer: AdamW
* Learning rate: 2e-5
* Model trained on training dataset

## ⚠️ Note

Due to computational limitations (CPU-based execution), the evaluation phase (accuracy, precision, recall, F1 score, confusion matrix) and advanced experiments could not be fully executed.


## 📊 Expected Outcomes

* A fine-tuned BERT model capable of classifying movie reviews as positive or negative
* Improved understanding of transformer-based models

## 🛠️ Tools & Technologies
* Python
* Hugging Face Transformers
* PyTorch
* Google Colab

## 📌 Conclusion
This assignment helped in understanding how pre-trained transformer models like BERT can be fine-tuned for NLP tasks. Despite computational limitations, the implementation of preprocessing, tokenization, and model training was successfully completed.

## Submission
* GitHub Repository: (Add your link here)
* LinkedIn Post: (Add your link here)

**NLP Assignment 5: POS Tagging & Chunking**
This task focuses on token classification using transformer-based techniques for POS tagging and chunking.
Text data is tokenized and processed, and labels are aligned for sequence prediction.
Model performance is evaluated using Precision, Recall, and F1 Score.
Inference is demonstrated on custom sentences with predicted POS and chunk labels.
A comparison between POS tagging and chunking is also included.
