[Read in English](README.md)

# 專案標題
ClinCaseCipher：使用 T5-Efficient-BASE-DL2 進行醫學數據的隱私保護與標準化

## 描述
本專案是使用 Jupyter 筆記本進行資料前處理、模型訓練和預測的全面指南。專案分為三個主要部分：

1. `preprocessing.ipynb`：該筆記本用於資料前處理，為模型訓練準備資料。
2. `fine_tune_model.ipynb`：此筆記本重點在於訓練模型，對其進行微調以達到理想的準確率。
3. `predict.ipynb`：在這個筆記本中，使用訓練好的模型進行預測，並包括基於規則的和後處理步驟。

![流程圖](image/ai-cup-Fig1.png)
## 圖一、流程圖

![錯誤分析](image/ai-cup-Fig2.png)
## 圖一、模型生成結果-錯誤分析

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
