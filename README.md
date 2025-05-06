# Sentiment-Analysis
*COMPANY*: CODTECH IT SOLUTIONS

*NAME*:CHAITANYA NAMDEO

*INTERN ID*:CT04DL130

*DOMAIN*:DATA ANALYTICS

*DURATION*:4 WEEKS

*MENTOR*:NEELA SANTHOSH 

Sentiment Analysis on IMDB Movie Reviews
This script performs binary sentiment classification (positive vs. negative) on movie reviews using the IMDB dataset. The main steps include:
 1. Library Imports
Essential Python libraries such as:pandas, numpy for data handling.
nltk for natural language processing.
sklearn for machine learning model building and evaluation.
matplotlib, seaborn for visualization.
2. NLTK Resource Downloads
Downloads necessary resources like:punkt (tokenizer)
stopwords (common English words to exclude)
wordnet (lemmatization base)
3. Dataset Loading
Loads the IMDB dataset from a CSV file with two columns:
review: the actual text
sentiment: 'positive' or 'negative' (later converted to 1 or 0)
 4. Text Preprocessing
Each review is cleaned through:Lowercasing,Tokenization,Stopword removal,Lemmatization (reduces words to base form)
5. TF-IDF Vectorization
The cleaned reviews are converted into numeric feature vectors using TF-IDF, limited to the top 5000 features for efficiency.
6. Model Training
The data is split into training and test sets (80-20), and a Logistic Regression classifier is trained to predict sentiment.
7. Model Evaluation
Accuracy and classification report (precision, recall, F1-score) are printed.
A confusion matrix heatmap visualizes true vs. predicted sentiment classes.
8. Data Insight
A bar chart shows the distribution of sentiments in the original dataset.
9. Custom Review Prediction
Tests the trained model on a new custom review and outputs the predicted sentiment.

*OUTPUT*:
Accuracy: 88.62%
Classification Report:
              precision    recall  f1-score   support

           0       0.90      0.87      0.88      4961
           1       0.88      0.90      0.89      5039

    accuracy                           0.89     10000
   macro avg       0.89      0.89      0.89     10000
weighted avg       0.89      0.89      0.89     10000
![image](https://github.com/user-attachments/assets/3a0c9f04-5950-4d59-8fb4-0057cab175d5)
![image](https://github.com/user-attachments/assets/ee1ec563-3edd-4ab6-a900-fb1c61d114aa)



