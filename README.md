🤖 AI vs Human Text Detection

A machine learning-based system that distinguishes between AI-generated and human-written text using a combination of statistical text representations and linguistic features.

⚠️ Note: This project is designed to run on Google Colab and uses Google Drive for data storage. Local execution setup is not included.

🚀 Features
🧠 Detects AI-generated vs human-written text
🔍 Uses TF-IDF with unigrams and bigrams for text representation
📊 Incorporates linguistic features (POS ratios, readability scores)
🌲 Robust classification using Random Forest algorithm
☁️ Fully compatible with Google Colab environment
🧠 Model Overview
Algorithm: Random Forest Classifier
Text Features:
TF-IDF (Unigrams + Bigrams)
Linguistic Features:
Part-of-Speech (POS) tag ratios
Readability metrics (e.g., sentence complexity, word length)
🛠️ Tech Stack
Language: Python
Libraries:
Scikit-learn
Pandas, NumPy
NLTK / spaCy (for linguistic features)
Platform: Google Colab
