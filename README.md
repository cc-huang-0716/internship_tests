# internship_tests

這個資料夾整理實習期間建立的測試型 notebook，內容以沙盒實驗、模型流程測試與資料處理雛形為主。

## 檔案說明

| 檔案 | 簡介 |
|---|---|
| `隨機序列產生器.ipynb` | 產生多筆穩定時間序列圖像，並輸出為圖片資料集與壓縮檔。 |
| `timeseries_handcraft.ipynb` | 手刻時間序列異常偵測流程，包含 ADF 概念、AR 殘差、leverage 判斷與 ARCH 檢定雛形。 |
| `yolov8n.ipynb` | 整理異常與正常時間序列圖片資料，建立 YOLO 格式資料集，並使用 YOLOv8n 進行訓練、預測與驗證。 |
| `negative_news_classification.ipynb` | 負面新聞分類實驗，使用文字資料前處理與深度學習模型進行情緒或負面內容判斷。 |
| `RAG.ipynb` | 讀取 PDF 法規文件，進行關鍵字分析、chunking 參數測試、共現矩陣與查詢擴充。 |
| `RAG_Chunking_research.ipynb` | 比較不同 chunking 方法，包含 recursive chunking 與 semantic splitting 的研究測試。 |
| `hilbert_huang.ipynb` | Hilbert-Huang Transform 相關實驗，用於時間序列訊號分解與特徵觀察。 |
