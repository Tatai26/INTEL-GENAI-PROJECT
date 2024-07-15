# INTEL-GENAI-PROJECT

## Overview
The Typo Detector project utilizes cutting-edge natural language processing techniques to identify and correct typographical errors in text. It incorporates a BERT model that has been fine-tuned specifically for the tasks of typo detection and correction. To achieve high performance and low latency in real-time applications, the model leverages Intel's OpenVINO toolkit for efficient inference on Intel AI hardware platforms.

## Unique Idea
The essence of this project lies in its ability to detect and correct typographical errors in text efficiently. The solution employs a fine-tuned BERT model trained on a dataset comprising sentences with and without typographical errors. Once trained, the model is converted into the OpenVINO format to optimize performance on Intel CPUs, making it ideal for real-time typo correction in various applications.

## Features
- *Typo Detection*: Precision in identifying sentences with typographical errors.
- *Typo Correction*: Offers corrections for sentences identified with errors.
- *Efficient Inference*: Uses OpenVINO toolkit to optimize inference processes on CPU, enhancing speed and efficiency.
- *Scalability*: The model can be seamlessly integrated into broader applications, including word processors, chatbots, and automated proofreading tools.
- *User-friendly Interface*: Provides a straightforward interface for users to input text and obtain both detection and correction of typographical errors.

## Technologies Used
- *BERT (Bidirectional Encoder Representations from Transformers)*: Utilizes this transformer-based model, which is pre-trained on vast text data for enhanced natural language understanding.
- *Transformers Library*: Assists in fine-tuning the BERT model, equipped with pre-trained models and necessary tools.
- *PyTorch*: An essential open-source library for model training and fine-tuning.
- *OpenVINO (Open Visual Inference and Neural Network Optimization)*: Intel's toolkit for model optimization and deployment.
- *Datasets Library*: Facilitates loading and preprocessing the dataset for model training and evaluation.
- *Pandas*: Employs this library for efficient data manipulation and analysis.
- *Python*: The core programming language used to develop and implement the entire solution.

## Getting Started
### Prerequisites
To get started with the Typo Detector project, ensure the following libraries are installed on your system:
```bash
pip install openvino transformers torch datasets pandas
