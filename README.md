🧠 Automated Medical Text Summarization using NLP and Transformer Models
📌 Project Overview

This project focuses on multi-label text classification of biomedical research articles from the PubMed dataset.
The goal is to automatically classify biomedical text into multiple relevant categories using Transformer-based deep learning models.

Natural Language Processing (NLP) techniques such as tokenization, stopword removal, and text preprocessing are applied before training the models.

📂 Dataset

The dataset used for this project is the PubMed Multi-Label Text Classification dataset.

It contains:

Biomedical research article abstracts

Multiple labels assigned to each abstract

These labels represent different biomedical categories.

⚙️ Methodology

The workflow followed in this project includes:

1️⃣ Dataset Collection
The PubMed dataset containing biomedical abstracts and labels was collected.

2️⃣ Tokenization
The text data was converted into tokens for processing.

3️⃣ Stopword Removal
Common words that do not contribute to meaning were removed.

4️⃣ Text Preprocessing
Text cleaning steps such as lowercasing, punctuation removal, and normalization were applied.

5️⃣ Transformer Models Applied
The following transformer models were used for text classification:

T5 (Text-to-Text Transfer Transformer)

BioGPT

PEGASUS

These models help in understanding biomedical language effectively.

📊 Model Evaluation

The models were evaluated using the following metrics:

Accuracy

Precision

Recall

F1 Score

These metrics help measure how well the models classify biomedical text into multiple categories.

📈 Results and Comparison

After training the models, their performance was compared using evaluation metrics.

The comparison helps identify which model performs best for multi-label biomedical text classification.

🛠 Technologies Used

Python

Natural Language Processing (NLP)

Transformer Models

Pandas

NumPy

Scikit-learn

Hugging Face Transformers

📷 Workflow

Dataset Collection
→ Tokenization
→ Stopword Removal
→ Text Preprocessing
→ Transformer Models (T5, BioGPT, PEGASUS)
→ Model Evaluation
→ Predicted Results

🎯 Conclusion

This project demonstrates how transformer-based models can effectively classify biomedical text into multiple categories, improving information retrieval and knowledge discovery in biomedical research.
