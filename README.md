# 基於深度遷移學習的糖尿病視網膜病變分類
### A 數據
#### 1.資料來源 : Kaggle 糖尿病視網膜病變分級競賽 (diabetic-retinopathy-classification-3) 的資料集。
https://www.kaggle.com/competitions/diabetic-retinopathy-classification-3/overview
#### 2.資料規模 : 測試集：1,465 張。訓練/驗證集：共 2,197 張，依據病變嚴重程度分為 0 到 4 個等級

### B.模型 (Model)
#### 1.採用 深度遷移學習 (Deep Transfer Learning)。
#### 2.使用 ResNet50 預訓練模型
#### 3.凍結模型參數使訓練速度變快，不會破壞預訓練的特徵

### C.訓練與優化 (Training)
#### 1.優化器採用 Adam 優化器

### D.結果與評估
#### 1.kaggle的評分
#### --- Advanced Baseline --- 0.72218
#### ---- Medium Baseline ---- 0.56730
#### 本次成績:0.79863


