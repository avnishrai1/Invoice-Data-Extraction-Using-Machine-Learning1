# Invoice Text Processing with LayoutLM and ONNX

This project aims to develop a Python application to extract key information from invoices using machine learning. The solution handles various invoice formats in English, Dutch, and French without hardcoded labels, understanding the context to accurately extract information.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Documentation](#documentation)
- [Evaluation Criteria](#evaluation-criteria)
- [License](#license)

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


