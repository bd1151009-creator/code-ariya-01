# 曹亦天 - 個人簡介網站 (Personal Card Website)

這是一個極簡、現代且亮麗風格的個人單頁網站，專為展示個人簡介、技能與聯絡資訊所設計。

---

## 🌟 網站特色

- **鮮豔亮麗視覺**：採用活力漸層背景與玻璃質感（Glassmorphism）卡片設計。
- **精簡響應式排版**：專為手機與電腦螢幕優化的單頁 layout。
- **個人頭像預留區**：頂部設置圓形質感大頭照位置，懸停時具備互動效果。
- **一鍵複製聯絡資訊**：包含 Email 與 Line ID 的快捷複製按鈕，並附帶動態 Toast 提示。
- **快速跳轉連結**：支援直接開啟 Instagram 個人主頁。

---

## 🛠️ 使用技術

- **HTML5** / **JavaScript (ES6+)**
- **Tailwind CSS**（透過 CDN 引入，免安裝環境）
- **FontAwesome 6**（圖示庫）
- **Google Fonts**（Plus Jakarta Sans / Noto Sans TC）

---

## 📸 如何替換個人照片？

開啟 `index.html` 檔案，搜尋 `id="avatar-img"`，並將 `src` 屬性更改為您的圖片網址即可：

```html
<!-- 範例：替換為您的照片 URL -->
<img id="avatar-img" src="您的照片網址.jpg" alt="曹亦天的大頭照" ...>
```

---

## 🚀 如何執行專案？

1. 下載 `index.html` 與 `README.md` 至同一資料夾。
2. 直接使用任何瀏覽器（Chrome, Edge, Safari 等）雙擊開啟 `index.html` 即可瀏覽網站。