A deep learning NLP project that classifies sentences from medical research abstracts into predefined sections such as Background, Objective, Methods, Results, and Conclusions.

This project is inspired by the idea behind SkimLit, a tool designed to help researchers quickly skim through scientific papers by structuring abstracts automatically.

Project Overview

Medical research abstracts contain multiple types of sentences, each serving a different purpose. This project builds several NLP models using TensorFlow and compares their performance for classifying abstract sentences.

The notebook explores:

Traditional machine learning baseline models
Deep learning sequence models
Transfer learning with pretrained embeddings
Character-level embeddings
Hybrid token + character embedding architectures
Positional embeddings
Model comparison and evaluation

Dataset

The project uses the PubMed 20k RCT dataset, a benchmark dataset for sequential sentence classification in medical abstracts.

Each sentence in an abstract is labeled as one of the following:

1.Background
2. Objective
3. Methods
4. Results
5. Conclusions

Workflow 

1. Load and preprocess dataset
2. Visualize class distribution
3. Encode labels
4. Build baseline ML model
5. Train deep learning models
6. Experiment with embeddings
7. Evaluate performance
8. Compare model results
9. Save and reload best model
10. Predict on unseen examples

Evaluation Metrics

The models are evaluated using:

1. Accuracy
2. Precision
3. Recall
4. F1-Score
