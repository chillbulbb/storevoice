# 店聲 StoreVoice - AI 商家評論分析與商圈對標平台

> **AI 商家評論分析、商圈競品對標與營運 ROI 成長驗證引擎（桃園示範區）**

StoreVoice 是一款針對餐飲與零售商家打造的現代化分析平台，結合 Google Maps 地理圖資、店家評論情緒分析、顧客痛點診斷、同業 PK 擂台及營運 ROI 成長雙折線驗證模型。

---

## 🌟 核心特色

1. **互動式商圈地圖**：整合 Leaflet 地圖，免 API Key 即可流暢瀏覽店家位置、星等、自訂 Pin 標記與即時視角平移。
2. **三維度 Dashboard 分流（仿 Google Maps 極簡導覽風格）**：
   - 📊 **總覽**：情感圓餅圖、人氣關鍵字、Phase 1 AI 新客行銷文案卡片。
   - 🛡️ **公關**：主題維度評分表、Phase 2 顧客負評痛點剖析與智慧公關回覆模組。
   - ⚔️ **同業**：Phase 3 商圈同業 PK 擂台與營運成長 ROI 驗證雙折線圖。
3. **即時全域搜尋與分類篩選**：支援店名、地址、招牌菜與關鍵字模糊搜尋，分類膠囊無死角切換。
4. **雙軌資料架構**：支援從 `stores.json` 非同步載入，並內建本地 Fallback 備援資料庫，離線雙擊開啟亦能 100% 完整運行。
5. **RWD 行動端體驗**：專為手機端設計之拉長雙列浮動切換列與原生 Web Share API 分享功能。

---

## 🚀 快速開始

### 方式一：直接雙擊開啟
雙擊打開 `StoreVoice.html` 即可直接在瀏覽器中離線運行。

### 方式二：本機 HTTP 伺服器
```bash
# 使用 Python 快速啟動本地伺服器
python3 -m http.server 8080
```
瀏覽器開啟：`http://localhost:8080/StoreVoice.html`

---

## 📁 檔案結構

- `StoreVoice.html` - 完整前端單一頁面應用程式（SPA），整合 Tailwind CSS、Leaflet、Chart.js。
- `stores.json` - 示範店家結構化資料庫（包含 7 家桃園代表性餐廳完整資料）。
- `README.md` - 專案說明文件。

