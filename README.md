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

