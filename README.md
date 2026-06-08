# Email Spam Detection using Machine Learning

## Objective

The objective of this project is to build an intelligent spam detection system capable of classifying emails or messages as:

- Spam
- Not Spam (Ham)

---

## Dataset

The dataset contains:

- Message Text
- Label (Spam/Ham)

---

## Tools & Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Jupyter Notebook

---

## Steps Performed

### 1. Data Loading
- Loaded SMS Spam Collection dataset.

### 2. Data Cleaning
- Selected relevant columns.
- Renamed columns for better readability.

### 3. Label Encoding
- Converted:
  - Ham → 0
  - Spam → 1

### 4. Text Preprocessing
- Applied TF-IDF Vectorization.
- Removed common stop words.

### 5. Train-Test Split
- Split data into training and testing sets.

### 6. Model Building
- Implemented Multinomial Naive Bayes classifier.

### 7. Model Training
- Trained the classifier on transformed text data.

### 8. Evaluation
- Calculated:
  - Accuracy Score
  - Classification Report

### 9. Prediction
- Tested model on a custom message.

---

## Outcome

- Successfully classified messages as spam or non-spam.
- Achieved high accuracy using TF-IDF and Naive Bayes.
- Demonstrated practical application of Natural Language Processing (NLP).

---

## Libraries Used

```python
pandas
numpy
scikit-learn
