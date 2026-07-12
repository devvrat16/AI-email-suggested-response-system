# AI Email Suggested Response System
# Hiver Challenge
## Overview

This project generates intelligent email responses using Retrieval-Augmented Generation (RAG).

The system retrieves the most similar historical emails using TF-IDF and Cosine Similarity and uses a Large Language Model (LLM) to generate a professional response.

It also evaluates the generated response using multiple evaluation metrics.

---

## Features

- Synthetic email dataset
- Retrieval using TF-IDF
- AI-generated email responses
- Automatic evaluation
- Overall accuracy score

---

## Dataset

The dataset is synthetically created and contains customer support email conversations.

Categories include:

- Refund
- Shipping
- Replacement
- Support
- Subscription
- General Queries

The dataset is representative of real customer service conversations and is suitable for demonstrating Retrieval-Augmented Generation.

---

## Response Generation

Pipeline

Incoming Email

↓

TF-IDF Vectorizer

↓

Cosine Similarity

↓

Top 3 Similar Emails

↓

LLM

↓

Suggested Response

---

## Evaluation

The generated response is evaluated using

- Semantic Similarity
- ROUGE-L Score

Overall Score

Overall = 70% Semantic Similarity + 30% ROUGE-L

---

## Results

Example

Semantic Similarity : 53.09

ROUGE-L : 53.33

Overall : 53.16

---

## How to Run

Install dependencies

```
pip install -r requirements.txt
```

Run the notebook

```
AI_Email_Response_System.ipynb
```

---

## AI Tools Used

- ChatGPT
- LLM API
- Scikit-learn
