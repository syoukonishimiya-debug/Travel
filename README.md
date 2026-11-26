# 北海道 7 日行程網站（2027.1.9–15）

3 人、7 日、札幌單一基地的北海道冬季行程網站。單一 HTML 檔，無框架、無後台。

## 內容

- **142 個選擇**：景點 50、餐廳 50、活動 30、動漫 6、酒店 6
- 每項有 **推薦排名**、推薦原因、位置／費用／時間／交通、貼士、Google 地圖
- **預算計算機**：可改人數、匯率、消費檔次、房型、裝備，即時重算
- 七日行程時間軸
- 篩選（全部／景點／活動／動漫／酒店／餐廳）

## 部署到 GitHub Pages

1. 開 repository → **Settings** → **Pages**
2. Source 揀 **Deploy from a branch**
3. Branch 揀 **main**、folder 揀 **/(root)** → **Save**
4. 等大約 1 分鐘，網址會係：
   `https://<你的用戶名>.github.io/<repo名>/`

想用最短網址（`https://<用戶名>.github.io/`），把 repository 命名為 `<用戶名>.github.io`。

## 更新內容

用任何文字編輯器開 `index.html`：

| 想改 | 搜尋 |
|---|---|
| 卡片標題／介紹 | `title:"` |
| 推薦排名 | `rank:` |
| 七日行程 | `const PLAN` |
| 預算數字 | `BUDGET_ROWS` |
| 裝備清單 | `const GEAR` |

## 注意

- 照片來自 Wikimedia Commons（CC 授權），僅作示意，需要網絡連線；離線會自動變成漸變底色＋emoji。
- 價格為 2026 年 11 月估算，出發前請以官網為準。
- 網頁冇追蹤、冇 cookie。
