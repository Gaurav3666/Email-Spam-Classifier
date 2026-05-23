# Email Spam Classifier

## Overview
This project is a Machine Learning based Email Spam Classifier that predicts whether a message is spam or ham (not spam).  
The model is trained using Natural Language Processing (NLP) techniques and classification algorithms.

---

## Features
- Detects spam and non-spam messages
- Text preprocessing using NLP
- Tokenization and stemming
- TF-IDF vectorization
- Machine Learning model training
- High accuracy prediction system

---

## Dataset
The dataset contains labeled SMS/email messages.

### Columns
- Message → Text message
- Label → Spam or Ham

### Dataset Source
UCI SMS Spam Collection Dataset

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Jupyter Notebook

---

## NLP Preprocessing
The following preprocessing steps were performed:
- Lowercasing
- Removing special characters
- Tokenization
- Stopword removal
- Stemming/Lemmatization
- Text vectorization using TF-IDF

---

## Machine Learning Model

### Algorithms Tested
- Naive Bayes
- Logistic Regression
- Random Forest

### Final Selected Model
- Multinomial Naive Bayes

---

## Model Performance

### Accuracy Score
97.3%

### Confusion Matrix

| Actual / Predicted | Ham | Spam |
|-------------------|-----|------|
| Ham               | 970 | 3    |
| Spam              | 27  | 115  |

### Evaluation Metrics
- Precision
- Recall
- F1 Score

---

## Workflow
1. Data Collection
2. Data Cleaning
3. Text Preprocessing
4. Feature Extraction using TF-IDF
5. Model Training
6. Model Evaluation
7. Prediction System

---

## Installation

```bash
git clone <your-github-link>

pip install -r requirements.txt
```

---

## How to Run

1. Open Jupyter Notebook
2. Run all cells
3. Enter a custom message
4. Model predicts spam or ham

---

## Example

### Input
Congratulations! You won a free iPhone

### Prediction
Spam

---

## Future Improvements
- Deploy using Flask or Streamlit
- Improve model recall for spam detection
- Add deep learning models
- Build real-time email filtering system

---

## Author
Gaurav Kumar

Aspiring Data Scientist & Machine Learning Enthusiast
