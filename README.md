## Model Summary Mandatory Tasks<b>  

Dataset Reference:
    https://github.com/ICCC-Platform/Air-Pollution-Image-Dataset-From-India-and-Nepal![image](https://github.com/user-attachments/assets/1d124aa7-71e0-4c1c-be38-2725ece0bf8c)

本專案使用 ResNet18 建立圖像分類模型，將每張圖片分類為下列 6 類之一：  
-    a_Good
-    b_Moderate
-    c_Unhealthy_for_Sensitive_Groups
-    d_Unhealthy
-    e_Very_Unhealthy
-    f_Severe  
---
模型訓練與驗證準確率皆超過 98%，顯示了測試集的以下評估指標：  
- Accuracy  
- Precision / Recall / F1-score（六類別）  
- Confusion Matrix（TestingSet）  
- 輸出 YU_submission.csv  

**Bonus Task (Regression)**  
額外實作了回歸模型，預測圖片對應的：  
- AQI（空氣品質指數）  
- PM2.5（細懸浮微粒濃度）  
輸出：YU_regression.csv，內容：
- Filename、AQI_true、AQI_pred、PM2.5_true、PM2.5_pred  
---
技術使用：
- Python 3.9<br>
- PyTorch / torchvision<br>
- matplotlib<br>
- ResNet18 預訓練模型<br>
