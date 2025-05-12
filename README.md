# SinoPac AI GO 2025: Stock Prediction Pipeline  
永豐 AI GO 2025：股票預測流程

This repository contains a comprehensive machine learning pipeline developed for the 2025 SinoPac AI GO Competition, focusing on predicting high-growth stocks in the Taiwan market. The project encompasses data preprocessing, feature selection, model training using ensemble methods, and hyperparameter optimization with Optuna.

本專案為參加 2025 永豐 AI GO 競賽所開發，旨在預測台灣股市中的高增長股票。內容涵蓋資料預處理、特徵選擇、使用集成方法進行模型訓練，以及透過 Optuna 進行超參數優化。

---

## Project Structure 專案結構

| Notebook Name              | Description (English)                                     | 說明（中文）                           |
|----------------------------|------------------------------------------------------------|----------------------------------------|
| `ML_data_clean.ipynb`      | Data loading and preprocessing                             | 資料載入與預處理                        |
| `ML_feature_select.ipynb`  | Feature selection using correlation and VIF                | 使用相關係數與 VIF 進行特徵選擇         |
| `ML_main.ipynb`            | Model training with LGBM, XGBoost, and CatBoost            | 使用 LGBM、XGBoost、CatBoost 進行模型訓練 |
| `ML_optuna.ipynb`          | Hyperparameter tuning with Optuna                          | 使用 Optuna 進行超參數調整              |

---

## Features 專案特點

- **Ensemble Models**：Implemented LightGBM, XGBoost, and CatBoost for robust predictions.
- **Hyperparameter Optimization**：Utilized Optuna for efficient hyperparameter tuning.
- **Feature Engineering**：Applied statistical methods for feature selection to enhance model performance.
- **Competition Alignment**：Designed in accordance with the requirements of the 2025 SinoPac AI GO Competition.

- **集成模型**：實現了 LightGBM、XGBoost 和 CatBoost，以提供穩健的預測。
- **超參數優化**：使用 Optuna 進行高效的超參數調整。
- **特徵工程**：應用統計方法進行特徵選擇，以提升模型效能。
- **競賽對齊**：專案設計符合 2025 永豐 AI GO 競賽的需求。
  
---

## Sample Results  
範例結果與競賽表現

This project ranked **14th out of 868 teams** in the 2025 SinoPac AI GO stock prediction competition, demonstrating strong predictive capability in a highly competitive environment.  
Final submission achieved an **F1 Score of 0.8615**, reflecting a well-balanced performance between precision and recall in binary stock movement classification.

本專案在 2025 年永豐 AI GO 股票預測競賽中，從 **868 支隊伍中脫穎而出，榮獲第 14 名**，展現出在高度競爭環境下的優異預測能力。  
最終提交結果達成 **F1 分數 0.8615**，在漲跌二分類預測中兼顧精確率與召回率，顯示模型判斷穩定且泛化能力佳。

Key Achievements | 核心成果：
- Ranked Top 2% in national-level quantitative modeling competition  
  國內量化建模競賽前 1.6%% 佳績
- Final F1 Score: **0.8615**
- Balanced ensemble approach using LGBM, XGBoost, and CatBoost
- Efficient Optuna tuning contributed to +5~10% performance gain

---

##  Requirements 環境需求
- Python 3.9+
- 套件需求：
  ```bash
  pip install pandas numpy matplotlib scikit-learn lightgbm xgboost catboost optuna

---
## 作者 Author

莊宗瀚 (Tsung Han Chuang)  
[GitHub](https://github.com/CTHQuant) ｜ [LinkedIn](https://linkedin.com/in/宗瀚-莊-1a8588358/)

---
## License 授權條款
This project is for educational and demonstration purposes only.
