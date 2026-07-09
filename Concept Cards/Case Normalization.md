# Case Normalization

## Definition

Case Normalization is the process of converting all text into a single letter case, usually lowercase, to ensure consistency during text processing. It is an important preprocessing step in Natural Language Processing (NLP).

---

## Purpose

The purpose of Case Normalization is to eliminate differences between uppercase and lowercase words so that the computer treats them as the same word. This improves the consistency and accuracy of text analysis.

---

## Working Principle

Case Normalization scans the input text and converts every alphabetic character into a common case, generally lowercase. This reduces duplicate representations of the same word caused only by differences in capitalization.

---

## Example

Original SMS:

Congratulations! YOU have WON a FREE Prize.

After Case Normalization:

congratulations! you have won a free prize.

---

## Role in Spam SMS Detection

Spam messages often contain words such as "FREE", "WIN", "OFFER", and "PRIZE" in uppercase to attract the user's attention. Case Normalization converts these words into lowercase, allowing the spam detection model to recognize them as the same keywords regardless of their capitalization.

---

## Advantages

- Improves consistency in text processing.
- Reduces duplicate words caused by different letter cases.
- Enhances feature extraction techniques like Bag of Words and TF-IDF.
- Improves machine learning model performance.

---

## Limitations

- Removes information where capitalization has meaning, such as proper nouns or abbreviations.
- May not be suitable for tasks where letter case carries important information.

---

## Applications

- Spam SMS Detection
- Email Spam Filtering
- Sentiment Analysis
- Search Engines
- Chatbots
- Machine Translation
