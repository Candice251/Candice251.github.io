# Hi, I'm Candice 👋
### 國立陽明交通大學 | 資訊管理與財務金融學系

具備機器學習、NLP 與 LLM 應用的實作經驗，能獨立執行從資料清洗、特徵工程到模型部署的完整 Pipeline。

## 工作經歷

**[Fiisual](https://tw.fiisual.com/product) | 資料科學實習生 | 2026.01 – 至今**

- 獨立建構全台房價預測系統，處理逾 100 萬筆實價登錄資料，採 LightGBM + 10-Fold CV 建模，六都 R² 達 0.75–0.84，RMSLE 控制在 0.13–0.16
- 設計 K-means 空間聚類特徵捕捉局部地段溢價，串接捷運、台鐵、高鐵、商圈開放資料計算空間距離特徵，經 SHAP 驗證聚類特徵重要性排名第一
- 自定義 30+ 個財經標籤庫，以 Embedding + Cosine Similarity 篩選候選集，串接 LLM API 進行 Zero-shot 標注，訓練 LinearSVM 多標籤分類模型達成 Micro F1 0.76、AP 0.84
- 參與爬蟲開發、資料庫寫入（SQL、MongoDB），產出結果串接前端系統已上線

## 專案

**[全台房價季度預測模型](https://github.com/Candice251/Housing-Price-Prediction-Model)**
`Python` `LightGBM` `SHAP` `GeoPandas`

處理 2012–2026 Q1 共 55 季、逾 100 萬筆實價登錄資料，建立每季可更新的全台房價預測系統。產出各縣市／行政區／屋齡區間／房屋類型的季度房價分佈指標，串接前端系統上線供使用者查詢。

**[財經新聞多標籤自動分類系統](https://github.com/Candice251/News-Tagging)**
`Python` `Sentence Transformers` `Groq LLM` `LinearSVM`

在零人工標注的前提下，透過 Embedding 篩選、LLM Zero-shot 標注、LinearSVM 訓練的三段式架構解決冷啟動問題，達成 Micro F1 0.76、AP 0.84，部署對公司十幾萬篇新聞進行批次自動標注。

**[BERT 美股新聞情緒分析](https://github.com/Candice251/Market-Sentiment-Analysis)**
`Python` `BERT` `yfinance`

微調 BERT 模型達成財經新聞情緒分類準確率 84.23%（較 Baseline +13%）。透過時間平移分析發現昨日情緒與今日報酬呈 −0.61 負相關，識別出符合情緒過度反應假說的反向預測訊號。

## 技能
- **機器學習／LLM**：LightGBM、BERT、Scikit-learn、PyTorch、SHAP、Sentence Transformers、LLM API 串接、Prompt Engineering
- **資料處理**：Pandas、NumPy、特徵工程（K-means、Target Encoding）、GeoPandas、Geopy
- **程式語言**：Python、SQL、R、C++
- **資料庫**：MySQL、MongoDB

---

## 聯絡我
* **Email**: candice251778@gmail.com
