## SMS Spam Classification System
The Email/SMS Spam Classifier is a machine learning project that identifies whether a given message is spam or not. It uses Natural Language Processing (NLP) techniques (Stemming and TF-IDF Vectorization) for text transformation and a trained Multinomial Naive Bayes Classifier for predictions.
## Directory Structure:
```
Directory structure:
└── 04bhavyaa-sms-spam-classification-system/
    ├── artifacts/
    │   ├── vectorizer.pkl
    │   ├── model.pkl
    │   └── spam.csv
    ├── app.py
    ├── sms-spam-classification.ipynb
    ├── requirements.txt
    ├── nltk.txt
    └── README.md
```
### Key Features
- Input a message through the user interface.
- Classify the message as Spam or Not Spam.
- Built with Streamlit for the web interface.
### How It Works
1. Input Transformation:
  - Converts the input message to lowercase.
  - Removes stopwords, punctuation, and non-alphanumeric characters.
  - Stems the words to their root forms using the Porter Stemmer.
2. Vectorization:
  - The transformed text is vectorized using a pre-trained TfidfVectorizer.
3. Prediction:
  - The vectorized text is fed into a pre-trained Multinomial Naive Bayes Model.
  - Outputs whether the message is Spam or Not Spam.
### Images:
![image](https://github.com/user-attachments/assets/63ea2b4a-901f-4fbd-9499-2fbc547b9dc7)
![image](https://github.com/user-attachments/assets/5938f614-a635-44d1-98ae-405e8915675b)

