# UrDigi 飲食紀錄 APP

一款免下載、免註冊、無廣告的 PWA 飲食紀錄工具。

## 功能特色

- 📸 **AI 視覺辨識** — 拍照即可辨識食物熱量與三大營養素（Gemini 1.5 Pro）
- 🔍 **條碼掃描** — 掃描商品條碼自動查詢營養資訊（Open Food Facts API）
- 📊 **營養素圖表** — Chart.js 圓餅圖呈現蛋白質/碳水/脂肪比例
- 💾 **本地儲存** — 無需帳號，使用 LocalStorage 記錄飲食歷史
- ⚖️ **體重追蹤** — 體重趨勢紀錄
- 📱 **PWA 支援** — 可加入手機主畫面，離線使用

## 技術架構

- 純 HTML5 / CSS3 / Vanilla JS（單頁應用）
- Chart.js 圖表
- Gemini 1.5 Pro API（食物 AI 辨識）
- Open Food Facts API（條碼商品資料）
- PWA Manifest + Service Worker

## 使用方式

直接開啟 `index.html` 或部署至任何靜態網頁服務（GitHub Pages、Netlify 等）。

---

**開發者：** Bart (CTO) @ UrDigi  
**品牌：** [UrDigi](https://urdigi.com)
