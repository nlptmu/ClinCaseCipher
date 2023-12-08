[![中文版](https://img.shields.io/badge/README-in-English-blue.svg)](README.md.md)
[![made-with-Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=flat&logo=Jupyter)](https://jupyter.org/)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nlptmu/ClinCaseCipher)

# 專案標題
ClinCaseCipher：使用 T5-Efficient-BASE-DL2 進行醫學數據的隱私保護與標準化

## 描述
本專案是使用 Jupyter 筆記本進行資料前處理、模型訓練和預測的全面指南。專案分為三個主要部分：

1. `preprocessing.ipynb`：該筆記本用於資料前處理，為模型訓練準備資料。
2. `fine_tune_model.ipynb`：此筆記本重點在於訓練模型，對其進行微調以達到理想的準確率。
3. `predict.ipynb`：在這個筆記本中，使用訓練好的模型進行預測，並包括基於規則的和後處理步驟。

<p align="center">
  <img src="image/ai-cup-Fig1.png" alt="Flowchart"/>
</p>
<h2 align="center">圖一、流程圖</h2>

<p align="center">
  <img src="image/ai-cup-Fig2.png" alt="Error Analysis"/>
</p>
<h2 align="center">圖二、模型生成結果 - 錯誤分析</h2>

## 資料隱私聲明
鑑於醫療數據的敏感性和嚴格的隱私要求，本項目中使用的數據集無法公開。病患資料的隱私與保密是我們最重視的事項，我們遵守HIPAA以及其他相關法規來確保數據安全。因此，提供的 Colab 筆記本主要用於展示代碼結構和輸出格式，僅供演示之用。由於它們需要訪問私有數據集，故目前的形式下無法執行。

## 安裝

### 先決條件
- Python 3.x
- CUDA 11.7 用於 GPU 加速（可選，但建議）

### 設置
要設置專案環境，請按照以下步驟操作：

1. 克隆倉庫：
  ```bash
  git clone https://github.com/nlptmu/ClinCaseCipher
  cd ClinCaseCipher
  ```

2. 安裝所需的包：
   ```bash
   pip install -r requirements.txt
   ```

### PyTorch 和 CUDA 兼容性
本專案使用 PyTorch 2.0.1。為了獲得最佳性能，建議使用 CUDA 11.7 進行 GPU 加速。確保您的系統已安裝 CUDA 11.7。

## 使用
按照筆記本的順序進行端到端處理：
1. 運行 `preprocessing.ipynb` 進行初始資料準備。
2. 使用 `fine_tune_model.ipynb` 進行模型訓練。
3. 執行 `predict.ipynb` 進行預測和後處理。

## 許可
本專案根據 Apache-2.0 許可證授權 - 有關詳細信息，請參見倉庫中的 LICENSE 文件。
