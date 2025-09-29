# Fake News Detection System

A machine learning system to detect fake news using techniques like TF-IDF, Bag of Words, and N-grams, with models such as Logistic Regression, SVM, Decision Tree, etc.

## 🚀 Table of Contents

- [Overview](#overview)  
- [Features](#features)  
- [Architecture / Workflow](#architecture--workflow)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Installation](#installation)  
  - [Usage](#usage)  
- [Model Training & Evaluation](#model-training--evaluation)  
- [Project Structure](#project-structure)  
- [Datasets](#datasets)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Overview

This project aims to build a **Fake News Detection System**.  
It uses text-based features (TF-IDF, Bag of Words, N-grams) and trains classical machine learning classifiers (e.g. Logistic Regression, SVM, Decision Tree) to classify news articles as **real** or **fake**.

---

## Features

- Text preprocessing (cleaning, tokenization, stop-word removal)  
- Feature extraction:  
  - Bag of Words  
  - TF-IDF  
  - N-grams  
- Multiple classification models  
- Model evaluation (accuracy, precision, recall, F1 score)  

---

## Architecture / Workflow

1. **Data Load & Preprocess**  
   - Read raw text  
   - Clean (remove punctuation, lowercasing, etc.)  
   - Tokenize & remove stopwords  
2. **Feature Engineering**  
   - Create numerical vectors (BoW, TF-IDF, N-grams)  
3. **Model Training & Tuning**  
   - Train Logistic Regression, SVM, Decision Tree, etc.  
   - Tune hyperparameters  
4. **Evaluation**  
   - Use held-out test set  
   - Report metrics like accuracy, precision, recall, F1  
5. **Inference / Prediction**  
   - Given new text, preprocess → extract features → predict class  

---

## Getting Started

### Prerequisites

- Python 3.7+  
- pip  
- (Optional) Virtual environment tool (venv, conda, etc.)

### Installation

```bash
# Clone the repo
git clone https://github.com/KanavSingla28-k/Fake_News_Detection_System.git
cd Fake_News_Detection_System

# (Optional) create & activate virtual env
python3 -m venv venv
source venv/bin/activate     # On Linux/Mac
venv\Scripts\activate        # On Windows

# Install dependencies
pip install -r requirements.txt
