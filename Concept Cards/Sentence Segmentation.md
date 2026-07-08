# Sentence Segmentation

## Definition

Sentence Segmentation is the process of dividing a block of text into individual sentences. It is one of the first steps in Natural Language Processing (NLP) and helps the computer understand where one sentence ends and the next begins.

---

## Purpose

The main purpose of sentence segmentation is to organize text into meaningful sentences so that each sentence can be processed separately. This improves the accuracy of later NLP tasks such as tokenization, sentiment analysis, and spam detection.

---

## Working Principle

Sentence segmentation identifies sentence boundaries using punctuation marks such as:

- Full Stop (.)
- Question Mark (?)
- Exclamation Mark (!)

Modern NLP libraries also use machine learning models to correctly identify sentence boundaries, especially in complex text where punctuation alone is not sufficient.

---

## Example

Original SMS:

Congratulations! You have won ₹50,000. Click the link below to claim your prize.

After Sentence Segmentation:

Sentence 1:
Congratulations!

Sentence 2:
You have won ₹50,000.

Sentence 3:
Click the link below to claim your prize.

---

## Advantages

- Makes text easier to process.
- Improves the accuracy of NLP tasks.
- Helps in understanding the context of each sentence.
- Useful for summarization, translation, and spam detection.

---

## Limitations

- Incorrect punctuation can lead to wrong sentence boundaries.
- Informal messages may not contain proper punctuation.
- Abbreviations (e.g., Dr., Mr., etc.) can sometimes confuse simple segmentation methods.

---

## Applications

- Spam SMS Detection
- Email Spam Filtering
- Chatbots
- Machine Translation
- Text Summarization
- Sentiment Analysis
