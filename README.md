# Invoice Text Processing with LayoutLM and ONNX

This project aims to develop a Python application to extract key information from invoices using machine learning. The solution handles various invoice formats in English, Dutch, and French without hardcoded labels, understanding the context to accurately extract information.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Usage](#usage)
- [Documentation](#documentation)
- [Evaluation Criteria](#evaluation-criteria)

## Introduction

This project uses LayoutLM, a transformer-based model, and ONNX for optimization to process invoices. The solution involves training a model, optimizing it for deployment, and running it on a client desktop. The steps include data collection, preprocessing, model training, optimization, and deployment.

## Requirements

Ensure you have Python 3.8 or later installed. The following libraries are required:

- numpy
- pandas
- scikit-learn
- torch
- transformers
- onnx
- onnxruntime
- pytorch-lightning
- pdf2image
- pytesseract

## Usage
1. Data Collection
Collect a diverse dataset of invoices in PDF format from the internet. Ensure the dataset includes invoices in English, Dutch, and French.
Use OCR to convert PDFs to text.
2. Data Preprocessing
Clean and preprocess the extracted text.
Annotate the data to identify key information (e.g., sender, receiver, VAT number, amounts) without relying on hardcoded labels.
3. Model Training
Use a pre-trained LayoutLM model and fine-tune it on your annotated dataset.
Ensure the model understands context to extract information from various formats and languages.
Evaluate the model's performance and adjust parameters as necessary.
4. Model Optimization
Export the trained model to ONNX format.
Use techniques like quantization to reduce model size and improve performance.

## Documentation
For detailed documentation on the project approach, model architecture, training process, evaluation metrics, optimization techniques, deployment steps, and performance, refer to invoice_text_processing_documentation.docx.

## Evaluation Criteria
Data Handling: Ability to collect, preprocess, and annotate data, including handling multiple languages.
Model Training: Effectiveness in training and fine-tuning the model to handle diverse formats.
Optimization: Success in optimizing the model for deployment.
Deployment: Ability to set up the client environment and run the model.
Documentation: Clarity and completeness of the documentation and code repository.
