# News Topic Classification using BERT

## Objective of the Task
The objective of this project is to build an automated system that classifies news headlines into predefined topic categories using a transformer-based deep learning model. The goal is to leverage transfer learning to achieve high classification accuracy with minimal manual feature engineering.

## Methodology / Approach
- Used the AG News dataset containing news headlines across four categories: World, Sports, Business, and Sci/Tech.
- Tokenized and preprocessed text using the BERT tokenizer.
- Fine-tuned the bert-base-uncased model for sequence classification using Hugging Face Transformers.
- Evaluated model performance using Accuracy and F1-score.
- Deployed the trained model using Gradio for real-time headline classification.

## Key Results / Observations
- Achieved 95% accuracy and F1-score, demonstrating strong model performance.
- The model effectively captures contextual semantics in news headlines, even for overlapping categories.
- Results highlight the effectiveness of transformer-based transfer learning for NLP classification tasks.

