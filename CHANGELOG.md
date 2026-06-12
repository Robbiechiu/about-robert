# CHANGELOG — 羅伯特農業科技 數位名片頁

線上網址：<https://robbiechiu.github.io/about-robert/>
Repo：`Robbiechiu/about-robert`（GitHub，public）

> 由新到舊。每次 `git push origin main` 後 GitHub Pages 會自動重新部署（約 30–60 秒）。

---

## 2026-06-13

### 社群區 3＋3 排版
- 六個社群連結改成固定兩排、每排三個：
  - 上排：**LINE ・ 個人臉書 ・ 農場臉書**
  - 下排：**IG 個人 ・ IG 農業科技 ・ IG 農場**
- 修正聯絡卡的 Email（`robert.horti.tech@gmail.com`）因不可斷行造成的版面溢出（加 `min-width:0` + `overflow-wrap:anywhere`）。

### 德馳品牌對外不公開（防冒用）
- 生產品牌：`德馳未來農場 / DECHI FUTURE FARM` → **`未來農場 / FUTURE FARM`**
- 貿易：`德馳國際 / DECHI INTERNATIONAL` → **`國際貿易 / INTERNATIONAL TRADE`**（標籤一併改成「貿易通路」避免與名稱重複）
- 移除頁尾與事業版圖中的「以德為本，馳向未來」標語（德馳 motto）。
- 全頁已無任何「德馳 / DECHI」字樣。

## 2026-06-12

### hero 主視覺
- 換上重新裁切的溫室照（`assets/greenhouse-hero.jpeg`），構圖置中（`object-position:center`）。
- 「上亮下暗」處理：`filter:brightness(1.12)`＋上半透、下半深色漸層，讓生菜/溫室看得清、文字仍凸顯。

### 標題與品牌字
- 首屏品牌「羅伯特農業科技」：宋體 → 黑體（`Noto Sans TC`，weight 600），金色 `--gold`（與英文 ROBERT HORTI-TECH 同色）。
- 英文 `ROBERT HORTI-TECH` 靠左、與中文對齊。
- 修正英文副標被切問題（縮字距、`white-space:nowrap`）。

### 戰績數字卡（4 格）
- 內容定版：**土耕 66 倍 ・ 水耕 10 倍 ・ 每公頃年產 1000 噸 ・ 米其林餐廳指定**。
- 移除「5 年」「IRR 45%」（IRR 屬募資敏感，不公開）。
- 米其林：用**自繪 SVG 花形星標（florette）×3**（非米其林官方商標檔；商標風險已向業主說明）。花標大小對齊「1000」數字。

### 聯絡方式
- 一鍵存入通訊錄（vCard，含姓名/電話/Email/兩個地址）。
- 兩個地址：羅伯特農業科技（台中市中興街 359 號 14 樓之 3）、羅伯特農場（苗栗縣卓蘭鎮西坪里西坪 125-10 號）。
- LINE 改為可點按鈕（`https://line.me/ti/p/ZOqlzwtyOY`）；IG ×3、FB ×2 皆為可點按鈕。
- 三張 IG QR 已裁掉裝飾背景並統一尺寸（後改為按鈕，QR 圖檔保留在 `assets/` 未使用）。

### 關於我
- 加入創業時間軸 4 里程碑：英國材料×復盛 PM（協助 TaylorMade 量產）→ 跨國 0→1（東莞模具/柬埔寨地產，能源燃料棒與碳纖維帶過）→ 羅伯特農場魚菜共生五年 → 全環控自動化溫室。
- 興趣縮小放「工作之外的我」：瑜伽 → 高爾夫 → 攝影。
- 經歷來源：業主簡報 `CXO_AI_Robert.pptx`。

### v1 初版
- 單頁 `index.html`，深綠×金、滿版照、宋體標題＋蘋方內文，RWD 手機優先。
- 上線 GitHub Pages。
