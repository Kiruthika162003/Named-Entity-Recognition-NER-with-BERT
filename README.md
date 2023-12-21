# Named Entity Recognition (NER) with BERT

## Overview
This project implements Named Entity Recognition (NER) using the BERT (Bidirectional Encoder Representations from Transformers) model. NER is a natural language processing task that involves identifying and classifying entities such as people, organizations, locations, time expressions, and more within a given text.

## Dataset
The dataset used for training and evaluation contains information about various entities, including geographical entities, organizations, persons, geopolitical entities, time indicators, artifacts, events, and natural phenomena. The dataset is preprocessed to handle null values and ensure a clean input for the model.

## Dataset Statistics
- Total Rows: 838,860
- Unique Tags: 17
- Unique Words: 35,178

## Model Training
The model is trained using the BERT architecture, a state-of-the-art transformer-based model. The training process involves encoding input sequences and fine-tuning the model to accurately predict entity labels for each token in the text.

## Evaluation Metrics
The model's performance is evaluated using several metrics:
- **Evaluation Loss:** 0.1694
- **F1 Score:** 0.7850
- **Precision:** 0.8124
- **Recall:** 0.7595

These metrics provide insights into the model's ability to correctly classify entities and its overall performance on the test data.

## Prediction Example
A sample prediction is demonstrated using the trained model. The model successfully identifies and labels entities in the provided text, showcasing its practical application.

## Usage
To utilize the NER model for your specific use case:
1. **Data Preparation:** Ensure your dataset is formatted similarly to the provided one, with columns for sentence ID, words, part-of-speech (POS), and labels.
2. **Model Training:** Adapt the provided code for model training, adjusting parameters as needed for your dataset size and characteristics.
3. **Evaluation:** Evaluate the model's performance using relevant metrics to gauge its accuracy and effectiveness.
4. **Prediction:** Utilize the trained model for entity recognition in new texts or documents.

Feel free to customize the code and integrate it into your projects. If you have any inquiries or suggestions, please feel free to reach out!
