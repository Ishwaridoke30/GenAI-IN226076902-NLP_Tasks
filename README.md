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
