# Tokenization

## Definition

Tokenization is the process of breaking a sentence or text into smaller units called **tokens**. These tokens are usually individual words, punctuation marks, or numbers. It is one of the most important preprocessing steps in Natural Language Processing (NLP).

---

## Purpose

The purpose of tokenization is to divide text into meaningful units so that a computer can analyze each token separately. This makes it easier to perform tasks such as spam detection, sentiment analysis, text classification, and machine translation.

---

## Working Principle

Tokenization scans the input text and separates it into individual tokens based on spaces, punctuation marks, or language-specific rules. Modern NLP libraries such as NLTK and spaCy use advanced tokenizers to correctly handle punctuation, contractions, abbreviations, and special characters.

---

## Example

Original SMS:

Congratulations! You have won ₹50,000. Click here to claim your prize.

After Tokenization:

- Congratulations
- You
- have
- won
- ₹50,000
- Click
- here
- to
- claim
- your
- prize

---

## Role in Spam SMS Detection

Tokenization helps convert an SMS into individual words so that the spam detection model can analyze important keywords such as "Congratulations", "Won", "Free", "Prize", and "Click". These keywords are commonly found in spam messages and help improve classification accuracy.

---

## Advantages

- Simplifies text processing.
- Enables feature extraction techniques like Bag of Words and TF-IDF.
- Improves the performance of NLP models.
- Supports efficient text analysis.

---

## Limitations

- Different languages require different tokenization rules.
- Informal text and emojis may be difficult to tokenize correctly.
- Incorrect tokenization may reduce model accuracy.

---

## Applications

- Spam SMS Detection
- Email Spam Filtering
- Sentiment Analysis
- Search Engines
- Chatbots
- Machine Translation
