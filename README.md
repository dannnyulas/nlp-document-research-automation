# NLP Document Research & Automation Pipeline

An end-to-end Python NLP workflow for researching and analysing unstructured text.

## Pipeline

Documents → Processing → Search → Evidence Retrieval → Summarisation → Transformer Analysis → Reliability Checks → Human Review Flag → Structured Output

## Key Features

• Word and character TF-IDF document retrieval
• Cosine-similarity evidence ranking
• Extractive query-focused summarisation
• Pretrained DistilBERT sentiment analysis
• VADER baseline comparison
• Human-in-the-loop reliability checks
• Structured JSON output for downstream automation

## Model Results

VADER:
Accuracy: 70%
F1: 0.737

DistilBERT:
Accuracy: 84%
F1: 0.837

DistilBERT was selected for the final pipeline based on its higher F1 score.

## Tools

Python, PyTorch, Hugging Face Transformers, Scikit-learn, Pandas, NumPy, VADER
