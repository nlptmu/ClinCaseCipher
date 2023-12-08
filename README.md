[![中文版](https://img.shields.io/badge/README-中文-blue.svg)](README_Chinese.md)
[![made-with-Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=flat&logo=Jupyter)](https://jupyter.org/)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nlptmu/ClinCaseCipher)

# Project Title
ClinCaseCipher: Privacy Preservation and Standardization in Medical Data using T5-Efficient-BASE-DL2

## Description
This project is a comprehensive guide to data preprocessing, model training, and prediction using Jupyter Notebooks. The project is structured into three main parts:

1. `preprocessing.ipynb`: This notebook is used for data preprocessing, preparing the data for model training.
[![Colab](https://img.shields.io/badge/Colab-preprocessing-orange)](https://colab.research.google.com/github/nlptmu/ClinCaseCipher/blob/main/preprocessing.ipynb)
2. `fine_tune_model.ipynb`: This notebook focuses on training the model, fine-tuning it to achieve the desired accuracy.
[![Colab](https://img.shields.io/badge/Colab-fine_tune_model-orange)](https://colab.research.google.com/github/nlptmu/ClinCaseCipher/blob/main/fine_tune_model.ipynb)
3. `predict.ipynb`: In this notebook, the trained model is used for making predictions and includes steps for rule-based and post-processing procedures.
[![Colab](https://img.shields.io/badge/Colab-predict-orange)](https://colab.research.google.com/github/nlptmu/ClinCaseCipher/blob/main/predict.ipynb)

<p align="center">
  <img src="image/ai-cup-Fig1.png" alt="Flowchart"/>
</p>
<h2 align="center">Fig1. Flowchart</h2>

<p align="center">
  <img src="image/ai-cup-Fig2.png" alt="Error Analysis"/>
</p>
<h2 align="center">Fig2. Model generation results-Error Analysis</h2>

## Data Privacy Notice
Due to the sensitive nature of medical data and stringent privacy requirements, the datasets used in this project are not publicly available. The privacy and confidentiality of patient data are our utmost priorities, and we adhere to HIPAA and other relevant regulations to ensure data security. Consequently, the Colab notebooks provided are primarily for demonstration purposes, showcasing the code structure and output formats. They are not executable in their current form as they require access to private datasets.

## Installation

### Prerequisites
- Python 3.x
- CUDA 11.7 for GPU acceleration (optional, but recommended)

### Setup
To set up the project environment, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/nlptmu/ClinCaseCipher
   cd ClinCaseCipher
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

### PyTorch and CUDA Compatibility
This project uses PyTorch 2.0.1. For optimal performance, it is recommended to use CUDA 11.7 for GPU acceleration. Ensure that your system has CUDA 11.7 installed.

## Usage
Follow the sequence of notebooks for end-to-end processing:
1. Run `preprocessing.ipynb` for initial data preparation.
2. Use `fine_tune_model.ipynb` for model training.
3. Execute `predict.ipynb` for predictions and post-processing.

## License
This project is licensed under the Apache-2.0 License - see the LICENSE file in the repository for details.
