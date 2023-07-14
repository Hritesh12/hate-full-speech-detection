# hate-full-speech-detection
Goal is to develop robust and scalable models that can accurately identify and classify hate speech in text data. 
This is a Python script that performs hate speech classification using natural language processing (NLP) techniques and machine learning algorithms. It uses the NLTK and scikit-learn libraries for text preprocessing, feature extraction, and model training. The goal is to classify text data into hate speech or non-hate speech categories.
You can install these dependencies using pip:
Copy code
pip install pandas nltk scikit-learn seaborn textstat
How to Use

Ensure that you have a CSV file named "HateSpeechData.csv" containing the dataset for hate speech classification. Adjust the file path in the script accordingly.

Run the script using Python.

The script performs the following steps:

Data Loading: The script reads the dataset from the CSV file using pandas.
Text Preprocessing: It tokenizes the text data, removes stopwords and punctuation, and performs stemming using NLTK.
Feature Extraction: It extracts features from the preprocessed text using the CountVectorizer and TfidfVectorizer from scikit-learn.
Model Training: It trains various machine learning models, including Logistic Regression, LinearSVC, RandomForestClassifier, and GaussianNB.
Model Evaluation: It evaluates the trained models using classification metrics such as accuracy, F1 score, and confusion matrix.
The script outputs the evaluation results and may generate visualizations, such as a confusion matrix using seaborn.

Dataset
The script assumes that you have a CSV file named "HateSpeechData.csv" that contains the dataset for hate speech classification. The dataset should have a text column containing the text data and a label column indicating whether the text is hate speech or not.

Please ensure that your dataset is appropriately formatted and labeled before running the script.
