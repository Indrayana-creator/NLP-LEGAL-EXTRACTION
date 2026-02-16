# Legal Entity Extraction from Indonesian Court Verdicts using NLP & Deep Learning

## Overview

This project builds an automated system to extract structured information from Indonesian legal verdict documents using Natural Language Processing and deep learning techniques.

The objective is to transform unstructured legal text into usable structured data for faster legal analysis.

## Project Pipeline

The workflow of the legal entity extraction system is illustrated below:

![Pipeline](assets/pipeline.png)
The pipeline consists of three main stages:

1. Data Preparation — document collection, cleaning, and manual labeling
2. Modeling — training multiple extraction models
3. Evaluation — comparison between deep learning and rule-based approaches

## Final Method Comparison

| Model         | Precision | Recall | F1 Score |
| ------------- | --------- | ------ | -------- |
| IndoLegalBERT | 0.94      | 0.89   | 0.93     |
| Rule-Based    | 0.69      | 0.57   | 0.60     |

IndoLegalBERT significantly outperformed the rule-based approach, demonstrating superior contextual understanding and entity extraction capability on Indonesian legal texts.

## Dataset

The dataset consists of Indonesian criminal court verdict documents in unstructured text format.
Documents were manually cleaned and annotated for Named Entity Recognition experiments.

The dataset is included for academic and reproducibility purposes.

## Models Implemented

* Regex baseline
* CRF
* BiLSTM
* BiLSTM-CRF
* IndoBERT

## Tech Stack

* Python
* PyTorch
* HuggingFace Transformers
* Scikit-learn

## Status

🚧 Actively improving documentation and adding demo inference notebook

## Author

Indrayana Widhikartiko
Data Science Student — Universitas Airlangga
