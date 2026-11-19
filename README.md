# longfrom

捲動式數據故事網頁。每一頁都是單一 HTML 檔，不需要建置，直接用 GitHub Pages 發佈。

## 網頁

| 頁面 | 線上網址 | 原始檔 |
|---|---|---|
| **ILLIT 數據誌** | https://yichieh0802.github.io/longfrom/illit.html | [illit.html](illit.html) |
| **台灣海廢之潮** | https://yichieh0802.github.io/longfrom/ | [index.html](index.html) |

## ILLIT 數據誌

ILLIT（아일릿）從 2024 年出道到 2026 年首張 Billboard 200 前十專輯的捲動式數據故事。

- **成員**：五位成員卡片（照片、生日、國籍、出道年齡），附出道年齡分布圖
- **〈Magnetic〉的紀錄**：Hot 100 #91、Global 200 #6、Spotify 2 億／5 億串流里程碑
- **Billboard 200 名次**：捲動時圖表固定，名次從 #93 → #94 → #171 → #26 → #6 逐張出現
- **大事記**：從《R U Next?》到 BREAK EVEN，搭配各時期團體合照；桌機版右側有跟著捲動切換的「NOW PLAYING」面板
- 手繪 SVG 貼圖、深色模式、手機版版面，並支援「減少動態效果」設定

圖表使用 [D3.js](https://d3js.org/)（由 cdnjs 載入）。

### 資料與照片來源

- 榜單與串流數據整理自公開報導（Billboard、Soompi、The Straits Times、Pinkvilla、Asia Economy、The Korea Herald、Wikipedia），截至 2026 年 11 月；完整連結列於頁尾。部分日期僅標示到月份。
- 照片來自 [Wikimedia Commons](https://commons.wikimedia.org/wiki/Category:Illit)，授權為 CC BY 3.0 / CC BY 4.0，攝影者標註於每張照片與頁尾。
- 本頁為非官方粉絲向數據頁。

## 本機預覽

直接用瀏覽器開啟 HTML 檔即可；照片與圖表套件需要網路連線。

## 更新網站

推送到 `main` 後，GitHub Pages 會自動重新部署，通常一兩分鐘內生效。
