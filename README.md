## 🚀 開發與測試指南 (Development and Testing)

### 🧪 假資料模式切換 (Mock Data Toggle)

為了方便進行介面 (Layout) 調整和本地測試，您可以透過 URL 參數快速切換到假資料模式，而無需修改程式碼。

#### 預設模式 (Default Mode / Real API)
直接開啟網頁，系統會調用真實的氣象 API：
**範例 URL:**
http://localhost:5500/index.html

#### 假資料模式 (Mock Data Mode)
在 URL 後方加上 `?mock=true`，系統會載入本地的 `mock_weather_data.json` 檔案：
**範例 URL:**
http://localhost:5500/index.html?mock=true
當假資料模式啟用時，網頁左上角的地區標籤旁會顯示「**假資料模式**」的提示。
