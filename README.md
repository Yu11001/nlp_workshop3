# Text Processing for Workshop 3

## Intro

This Python script performs several text processing tasks on a given input file (`spam.csv`). The operations include:

- Cleaning the text: Remove special chars, numbers, and extra spaces
- Tokenizing it into sentences and words
- Lowercasing and Stop word removal
- Emoticons, Stemming and Lemmatization

The processed results are saved into respective output files.

---

## Input and Output Files

### Input

- **`./data/spam.csv`:** The original csv file.

### Output

- **`./data/results.csv`:** a clean version.

---

## Required Libraries

- **`nltk`**- Natural Language Toolkit
- **`re`**- Regular Expressions
- **`collections`**- Counter
- **`numpy`**
- **`pandas`**
- **`string`**

## Recommended Versions

- **`python`**- here used version 3.12.3

---

### **Installation:**

- clone the repository to local pc

```python
    pip install nltk, numpy, pandas
```
