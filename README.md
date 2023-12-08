[中文版](README_Chinese.md)

[![Colab](https://img.shields.io/badge/Colab-fine_tune_model-orange)](https://colab.research.google.com/github/nlptmu/ClinCaseCipher/blob/main/fine_tune_model.ipynb)

[![Colab](https://img.shields.io/badge/Colab-predict-orange)](https://colab.research.google.com/github/nlptmu/ClinCaseCipher/blob/main/predict.ipynb)

[![Colab](https://img.shields.io/badge/Colab-preprocessing-orange)](https://colab.research.google.com/github/nlptmu/ClinCaseCipher/blob/main/preprocessing.ipynb)

# Project Title
ClinCaseCipher: Privacy Preservation and Standardization in Medical Data using T5-Efficient-BASE-DL2

## Description
This project is a comprehensive guide to data preprocessing, model training, and prediction using Jupyter Notebooks. The project is structured into three main parts:

1. `preprocessing.ipynb`: This notebook is used for data preprocessing, preparing the data for model training.
2. `fine_tune_model.ipynb`: This notebook focuses on training the model, fine-tuning it to achieve the desired accuracy.
3. `predict.ipynb`: In this notebook, the trained model is used for making predictions and includes steps for rule-based and post-processing procedures.

<p align="center">
  <img src="image/ai-cup-Fig1.png" alt="Flowchart"/>
</p>
<h2 align="center">Fig1. Flowchart</h2>

<p align="center">
  <img src="image/ai-cup-Fig2.png" alt="Error Analysis"/>
</p>
<h2 align="center">Fig2. Model generation results-Error Analysis</h2>

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
