 Task 1

# News Topic Classifier Using BERT

## Overview

This project implements a News Topic Classification system using the BERT transformer model. The model is fine-tuned on the AG News Dataset to automatically classify news headlines into predefined categories.

## Objective

* Fine-tune the BERT (bert-base-uncased) model.
* Classify news headlines into topic categories.
* Evaluate performance using Accuracy and F1-Score.
* Deploy the model using Gradio.

## Dataset

AG News Dataset (Hugging Face)

Categories:

* World
* Sports
* Business
* Sci/Tech

## Technologies Used

* Python
* Hugging Face Transformers
* PyTorch
* Scikit-learn
* Gradio
* Pandas
* Matplotlib

## Project Workflow

1. Dataset Loading
2. Text Preprocessing and Tokenization
3. BERT Fine-Tuning
4. Model Evaluation
5. Model Deployment

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## Results

The fine-tuned BERT model achieved high classification performance with an accuracy above 90%.

## Project Structure

News-Topic-Classifier-BERT/
│
├── News_Classifier.ipynb
├── app.py
├── requirements.txt
├── README.md
├── screenshots/
└── saved_model/

## Skills Gained

* Natural Language Processing (NLP)
* Transformer Models
* Transfer Learning
* Text Classification
* Model Deployment

## Author

Ali Shakeel
DevelopersHub Corporation Internship Program

### README.md — Task 2

# End-to-End ML Pipeline for Customer Churn Prediction

## Overview

This project develops a production-ready Machine Learning Pipeline using Scikit-learn for predicting customer churn in a telecom company.

## Objective

* Build a reusable ML pipeline.
* Automate preprocessing using Pipeline API.
* Train and compare multiple machine learning models.
* Optimize performance using GridSearchCV.
* Export the trained pipeline using Joblib.

## Dataset

Telco Customer Churn Dataset

Target Variable:

* Churn (Yes/No)

## Technologies Used

* Python
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Joblib

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Feature Engineering
4. Pipeline Construction
5. Model Training
6. Hyperparameter Tuning
7. Model Evaluation
8. Pipeline Export

## Models Used

* Logistic Regression
* Random Forest Classifier

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## Results

Random Forest achieved the best performance after hyperparameter tuning and was selected as the final model.

## Project Structure

Customer-Churn-ML-Pipeline/
│
├── Customer_Churn_Pipeline.ipynb
├── customer_churn_pipeline.pkl
├── requirements.txt
├── README.md
├── dataset/
├── screenshots/
└── src/

## Skills Gained

* ML Pipeline Construction
* Hyperparameter Tuning
* Feature Engineering
* Model Serialization
* Production-Ready ML Development

## Author

Ali Shakeel
DevelopersHub Corporation Internship Program

### README.md — Task 3

# Intelligent Support Ticket Tagging Using LLM

## Overview

This project uses Large Language Models (LLMs) to automatically classify customer support tickets into relevant categories and generate the top three most probable tags.

## Objective

* Implement support ticket classification using LLMs.
* Compare Zero-Shot and Fine-Tuned approaches.
* Apply Few-Shot Prompt Engineering.
* Generate Top-3 Category Predictions.

## Dataset

Free-Text Support Ticket Dataset

Sample Categories:

* Billing
* Technical Support
* Account Access
* Subscription
* Shipping
* Refund
* Complaint
* Product Inquiry

## Technologies Used

* Python
* Hugging Face Transformers
* OpenAI API (Optional)
* Scikit-learn
* Pandas
* Matplotlib
* Seaborn

## Project Workflow

1. Dataset Loading
2. Text Preprocessing
3. Zero-Shot Classification
4. Few-Shot Prompt Engineering
5. Fine-Tuned Model Training
6. Performance Comparison
7. Top-3 Tag Prediction

## Approaches Implemented

### Zero-Shot Learning

Uses a pre-trained language model without additional training.

### Few-Shot Learning

Uses prompt engineering with examples to improve classification performance.

### Fine-Tuned Model

Fine-tunes a transformer model on the support ticket dataset for maximum accuracy.

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## Results

Fine-tuned transformer models outperformed zero-shot and few-shot approaches, achieving the highest classification accuracy.

## Project Structure

LLM-Support-Ticket-Tagging/
│
├── Support_Ticket_Classification.ipynb
├── support_tickets.csv
├── requirements.txt
├── README.md
├── screenshots/
├── models/
└── src/

## Skills Gained

* Prompt Engineering
* Large Language Models
* Zero-Shot Learning
* Few-Shot Learning
* Multi-Class Classification
* Ranking and Recommendation Systems

## Author

Ali Shakeel
DevelopersHub Corporation Internship Program
