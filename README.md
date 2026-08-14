# Language Detector

A deployed Streamlit app that detects the language of any typed or pasted
text in real time.

## Overview

Character-level TF-IDF features feed a Linear SVM classifier. The app shows
a live confidence score alongside the prediction and includes one-click
example buttons (English, French, Spanish) for a quick demo.

## Tech Stack

scikit-learn (Linear SVM) · Streamlit

## How to Run

```bash
pip install -r requirements.txt
streamlit run app.py
```

Requires `model.pkl` and `vectorizer.pkl` in the working directory.
