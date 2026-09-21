
# 📰 Fake News & Hate Speech Detection using NLP

A Natural Language Processing project focused on detecting **fake news** and **hate speech** from textual data using machine learning and NLP techniques.

The project includes two major tasks:

1. 📰 **Fake News Detection**
2. 🚨 **Hinglish Hate Speech Detection**

---

## 📰 Fake News Detection

The fake news dataset contains approximately **44,898 text samples** with the following features:

| Feature | Description          |
| ------- | -------------------- |
| `title` | News article title   |
| `text`  | News article content |
| `label` | Target class         |

```text
Title → 44,898 non-null
Text  → 44,898 non-null
Label → 44,898 non-null
```

### 🔤 NLP Preprocessing

The text data was processed using several NLP techniques:

* Stopword removal
* Contractions handling
* Lemmatization
* Bag of Words (BoW)
* TF-IDF
* Word2Vec

Example:

```python
import nltk
from nltk.stem import WordNetLemmatizer
from nltk.corpus import wordnet
```

### 🤖 Machine Learning Models


### 📈 Result

The best-performing model achieved approximately:

> **99% Accuracy**

on the evaluation dataset.

---

# 🚨 Hinglish Hate Speech Detection

A separate experiment was conducted for **hate speech detection on Hinglish social-media text**.

### Dataset

* Approximately **20,000 tweets**
* Language: **Hinglish**
* Task: Hate Speech Classification
* Dataset: **Highly imbalanced**

Because of the class imbalance, accuracy alone may not fully represent model performance.

### 📊 Result

The model achieved approximately:

> **74% Accuracy**

on the Hinglish hate-speech classification task.

For imbalanced datasets, metrics such as **Precision, Recall, F1-score, Macro F1, and Confusion Matrix** are also important for evaluating minority-class performance.

---

## 🛠️ Technologies & Techniques

* Python
* NLTK
* Pandas
* NumPy
* Scikit-learn
* CatBoost
* Natural Language Processing
* TF-IDF
* Bag of Words
* Word2Vec
* Text Classification
* Sentiment / Hate Speech Analysis

---

## 🔄 NLP Pipeline

```text
Raw Text
   ↓
Text Cleaning
   ↓
Contractions Removal
   ↓
Stopword Removal
   ↓
Lemmatization
   ↓
Text Vectorization
   ├── Bag of Words
   ├── TF-IDF
   └── Word2Vec
   ↓
Machine Learning Model
   ├── GBM
   └── CatBoost
   ↓
Classification
```

---

## 📊 Project Results

| Task                 | Dataset Size | Challenge           | Best Accuracy |
| -------------------- | -----------: | ------------------- | ------------: |
| Fake News Detection  |      ~44,898 | Text classification |       **99%** |
| Hinglish Hate Speech |      ~20,000 | Highly imbalanced   |       **74%** |

> **Note:** Reported accuracy depends on the dataset split and evaluation methodology. For the highly imbalanced Hinglish dataset, additional class-wise metrics should be considered alongside accuracy.

---



